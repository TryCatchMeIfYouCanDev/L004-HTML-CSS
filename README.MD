# HTML Anchors #

A structured summary and organised notes from a web development class on HTML `<a>` tags, including absolute, relative, internal anchors, and special links like email, telephone, WhatsApp, and social media.

---

## 1. Overview of Links ##

### 1.1 Absolute Links ###

Links that point to external websites.

```html
<a href="https://www.example.com" target="_blank" rel="noopener noreferrer">Visit our website</a>
```

### 1.2 Relative Links ###

Links that point to pages or resources within the same website using relative paths.

```html
<a href="/assets/documents/eng/courses.html">Our Courses</a>
```

### 1.3 Internal Anchors (Page Anchors) ###

Links to sections within the same page using `id` attributes.

```html
<h2 id="section2">Section 2</h2>
<a href="#section2">Go to Section 2</a>
<a href="#top">Back to Top</a>
```

### 1.4 Fake Links ###

Links with no destination, often used as placeholders.

```html
<a href="#">Click here</a>
```

### 1.5 Named Anchors (External + Internal) ###

Links that combine external pages with a specific section anchor.

```html
<a href="https://it.wikipedia.org/wiki/Roma#Istruzione">Culture in Rome</a>
```

---

## 2. HTML Element Types ##

### 2.1 Block Elements ###

* Occupy full width by default
* Can contain any elements
* Cause a line break after closing

```html
<div>This is a block element</div>
<p>Another block element</p>
```

### 2.2 Inline Elements ###

* Width depends on content
* Can only contain inline elements
* Do not force line breaks

```html
<span>This is inline</span>
<strong>Bold inline text</strong>
```

---

## 3. Special Anchors and Protocols ##

| Type               | Href Format                        | Example                                                              |
| ------------------ | ---------------------------------- | -------------------------------------------------------------------- |
| Email              | `mailto:`                          | `<a href="mailto:hello@example.com">Send Email</a>`                  |
| Email CC           | `mailto:?cc=`                      | `<a href="mailto:main@example.com?cc=cc@example.com">Send CC</a>`    |
| Email BCC          | `mailto:?bcc=`                     | `<a href="mailto:main@example.com?bcc=bcc@example.com">Send BCC</a>` |
| Email with Subject | `mailto:?subject=`                 | `<a href="mailto:main@example.com?subject=Hello">Subject</a>`        |
| Email with Body    | `mailto:?body=`                    | `<a href="mailto:main@example.com?body=Hello%20World">Body</a>`      |
| Telephone          | `tel:`                             | `<a href="tel:+391234567890">Call Us</a>`                            |
| SMS                | `sms:`                             | `<a href="sms:+391234567890">Send SMS</a>`                           |
| MMS                | `mms:`                             | `<a href="mms:+391234567890">Send MMS</a>`                           |
| WhatsApp           | `https://wa.me/`                   | `<a href="https://wa.me/+391234567890">Contact on WhatsApp</a>`      |
| Skype              | `skype:username?call`              | `<a href="skype:live:username?call">Call on Skype</a>`               |
| FTP                | `ftp://`                           | `<a href="ftp://ftp.example.com">Download via FTP</a>`               |
| File Local         | `file:///`                         | `<a href="file:///C:/path/to/file.txt">Open File</a>`                |
| Social Media       | `https://`                         | `<a href="https://twitter.com/username">Follow on Twitter</a>`       |
| YouTube            | `https://www.youtube.com/watch?v=` | `<a href="https://www.youtube.com/watch?v=ID">Watch Video</a>`       |
| Google Maps        | `https://www.google.com/maps?q=`   | `<a href="https://www.google.com/maps?q=Address">View Map</a>`       |
| Download PDF       | `https://`                         | `<a href="https://www.example.com/document.pdf">Download PDF</a>`    |
| Spotify            | `https://open.spotify.com/track/`  | `<a href="https://open.spotify.com/track/ID">Listen on Spotify</a>`  |

---

## 4. Image Anchors ##

Images can be displayed directly or used as clickable links.

```html
<img src="https://picsum.photos/300/300" alt="Sample Image" title="Sample Image">
<a href="https://www.example.com"><img src="logo.png" alt="Logo"></a>
```

**Tips:**

* Resize and compress images for faster loading (WebP, compressed PNG/JPEG).
* Keep logos under 20 KB for web use.
* Online tools: [TinyPNG](https://tinypng.com), [Squoosh](https://squoosh.app/), [WebP converters](https://webponize.org/).

---

## 5. Best Practices ##

* Provide descriptive `title` and `aria-label` attributes for accessibility.
* Minimise external HTTP requests (CSS, JS, images) to speed up page load.
* Use internal anchors for easy navigation.
* Optimise all media for web performance.
* Test page performance: [Google PageSpeed Insights](https://pagespeed.web.dev/).
* Consider mobile-first design principles.

---


**Useful Links**

1. https://www.w3schools.com/
2. https://tinypng.com/
3. https://webponize.org/
4. https://www.gimp.org/
5. https://github.com/nathan-osman/gimp-webp
6. https://squoosh.app/
7. https://convertio.co/it/webp-converter/
8. https://csscompressor.net/
9. https://pagespeed.web.dev/
10. https://html5test.com/



*End of Class Notes Summary*
