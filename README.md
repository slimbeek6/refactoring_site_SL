# Refactoring the Horiseon Front Page

## Summary

The request from the client is to review and refactor their codebase to ensure the use of code that follows accessibility standards. This will also help optimize the codebase for search enginges.

In reviewing the codebase, I ensured that the source code contains semantic HTML elements, followed a logical structure, and includes alt and heading attributes to ensure search engine optimization

## Code Updates Made

In the majority of the html, the different sections of 


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

