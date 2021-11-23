+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 3000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "calc(100vh - 70px)"
#height = "600px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  #title = "2021 PAGK Annual Meeting"
  #content = "Donggang B, The K Hotel, Seoul"
  align = "right"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/2021-pagkkr-header.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Details"
  cta_url = "https://www.pagk.kr/post/2021-11-26-annual-meeting"
  cta_icon_pack = "fas"
  cta_icon = "camera"

[[item]]
  title = "2021-2022 신임회장"
  content = "LG화학 이지은 박사"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/lee.jpg"  # Image path relative to your `static/img/` folder.
  #overlay_filter = 0  # Darken the image. Value in range 0-1.
  cta_label = "인사 영상"
  cta_url = "https://www.youtube.com/watch?v=k5ZiatceTLk"
  cta_icon_pack = "fas"
  cta_icon = "camera"
+++
