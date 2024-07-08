<div align="center">
  <h1>Sample Bunker App</h1>
</div>

## Installation & Building
- Install Packages ``npm i``
- Build the App ``rollup --config rollup.config.mjs``

## Usage
Please be aware that you should contain your App to ``App.svelte`` and any npm packages you choose to use.<br>
- Component Libraries like shadcn-svelte will not work due to using extra .svelte files.
- ``bits-ui`` and libraries like it that aren't wrappers should work
- ``lucide-svelte`` will work as well.

## App Configuration 
The configuration file for your App should be placed alongside the built files.
```json
{
    "name": "Sample App",
    "id": "cattn.app",
    "description": "Sample App for Bunker",
    "version": "0.0.1",
    "author": "cattn",
    "content": "App.js",
    "type": "tile",
    "url": "https://raw.githubusercontent.com/Cattn/sample-bunker-App/main/dist/"
}
```
- name
  - The name of your App
- id
  - The id of your App (``author``.``name``), must be all lowercase, no spaces.
- description
  - A brief description of your App. This will be shown in the Addon Manager.
- version
  - The version number of your App. Follow x.x.x scheme.
- author
  - Name of the user who created the App. Does not need to be lowercase & spaces allowed.
- content
  - Relative link to the built content. You shouldn't change this unless you know what you're doing.
- type
  - Should be set to ``app`` for Apps.
- url
  - Url that the App is avalible at. You may use a raw.githubusercontent.com link.

## Contributors
Created by [Cattn](https://github.com/Cattn)
