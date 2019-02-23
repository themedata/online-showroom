+++
description = "about online showroom"
draft = false
iscjklanguage = false
title = "About Showroom Theme"
type = "presentation"

[[gmgt_section]]
id = "gt_cover"
partial = "goandtalk/cover/default"

  [gmgt_section.data]
  card_font_size = 3.0
  card_font_weight = 1.0
  card_letter_spacing = "tracked"
  card_text_align = "tc"
  content = "with innovation."
  description = "with innovation. "
  intro = "Go and Talk"
  title = "Make a Difference"
  title_color = "gold"
  title_font_family = "baskerville"
  title_font_size = -5.0
  title_font_weight = 4.0
  title_letter_spacing = "tracked"

    [gmgt_section.data.appearance]
    trigger_class = "slide-trigger"
    section_background = "bg-primary-color-light"

    [gmgt_section.data.cta]
    background_color = "bg-black-20"
    button_text_color = "white-90"
    name = "Play Slides ->"
    pv = 1.0
    title = "view page as slides. "
    url = "#"

    [gmgt_section.data.image]
    animation = "slowUp"
    flow_end = true

    [gmgt_section.data.menu]

      [[gmgt_section.data.menu.global]]
      url = "/about/"
      name = "About"
      menu = "global"
      identifier = ""
      pre = ""
      post = ""
      weight = 0.0
      parent = ""

      [[gmgt_section.data.menu.global]]
      url = "/product/"
      name = "All Products"
      menu = "global"
      identifier = ""
      pre = ""
      post = ""
      weight = 0.0
      parent = ""

      [[gmgt_section.data.menu.global]]
      url = "/popular/"
      name = "Most Popular"
      menu = "global"
      identifier = ""
      pre = ""
      post = ""
      weight = 0.0
      parent = ""

      [[gmgt_section.data.menu.global]]
      url = "/new/"
      name = "New"
      menu = "global"
      identifier = ""
      pre = ""
      post = ""
      weight = 0.0
      parent = ""

      [[gmgt_section.data.menu.iconmenu]]
      url = "#"
      menu = "iconmenu"
      identifier = ""
      pre = "Facebook"
      post = ""
      weight = 0.0
      parent = ""

[[gmgt_section]]
id = "gt_content"
partial = "goandtalk/content/text-block"

  [gmgt_section.data]
  image_column_width = 100.0
  image_opacity = 100.0
  card_overlay = 0.0
  card_width = 100.0
  image_height = 100.0
  image_layer = "absolute"
  image_under_text = false
  cta_display = "dn"
  quote_display = "dn"
  title_font_family = "handwriting"
  title_color = "primary-color"
  title_ph = "0"
  title_pv = "3"
  title_font_size = "2"
  title_align = "tc"
  title_transform = "ttc"
  title_font_weight = "7"
  card_font_size = "5"
  card_font_weight = "4"
  image_br = "br0"
  object_fit_class = "of-scale-down"
  height_reference = "h"
  image_order = "even-order-1-ns"

    [gmgt_section.data.cta]
    url = "#"
    name = " Quick Start "
    background_color = "bg-light-gray"
    button_text_color = "mid-gray"
    border_color = "b--light-gray"
    border_radius = "br0"
    block_button_width = 50.0
    ph = 3.0
    pv = 2.0
    mv = 3.0
    icon_mask = "circle"
    inner_icon = "info"
    inner_icon_transform = "shrink-4"
    button_font_size = "4"
    align = "center"

    [gmgt_section.data.appearance]
    section_background = "bg-white-60"
    slide_animation = "fadeIn"

    [gmgt_section.data.image]
    responsive = false

    [gmgt_section.data.base_image]
    responsive = false

    [gmgt_section.data.bg_icon]
    icon_mask = "square"
    inner_icon = "font"
    inner_icon_transform = "shrink-6"
    bg_icon_display = "dn"

[[gmgt_section]]
id = "gt_footer"
is_global = true
partial = "goandtalk/footer/default_footer"
+++

Online showroom is a theme for Go and Talk page builder. It can be used to showcase your  products or projects, quickly of course. 

## Theme Highlight

This theme demonstrates the use of global sections in Go and Talk page builder. A global section applies to the whole site. It is created once, and used everywhere. The section about product categories and sub categories are both global sections in this theme.

Global section can be created and updated on any page, and changes to a global section apply to new pages built afterwards. If you have already created many pages but changed the global section later, you can use Go and Talk premium theme for Hugo to batch update the whole site. 

## How to Use This Theme

* if you are using Github Pages or Gitlab Pages, create an organization first
* fork this repository under the organization you have created. Please replace [orgname] below with the actual organization name.
  - On Github the repository should be named [orgname].github.io
  - On Gitlab the repository should be named [orgname].gitlab.io 
* alternatively you can download as a zip file and upload to your web server.

The sample pages will be available under [orgname].github.io, [orgname].gitlab.io or your custom domain name. 

Gitlab Pages will automatically publish the sample pages using the configuration from the file .gitlab-ci.yml at the room of this repository.

## Navigation Links

The navigation links are the same as your folder structure. You can rename the folder to reflect your products or projects, and update the navigation links accordingly.

## Editing a Page

There is an edit link at the bottom of every page. You can click on the edit link and create content in the browser. When you are done, export the page as web page and save as index.html file to your repository or web server, under the appropriate folder or subfolder.

The page content is automatically saved in a database in your browser while you type. Please refer to [Go and Talk page builder tutorials](https://builder.goandmake.app) on how to quickly create contents, add or remove sections.

## Creating a New Page

Each page on your site is represented by a subfolder with two files, index.html,  and index.goandmake.html. The file index.html is the content for the public, and index.goandmake.html is the editable page with page builder. 

You can create a new subfolder for a new page, and copy index.html and index.goandmake.html from a similar page. Navigate to the editable page, and update it with new contents. To publish the new page, export the page as web page and save it as index.html under the new subfolder 

## License

This theme and website template are licensed under [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/). 

[Go and Talk page builder](https://builder.goandmake.app) is free for non-commercial use. 

A license is required to use the theme template and page builder for commercial uses. 

