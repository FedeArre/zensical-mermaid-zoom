# Zensical Mermaid zoom

This is a little plugin for Zensical that adds a zoom button on the bottom-right of Mermaid charts, which opens a pop-up where users can freely move and zoom into the chart.

<img width="926" height="235" alt="image" src="https://github.com/user-attachments/assets/ae637765-3102-4094-9ca5-a72a42292cba" />


<img width="1836" height="828" alt="image" src="https://github.com/user-attachments/assets/3e169083-4467-4009-98a2-77d5434abaf4" />

## Installation

I recommend you create a "javascripts" and a "stylesheets" folder inside "docs" folder, as the [Zensical docs show](https://zensical.org/docs/customization/#additional-css). 

Simply drag & drop the code respectively (.js into javascripts and .css into stylesheets), and then register them into your `zensical.toml`

```
extra_css = ["stylesheets/mermaid-zoom.css"]

extra_javascript = ["javascripts/mermaid-zoom.js"]
```

With this, the zoom button will be available for all Mermaid charts of your docs.
