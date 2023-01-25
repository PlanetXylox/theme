# theme
Planet Xylox theme manager

## The image files

You can use a photo editor to make the template colors you want

## The CSS files

You see the CSS file in the repo but you can edit the HEX colors in them to match the theme.

* style-[name].css

[nsme] being the theme name of choice.

## themes.json

You can add theme and the details.

Types are 'classic', 'seasonal',

for the 'seasonal' type, add: `"time": ["0125", "0201"]`

Theme will be the default until 01/25 to 02/01

```
{
"name": "[name] Theme",
"id": "[name]",
"css": "-[name]",
"type": "[classic|seasonal]",
"enabled": true,
"default": true
}
```
