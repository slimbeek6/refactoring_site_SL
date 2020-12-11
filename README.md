# Refactoring the Horiseon Front Page

## Summary

The request from the client is to review and refactor their codebase to ensure the use of code that follows accessibility standards. This will also help optimize the codebase for search enginges.

In reviewing the codebase, I ensured that the source code contains semantic HTML elements, followed a logical structure, and includes alt and heading attributes to ensure search engine optimization

![Picture of Website] (/assets/images/site.png)

## Code Updates Made


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

## Functionality Changes & User Guide


## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Deployed Link

* [See Live Site](#)


## Authors

* **Shaun Limbeek** 

- [Link to Portfolio Site](#)
- [Link to Github](https://github.com/)
- [Link to LinkedIn](https://www.linkedin.com/)