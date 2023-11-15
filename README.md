# groupmate Docs

## Custom Integration Guide
1. Download the [snippets/groupmate_picker.liquid](snippets/groupmate_picker.liquid) file
2. Upload this file into the snippets folder of your theme
3. Paste this liquid code `{% render 'groupmate_picker', product: product %}` in the place where you want the groupmate Picker to appear
4. At the top of `groupmate_picker.liquid`, you can adjust the behavior and appearance of the Picker with the settings below


## Available Settings

| Field Name                | Data Type      |
|---------------------------|----------------|
| swatch_size               | integer        |
| show_label                | boolean        |
| show_swatch_titles        | boolean        |
| disable_app_css           | boolean        |
| only_available_products   | boolean        |
| sort_order                | string         |
