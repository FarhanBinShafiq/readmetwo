# label-tooltip

<center>
   [Add Preview Image URL Here]
</center>

## Description
The label-tooltip plugin enhances SurveyCTO forms by adding an interactive tooltip to various field types, triggered by a customizable Font Awesome v5 icon. It displays additional information in a responsive popup card, ideal for providing contextual help or instructions for fields such as `select_one`, `select_multiple`, `integer`, `decimal`, `text`, `note`, and `datetime`.

## ✅ Key Features
🧩 **Interactive Tooltip**: Displays a dynamic tooltip for various form fields, enhancing user understanding.  
🎨 **Customizable Icon (Font Awesome v5)**: Use any Font Awesome v5 icon to trigger the tooltip. Browse icons here: [Font Awesome v5 Icons](https://fontawesome.com/v5/search).  
🗂️ **Supports Multiple Field Types**: Compatible with `select_one`, `select_multiple`, `integer`, `decimal`, `text`, `note`, and `datetime` fields.  
💬 **Responsive Popup Card**: Tooltip content appears in a styled, responsive popup with formatted text or instructions.  
❌ **User-Friendly Dismissal Options**: Close the tooltip using a close button, clicking the backdrop, or pressing the Escape key.

---

## Download the Plugin
[DOWNLOAD PLUGIN](label-tooltip.fieldplugin.zip)

---

## Default SurveyCTO Feature Support

| Feature / Property         | Support |
|----------------------------|---------|
| Supported field type(s)    | `select_one`, `select_multiple`, `integer`, `decimal`, `text`, `note`, `datetime` |
| Custom required message    | No      |
| Custom constraint message  | No      |
| Font Awesome v5 Icons      | Yes — [Font Awesome v5 Icons](https://fontawesome.com/v5/cheatsheet) |

---

## 🛠️ How to Use
Follow these steps to integrate and test the label-tooltip plugin in your SurveyCTO form:

1. 📥 **Download the sample form**  
   Grab the test form from [`extras/sample-form`](./extras/sample-form) and upload it to your SurveyCTO server.

2. 🎨 **Ensure Font Awesome v5 is available**  
   Ensure your SurveyCTO environment includes Font Awesome v5, specified via `all.css` in the `manifest.json` file.

3. 🧩 **Attach the field plug-in**  
   Download the plug-in file:  
   [label-tooltip.fieldplugin.zip](label-tooltip.fieldplugin.zip)  
   Attach it to the test form using SurveyCTO's field plug-in configuration.

4. ⚙️ **Set up parameters properly**  
   Provide the correct parameters in your form design.  
   **Example**:  
   ```text
   label-tooltip(icon_class="fas fa-user-tie", tools_text="You will collect data using imagine")
