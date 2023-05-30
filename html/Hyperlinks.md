# Hyperlinks
# Creating a hyperlink

```
<p> 
This is 
<a href="google.com">my link</a>.
</p>
```
<p> 
This is 
<a href="google.com">my link</a>.
</p>

# Block level links
Nearly everything can be made into a link.
```
<a href="https://developer.mozilla.org/en-US/">
  <h1>MDN Web Docs</h1>
</a>
<p>
  Documenting web technologies, including CSS, HTML, and JavaScript, since 2005.
</p>
```
Give us:
<a href="https://developer.mozilla.org/en-US/">
  <h1>MDN Web Docs</h1>
</a>
<p>
  Documenting web technologies, including CSS, HTML, and JavaScript, since 2005.
</p>

# Image links

```
<a href="https://developer.mozilla.org/en-US/">
  <img src="https://live-samples.mdn.mozilla.net/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks/mdn_logo.svg" alt="MDN Web Docs homepage" />
</a>
```
<a href="https://developer.mozilla.org/en-US/">
  <img src="https://live-samples.mdn.mozilla.net/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks/mdn_logo.svg" alt="MDN Web Docs homepage" />
</a>

## Supporting information

Title: appears as tooltip upon hovering link with mouse
```
<p>
  I'm creating a link to
  <a
    href="https://www.mozilla.org/en-US/"
    title="The best place to find more information about Mozilla's
          mission and how to contribute">
    the Mozilla homepage</a>.
</p>
```
<p>
  I'm creating a link to
  <a
    href="https://www.mozilla.org/en-US/"
    title="The best place to find more information about Mozilla's
          mission and how to contribute">
    the Mozilla homepage</a>.
</p>

# Document fragments

You can link to a specific part of a document using document fragments. To do this, assign an id attribute to the element you want to link to.

```
<h2 id="Mailing_address">Mailing address</h2>
```
Then link to it using a \#
```
<p>
    Want to write us a letter? Use our
    <a href="site.html#Mailing_address">mailing address</a>.
</p>
```
You can also link to parts of the same document, just omit the "```site.html```" in our previous example.

## Best practices

- Give links clear names and avoid repeating link names

- When linking to a non-HTML page, add clear wording to reduce confusion.

