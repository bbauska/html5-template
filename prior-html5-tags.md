<h2 id="2-html-tags">2. HTML Tags</h2>

**1. Title tag:**

Title tags are used by search engines to determine the subject of a page and display it in SERP. As a rule of thumb, titles that are under 60 characters long will fit on most screens. In HTML, a title tag looks like this:

```html
<title>Your Title Goes Here</title>
```

**2. Meta description tag:**

Meta description is a short paragraph of text used to describe your page in search results. The function of meta description is similar to the title. It provides a little more detail about your page and it helps users decide whether to visit your page or not. In HTML, a meta description tag looks like this:

```html
<meta name="description" content="Your description goes here">
```

**3. Heading tags:**

Headings (H1-H6) are used to split your page into sections or chapters. Each heading is like a small title within the page. In HTML, a heading looks like this:

```html
<h1>Your heading goes here</h1>
```

<div align="right">
    <b><a href="#toc">↥ back to top</a></b>
</div>

**4. Image alt attribute:**

The `alt` text attribute is a part of an image tag, and it provides a description for an image. Alt text plays a major role in image optimization. It makes your images accessible both to search engines (by telling them what a particular image means) and to people (by displaying an alternative text in case a particular image cannot be loaded or by helping screen readers convey images). In HTML it may look like this:

```html
<img src="url" alt="Your image description goes here">
```

**5. Open Graph tags:**

Open Graph (OG) tags are placed in the `<head>` section of a page and allow any webpage to become a rich object in social networks. OG tags let you control how the information about your page is represented when shared via social channels. This possibility may help you enhance the performance of your links on social media, thus driving more click-throughs and increasing conversions. In HTML, it can look like this:

```html
<meta name="og:title" property="og:title" content="Your Open Graph Title Goes Here">
```

**6. Robots tag:**

A robots tag is an element in the HTML of a page that informs search engines which pages on your site should be indexed and which should not. Its functions are similar to robots.txt, but robots.txt gives suggestions. Whereas robots tags give instructions. In HTML, it can look like this:

```html
<meta name="robots" content="index, follow">
```

**7. Canonical tag:**

A canonical tag is a way of telling search engines that a specific URL represents the master copy of a page. Using the canonical tag prevents problems caused by identical or "duplicate" content appearing on multiple URLs. Practically speaking, the canonical tag tells search engines which version of a URL you want to appear in search results. In HTML, it may look like this:

```html
<link href="URL" rel="canonical">
```

**8. HTML5 semantic tags:**

One of the most important features of HTML5 is its semantics tags. Semantic tags refers to syntax that makes the HTML more comprehensible by better defining the different sections and layout of web pages. It makes web pages more informative and adaptable, allowing browsers and search engines to better interpret content. For example, instead of using `<div id="header"></div>` you can use a `<header></hrader>` tag.

<!--
<p align="center">
    <img src="assets/images/semantic-tags.png" alt="HTML5 semantic tags" width="300px" />
</p>
-->
