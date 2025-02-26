A Shopify section template.

Compatible with Dawn theme. To install, append this block under "featured_collection":

```
"custom-section": {
  "type": "custom-section",
  "settings": {
    "title": "Custom Section Title",
    "description": "Custom section description text"
  }
}
```

Get `tailwind.css` from the TailwindCSS CDN, and upload it to via your Shopify Admin's Assets page. Get the link to the uploaded CSS file, and insert the code to in the file `layout/theme.liquid`

`<script defer src="https://cdn.shopify.com/s/files/1/0726/6628/4263/files/tailwindcss.js?v=1740539956"></script>`

Replace the script `src` with the file you uploaded.

In the `sections` folder, create a new file called `custom-section.liquid` and copy the contents with the contents of this file:
`https://github.com/angelsoftph/wonderdrug/blob/master/sections/custom-section.liquid`

Demo: https://sxh10e-cn.myshopify.com/
