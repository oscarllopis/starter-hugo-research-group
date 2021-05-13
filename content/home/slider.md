---
widget: slider
headless: true  # This file represents a page section.
# Order that this section appears on the page.
weight: 20

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 7000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "calc(100vh - 70px)"


item:
  - title: Bienvenidos
    content: 'EMPINNOVA'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    # overlay_color: '#666'  # An HTML color value.
    overlay_img: 'coders.jpg'  # Image path relative to your `assets/media/` folder
    # overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Nuestras soluciones
    cta_url: 'soluciones'
    cta_icon_pack: fas
    cta_icon: graduation-cap
  - title: Nuestras especialidades
    content: 'Somos expertos en emprendimiento e innovación'
    align: left
    overlay_color: '#555'
    overlay_img: ''
    overlay_filter: 0.5
  - title: Seminario Online
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
    cta_label: Apuntante aquí
    cta_url: 'event/example'
    cta_icon_pack: fas
    cta_icon: graduation-cap

---
