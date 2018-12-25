# Extension Starter
A Cosmic JS Extension Starter

### Installation
1. Download the .zip file in this repo
2. [Login to Cosmic JS](https://cosmicjs.com) and go to Your Bucket > Settings > Extensions > Add Extension

#### extension.json file properties
Key | Type | Description
--- | --- | ---
| title     | String | Function title
| font_awesome_class      | String | Icon to display in the Bucket sidenav
| image_url      | String | Image thumbnail
| repo_url      | String | Extension source code url

Example `extension.json` file:
```json
{
  "title": "Extension Starter",
  "font_awesome_class": "fa-puzzle-piece",
  "image_url": "https://cosmicjs.com/images/marketing/logo-w-brand.jpg",
  "repo_url": "https://github.com/cosmicjs/extension-starter"
}
```
