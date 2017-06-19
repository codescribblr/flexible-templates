# Flexible Templates for ACF PRO
WP Plugin that allows saving templates of the "Flexible Content" field, for easy and fast use of them on other pages. 

## Install / How to use
Install as any other wp plugin and activate. 

When you go to page that has Flexible Content, you'll notice a button on top left corner with saved templates. Hover the button to see a dropdown with template selection, click the template name to load it. Be aware that loading the template will overwrite the existing one. You also able to delete templates from there, by pressing the "minus" button/circle.

To save your template, go to the bottom of your Flexible Content field, you will see the input field for the name of your tempalte and save button. Before saving plugin checks for the already existing template with name you input, every template name have to be unique.

## How it works?
ACF saves all the field values to own meta. But to save templates, we created a new table in DB for storing them, as we store the HTML code that has been generated by the plugin to show the layout in Flexible Content field. This way we save all the fields and values in one place. When loading it back to Flexible Content field, we than have save/update page, as this reinitializes the fields like "Wysiwyg Editor".

## Contributors
I would like to avoid saving the page after the template is loaded, but couldn't find a solution yet, to reint the tinymce plugin. If you have and ideas or a solution for the issue, please contribute! :)
