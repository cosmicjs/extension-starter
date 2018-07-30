# Extension Starter
A Cosmic JS Extension Starter

### Installation
1. Download the .zip file in this repo
2. [Login to Cosmic JS](https://cosmicjs.com) and go to Your Bucket > Settings > Extensions > Upload Extension

#### extension.json file properties
Key | Type | Description
--- | --- | ---
| title     | string | Function title
| font_awesome_class      | string | Icon to display in the Bucket sidenav
| image_url      | string | Image thumbnail
| source_code_url      | string | Extension source code url

Example `function.json` file:
```json
{
  "title": "Extension Starter",
  "font_awesome_class": "fa-puzzle-piece",
  "image_url": "https://cosmicjs.com/images/marketing/logo-w-brand.jpg",
  "source_code_url": "https://github.com/cosmicjs/extension-starter"
}
```
