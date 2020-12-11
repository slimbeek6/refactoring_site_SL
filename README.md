# Refactoring the Horiseon Front Page

## Summary

The request from the client is to review and refactor their codebase to ensure the use of code that follows accessibility standards. This will also help optimize the codebase for search enginges.

In reviewing the codebase, I ensured that the source code contains semantic HTML elements, followed a logical structure, and includes alt and heading attributes to ensure search engine optimization

![Picture of Website](/assets/images/site.png)

<hr>

## Code Updates Made

There is now a title on the webpage of "Horiseon | SEO, Online PR, and Social Media Marketing" which does a better job of describing the page than the previous title of "website".

There are a number of new alt text descriptors to all of the images in the code to ensure that the page is accessible and optimized for search engines.


In the majority of the html, the different containers are all labeled as divs, rather than using semantic code.  The code is updated to include semantic elements like:

```
<body>
    <header class="header">
    <!-- Updated div to use header instead -->
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
        <!-- Updated div to use nav instead -->
```


In as many places as possible, I consolidate identical CSS code into a single class , including the benefit sections and the main section of the page.  As an example:

```
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```
Replaced by:
```
.benefit-content {
    margin-bottom: 32px;
    color: #ffffff;
}
```
<hr>

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Deployed Link

* [See Live Site](https://slimbeek6.github.io/refactoring_site_SL/)


## Authors

* **Shaun Limbeek** 

- [Link to Github](https://github.com/slimbeek6/)
- [Link to LinkedIn](https://www.linkedin.com/in/shaun-limbeek/)