## User Stories and Feature Tasks

*As a user, I want to have an application that looks good, is easy to use, and is updated often, so that I want to come back and use it frequently.*

- Working from the provided comp images, write CSS such that the browser rendering matches the images as closely as possible.
- Utilize the icon fonts located in `styles/icons.css` for navigation features as shown in the comp images.

*As a developer, I want to use standard industry practices for setting up and organizing the code that handles the styling of my application so that my code is easy to edit and maintain.*

- Utilize a [`normalize.css`](https://github.com/necolas/normalize.css/blob/master/normalize.css) file, which should be placed in a `vendor/styles/` directory, to override default browser settings that affect the way documents render.
- Utilize SMACSS practices to organize CSS into separate files and appropriately order the loading of those files in the `<head>` of the HTML document.

*As a user, I want a familiar experience of the application so that I know how to use it on my smartphone and occasionally my laptop.*

 - Initially design the application to render per the comp images on mobile devices.
 - Set up the viewport and fluid media rules so content renders per the comp images in both mobile and desktop views. Use a breakpoint of 640 pixels.
 - Add a "Hamburger" menu button that reveals the nav links when hovered over.
- Ensure that images are responsive and do not exceed the size of the viewport.
