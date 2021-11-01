+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true # Activate this widget? true/false
weight = 1  # Order that this section will appear.
title = ""

# Hero image (optional). Enter filename of an image in the `static/media/` folder.
hero_media = "Toad.png"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "#fff"
  
  # Background gradient.
  # gradient_start = "#4bb4e3"
  # gradient_end = "#000"
  
  # Background image.
  # image = ""  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = false

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[butn]
  url = "/authors/ErikKusch"
  label = "About me"
  
# [butn_alt]
#   url = "#contact"
#   label = "Contact me"

+++

## Hi. I'm **Erik Kusch**, a PhD student of **Ecoinformatics and Biodiversity** who creates and applies novel statistical methods to big-data.  

I aim to understand how global and local processes and patterns in biological systems come about and are reinforced thus generating knowledge about the resilience of the Earth's ecosystems. My PhD project is under the guidance of [Alejandro Ordonez](https://pure.au.dk/portal/en/persons/alejandro-ordonez-gloria(93af1df3-ce78-48c3-94fa-2317fa00bd4a).html) and co-supervised by [Roberto Salguero-Gómez](https://www.zoo.ox.ac.uk/people/dr-rob-salguero-gomez). 

<style>
.butn {
  background-color: inherit;
  padding: 14px;
  border-radius: 0px;
  border-width: 2px;
  border-style: solid;
  border-color: green;
  font-size: inherit;
  cursor: pointer;
  display: inline-block;
}

/* On mouse-over */
.butn:hover {background: #eee;}

.success {background-color: forestgreen;}
.info {background-color: #67da6f;}
.warning {background-color: orange;}
.danger {background-color: red;}
.default {background-color: inherit;}

}
</style>


<button class="butn default">[About Me](about)</button>
<button class="butn default">[Reach Me](contact)</button>