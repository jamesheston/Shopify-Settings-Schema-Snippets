Shopify Settings Schema Snippets
--------------------------------

For adding fields to the [new Shopify Theme editor](https://docs.shopify.com/themes/theme-development/storefront-editor/settings-schema) easier. Refer to the aforementioned link for further technical info on this Shopify feature.

Instructions
============

Just type `ngs` and an autocomplete dropdown will appear. Depending on your Sublime Text settings, hitting `control` + `spacebar` may be necessary to open dropdown menu.

The theme file you're editing is `theme/config/settings_schema.json`.

To start off, you'll want to insert the `ngs.init` snippet. This inserts the foundation for the file structure. For a new fieldset, which is represented in the Shopify Settings Editor as an accordian section, use `ngs.fieldset`. Also, note that to successfully upload a file, you've got have at least two fields inside a fieldset. Also, Shopify will deny your theme upload if there are any formatting errors. This will mostly be trailing commas.

I've put some effort into making the formatting consistent and clean in terms of indentation and comments. This could get a bit funky depending on your particular ST settings, but should be trivial to fix.