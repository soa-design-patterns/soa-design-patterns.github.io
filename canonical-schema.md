---
layout: default
comments: true
---

# [](#summery) Summary

How can services be designed to avoid data model transformation?

## [](#problem) Problem
Services with disparate models for similar data impose transformation requirements that increase development effort, design complexity, and runtime performance overhead.

## [](#solution) Solution
Data models for common information sets are standardized across service contracts within an inventory boundary.

## [](#application) Application
Design standards are applied to schemas used by service contracts as part of a formal design process.

## [](#impacts) Impacts
Maintaining the standardization of contract schemas can introduce significant governance effort and cultural challenges.

## [](#priciples) Principles
Standardized Service Contract

## [](#Architecture) Architecture
Inventory, Service

# [](#profile) (Semi)Formalized Profile
## [](#vocabulary) Vocabulary
![vocabulary](./images/CanonicalSchema-vocabulary.png)

## [](#problem) Problem Variants
### [](#problem1) Model transformation is required
![problem1](./images/CanonicalSchemaTransformationIsRequired.png)

### [](#problem2) Model transformation is implemented
![problem2](./images/CanonicalSchemaTransformationExists.png)

## [](#solution) Solution Variants
### [](#solution1) Standardized model for data is defined
![solution](./images/CanonicalSchemaSolution.png)

## [](#application) Application
### [](#application1) Tranformation implmenentation is removed
![application1](./images/CanonicalSchemaTransformationExistsPR.png)

### [](#application2) Standardized model is defined
![application1](./images/CanonicalSchemaTransformationIsRequiredPR.png)

**[Back](./)**

{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://soa-design-patterns.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}