# Overlapping Content Example

This project demonstrates a simple HTML page where an overlay background with text is displayed on top of the main content. The overlay disappears when the window is zoomed in to a certain threshold, without saving the state permanently between page reloads. This is useful for creating page cloaks.

## Features

- **Main content**: A full-page background with centered text.
- **Overlay background**: A semi-transparent background with text that overlays the main content.
- **Responsive behavior**: The overlay is hidden when the window is resized below a set width (1000px in this case).

## How It Works

1. The main content is displayed on a full viewport.
2. The overlay content appears on top of the main content initially.
3. When the window width is resized to 1000px or below, the overlay content disappears.
4. The overlay content remains hidden for the duration of the session but will reappear if the page is reloaded or if the window is resized back above 1000px.
