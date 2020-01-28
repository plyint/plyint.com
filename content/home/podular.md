+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank_right"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 17  # Order that this section will appear.

title = "*podular*"
subtitle = ""

left_image = "plyint_podular.svg"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  color = "#eeeeee"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "headers/remote_network.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
---

Plyint is organized as a collection of small teams known as *"Pods"*.  Each pod is responsible for a **single product or large feature** end-to-end.  (i.e. From design all the way through production support)  This allows each product or major feature to be deployed and maintained independently.

Dependencies between products/features are handled using well-defined interfaces.  These interfaces are the **same** regardless of whether they are external or internal to the organization. This reduces complexity and ensures we are *"[dogfooding](https://en.wikipedia.org/wiki/Eating_your_own_dog_food)"* our own sofware. 

By using a small team approach, deep technical expertise and design consensus can be quickly reached.  This intimate knowledge of each product translates into higher quality software that meets the needs of our users.
