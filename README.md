# Fancy Tasks NG (Custom)

Forked from [daydve/FancyTasksNG](https://github.com/daydve/FancyTasksNG).

## Added Features

- **Custom Plasmoid ID (`io.github.daydve.fancytasksng-custom`)**: Installs as **Fancy Tasks NG (Custom)** so KDE Store updates do not overwrite custom changes.
- **Configurable Icon Hover Backing & Shrink** (*Appearance → Animation Options*):
  - **Hover backing** (`iconHoverBacking`, default enabled at `25%` opacity): draws a rounded theme-highlight backing rectangle behind hovered/active task icons.
  - **Hover shrink** (`iconHoverShrink`, default enabled at `85%` scale): smoothly shrinks the task icon on hover instead of zooming.
  - **Hover icon highlight flash** (`iconHoverHighlight`, default disabled): toggle for the `Kirigami.Icon` active highlight effect on hover.
- **Separate Audio Badge Toggle** (*Indicators*):
  - **Show audio icon on tasks playing sound** (`showAudioBadge`, default disabled): hides the corner audio badge overlay on task icons while keeping audio stream tracking and tooltip volume controls (`indicateAudioStreams`) active.
- **Live Preview Support**: All new hover and audio badge options are reflected in the settings dialog's Live Preview.
