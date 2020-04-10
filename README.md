# Machaera Altus Nox (Aurorae)

https://github.com/oversword/Machaera-Altus-Nox-Aurorae

Machaera Altus Nox is a modern, color-schemeable KDE Plasma theme, with a futuristic, mechanical design.

Known Issues:
 * This theme can take up a lot of (visual) space, it is not recommended for smaller screens
 * The title text color is not configurable through the color scheme - this is an issue with Plasma
    - To change this, you have to edit ActiveTextColor and InactiveTextColor inside Machaera-Altus-Noxrc
 * Only looks right when the window border size is set to "Huge"
    - I have tried using custom sizes but they are not working the same way as this setting
 * The window title bar is very large, this can be reduced, but only if the correct font is chosen (see next point)
    - Uncomment the second values for TitleEdgeBottom and TitleEdgeBottomMaximized in Machaera-Altus-Noxrc if you want to fix this
 * The window title text appears right next to the bottom of the title bar
    - To fix this, you can increase the font size, and/or choose a decorative font (these often have different baselines)

The recommended title font is Lethal Injector https://www.dafont.com/lethal-injector.font
