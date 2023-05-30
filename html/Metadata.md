# Metadeta in HTML

# Common metadata

\<meta name="author" content="Author Name">

\<meta name="description" content="Description of webpage">

Description is useful to include keywords for SEO.

---

# Proprietary Metadata

## Open Graph Data

This is a metadata protocol by Facebook.

### Attributes

property="og:image"
content="link-to-image"

property="og:description"
content="Description for Facebook"

property="og:title"
content="Title"

## Twitter Cards

Similar to OGD.

name="twitter:title" 
content="Title"

---

# Site Icons

## Favicon

"favorites icon"

Save in same directory as sites index page in .ico format

\<link rel="icon" href="favicon.ico" type="image/x-icon"/>

There are also other types of icons, i.e. for if your website is saved to an iPhone home screen.

--- 

# Adding CSS, JS

Specify document's stylesheet

\<link rel="stylesheet" href="style.css"/>

JS:

\<script src="file.js" defer></script>

Note how it's not a void element. Also the defer causes the JavaScript to be loaded after the HTML is parsed to avoid some possible errors.

---

# Setting language

\<html lang="en-US">\<html>

Good for SEO and screen readers.

## Setting language for specific parts of document

\<p>Japanese example: \<span lang="ja">ご飯が熱い。\</span>.\</p>