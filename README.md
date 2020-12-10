# Refactoring the Horiseon Front Page

## Summary

The request from the client is to review and refactor their codebase to ensure the use of code that follows accessibility standards. This will also help optimize the codebase for search enginges.

In reviewing the codebase, I ensured that the source code contains semantic HTML elements, followed a logical structure, and includes alt and heading attributes to ensure search engine optimization

## Code Updates Made

asdfasdf

```
<main class="content">
    <!-- Replaced div with main to contain the majority of the page, including the three sections on the left.-->
        <section id="search-engine-optimization" class="main-section">
        <!-- Replaced div with section to improve accessibility, and added an id for the section to ensure that the link works -->
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="Search Engine Optimization" />
            <!-- Added alternate tag to the image to ensure accessibility and SEO -->
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </section>
        <section id="online-reputation-management" class="main-section">
        <!-- Replaced div with section to improve accessibility -->
            <img src="./assets/images/online-reputation-management.jpg" alt="Online Reputation Management" class="float-right" />
            <!-- Added alternate tag to the image to ensure accessibility and SEO -->
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </section>
        <section id="social-media-marketing" class="main-section">
        <!-- Replaced div with section to improve accessibility -->
            <img src="./assets/images/social-media-marketing.jpg" alt="Social Media Marketing" class="float-left" />
            <!-- Added alternate tag to the image to ensure accessibility and SEO -->
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </section>
</main>     
```

## Functionality Changes & User Guide

