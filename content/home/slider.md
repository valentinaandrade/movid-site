+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 6  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "500px"


# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "<br><br><br><br><br><br>"
  content = ""
  align = "right"

  #overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/3.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.

  cta_label = "Más información"
  cta_url = "https://www.who.int/es/emergencies/diseases/novel-coronavirus-2019/advice-for-public"

[[item]]
  title = "La **pandemia** la enfrentamos <br>entre **todas/os**👊"
  content = "    "
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  #overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/1.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.3  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "¡Participa!"
  cta_url = "https://movid.netlify.app/terms/"
  cta_icon_pack = "fas"
  cta_icon = "pencil"

  [[item]]
    title = "<br>¿Qué hemos aprendido<br>hasta ahora?<br><br>"
    content = "    "
    align = "center"

    #overlay_color = "#555"  # An HTML color value.
    overlay_img = "headers/2.png"  # Image path relative to your `static/img/` folder.
    overlay_filter = 0.3  # Darken the image. Value in range 0-1.

  cta_label = "📚Ver informes"
  cta_url = "https://movid.netlify.app/informes/participante"

+++
