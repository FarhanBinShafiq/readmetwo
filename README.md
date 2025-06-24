
# label-tooltip

[Add Preview Image URL Here]

## Description

The label-tooltip plugin enhances SurveyCTO forms by adding an interactive tooltip to various field types, triggered by a customizable Font Awesome v5 icon. It displays additional information in a responsive popup card, ideal for providing contextual help or instructions for fields such as `select_one`, `select_multiple`, `integer`, `decimal`, `text`, `note`, and `datetime`.

## ✅ Key Features

🧩 **Interactive Tooltip**: Displays a dynamic tooltip for various form fields, enhancing user understanding.  
🎨 **Customizable Icon (Font Awesome v5)**: Use any Font Awesome v5 icon to trigger the tooltip. Browse icons here: [Font Awesome v5 Icons](https://fontawesome.com/v5/search).  
🗂️ **Supports Multiple Field Types**: Compatible with `select_one`, `select_multiple`, `integer`, `decimal`, `text`, `note`, and `datetime` fields.  
💬 **Responsive Popup Card**: Tooltip content appears in a styled, responsive popup with formatted text or instructions.  
❌ **User-Friendly Dismissal Options**: Close the tooltip using a close button, clicking the backdrop, or pressing the Escape key.

----------

## Download the Plugin

[DOWNLOAD PLUGIN](https://grok.com/chat/label-tooltip.fieldplugin.zip)

----------

## Default SurveyCTO Feature Support


| Feature / Property | Support |
|--|--|
|  Supported field type(s)|`select_one`, `select_multiple`, `integer`, `decimal`, `text`, `note`  |
| Custom  message| Yes|  
| Font Awesome v5 Icons| Yes — [Font Awesome v5 Icons](https://fontawesome.com/v5/cheatsheet) |


















## 🛠️ How to Use

Follow these steps to integrate and test the label-tooltip plugin in your SurveyCTO form:

1.  📥 **Download the sample form**  
    Grab the test form from [`extras/sample-form`](https://grok.com/chat/extras/sample-form) and upload it to your SurveyCTO server.
    
2.  🎨 **Ensure Font Awesome v5 is available**  
    Ensure your SurveyCTO environment includes Font Awesome v5, specified via `all.css` in the `manifest.json` file.
    
3.  🧩 **Attach the field plug-in**  
    Download the plug-in file:  
    [label-tooltip.fieldplugin.zip](https://grok.com/chat/label-tooltip.fieldplugin.zip)  
    Attach it to the test form using SurveyCTO's field plug-in configuration.
    
4.  ⚙️ **Set up parameters properly**  
    Provide the correct parameters in your form design.  
    **Example**:
    
    ```text
    label-tooltip(icon_class="fas fa-user-tie",  tools_text="You will collect data using imagine")
    
    ```
    

----------

## ⚙️ Parameters
|  COMPONENT|VALUE  | 
|--|--|
| Plugin Name | "label-tooltip" |
|  Parameter|"icon_class" |
|  Parameter| "tools_text" |



Parameter :"icon_class"-Specifies the Font Awesome v5 icon class for the tooltip trigger (e.g., "fas fa-user-tie").

Parameter :"tools_text"-Defines the tooltip text displayed in the popup card (e.g., "You will collect data using imagine").

**Notes**:

-   The `icon_class` parameter must reference a valid Font Awesome v5 icon class.
-   The `tools_text` parameter supports plain text or HTML for rich formatting in the tooltip.
-   Font Awesome v5 must be included (via `all.css` as specified in `manifest.json`) for icons to render correctly.
-   The tooltip is displayed as a fixed-position popup card that does not affect the form's layout, ensuring compatibility across devices.

## Example Usage

```text
label-tooltip(icon_class="fas fa-user-tie", tools_text="You will collect data using imagine")

```

'''''This example sets a user-tie icon and displays the message "You will collect data using imagine" in the tooltip popup when the icon is clicked.'''''

----------

## 👨‍💻 Author

Md. Farhan Bin Shafiq, Web Developer, SoTLab, [ARCED Foundation](https://arced.foundation/).

----------

## 📚 More Resources

### 📄 Sample Form

Find a sample form definition in this repo:  
[`extras/sample_form`](https://grok.com/chat/extras/sample_form)

### 🛠️ Developer Documentation

Detailed instructions for developing and using field plug-ins:  
[SurveyCTO Field Plug-in Resources](https://github.com/surveycto/Field-plug-in-resources)

### 🧑‍🏫 User Documentation

Learn how to get started with field plug-ins in your SurveyCTO form:  
[Using Field Plug-ins – SurveyCTO Docs](https://docs.surveycto.com/02-designing-forms/03-advanced-topics/06.using-field-plug-ins.html)
