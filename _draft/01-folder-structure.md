# 1. Sistema de carpetas.

  Centralizar todos los estilos en un mismo fichero (`main.css`, `style.css) que no contenga reglas, únicamente
  `@import` a otros ficheros.

  >_Puede haber más de uno dependiendo las necesidades. Por ejemplo en una guía de estilos, si tenemos soporte para algun navegdor concreto o si tenemos estilos que sólo se cargan en una página._

  > **Leer sobre HTTP2 a ver si es relevnte.**

#### Ejemplo: [7-1 Pattern](http://sass-guidelin.es/#the-7-1-pattern)

  7 Carpetas, 1 archivo:

```
  sass/
  |
  |– base/
  |   |– _reset.scss       # Reset/normalize
  |   |– _typography.scss  # Typography rules
  |   ...                  # Etc…
  |
  |– components/
  |   |– _buttons.scss     # Buttons
  |   |– _carousel.scss    # Carousel
  |   |– _cover.scss       # Cover
  |   |– _dropdown.scss    # Dropdown
  |   ...                  # Etc…
  |
  |– layout/
  |   |– _navigation.scss  # Navigation
  |   |– _grid.scss        # Grid system
  |   |– _header.scss      # Header
  |   |– _footer.scss      # Footer
  |   |– _sidebar.scss     # Sidebar
  |   |– _forms.scss       # Forms
  |   ...                  # Etc…
  |
  |– pages/
  |   |– _home.scss        # Home specific styles
  |   |– _contact.scss     # Contact specific styles
  |   ...                  # Etc…
  |
  |– themes/
  |   |– _theme.scss       # Default theme
  |   |– _admin.scss       # Admin theme
  |   ...                  # Etc…
  |
  |– utils/
  |   |– _variables.scss   # Sass Variables
  |   |– _functions.scss   # Sass Functions
  |   |– _mixins.scss      # Sass Mixins
  |   |– _helpers.scss     # Class & placeholders helpers
  |
  |– vendors/
  |   |– _bootstrap.scss   # Bootstrap
  |   |– _jquery-ui.scss   # jQuery UI
  |   ...                  # Etc…
  |
  |
  `– main.scss             # Main Sass file
```

  > Es recomendable ajustar esta estructura a las necesidades del proyecto y simplificarla eliminando las carpetas que no necesitemos.
