<a href="https://cosmicjs.com" target="_blank"><img src="https://cosmic-s3.imgix.net/70b26370-2012-11e9-8b75-9b9c29c68edc-main.jpg?w=1500" width="500" /></a>

# Cosmic JS Extension Starter
Extend the <a href="https://cosmicjs.com" target="_blank">Cosmic JS</a> dashboard experience. Cosmic JS Extensions enable you to:
- Create custom views in your Cosmic JS dashboard
- Connect to third-party APIs


### What is a Comsic JS Extension?
In short, it's a [JAMstack app](https://jamstack.org). It can be a simple static website, or complex web app, using front end web technology.


### Links
[Extension docs](https://cosmicjs.com/docs/extensions)

[Extension examples](https://cosmicjs.com/extensions/)


### Installation
1. Download the .zip file in this repo
2. [Login to Cosmic JS](https://cosmicjs.com) and go to Your Bucket > Settings > Extensions > Add Extension


### Required files
#### extension.json
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
  "font_awesome_class": "fa-rocket",
  "image_url": "https://cosmicjs.com/images/marketing/logo-w-brand.jpg",
  "repo_url": "https://github.com/cosmicjs/extension-starter"
}
```
#### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Extension Starter</title>
</head>
<body>
  <h1>Hello World! or whatever...</h1>
</body>
</html>
```
