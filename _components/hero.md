---
permalink: /components/hero/
redirect_from:
- /hero/
- /heroes/
- /components/heroes/
layout: styleguide
type: element
title: Hero
category: Components
lead: A hero showcases a specific piece of content on your site.
---

{% include code/preview.html component="hero" %}
<section class="site-component-section">
  {% include code/accordion.html component="hero" %}
  <div class="usa-accordion usa-accordion--bordered site-accordion-docs">
    <button class="usa-button-unstyled usa-accordion__button"
        aria-expanded="true" aria-controls="hero-docs">
      Guidance
    </button>
    <div id="hero-docs" aria-hidden="false" class="usa-accordion__content site-component-usage">
      <h4>When to use the hero component</h4>
      <ul class="usa-content-list">
        <li><strong>Highlighting content.</strong> When you want to highlight an existing piece of content, such as a blog post or article.</li>
      </ul>
      <h4>When to consider something else</h4>
      <ul class="usa-content-list">
        <li><strong>Everything's important.</strong> When everything is important, nothing is important. Heroes should be used sparingly.</li>
      </ul>
      <h4>Usability guidance</h4>
      <ul class="usa-content-list">
        <li><strong>Be succinct.</strong> Don't overload users with information.</li>
        <li><strong>Think about performance.</strong> Use the <code>&lt;picture&gt;</code> element to serve the appropriately sized image for each breakpoint.</li>
      </ul>
      <h4 class="usa-heading">Accessibility</h4>
      <ul class="usa-content-list">
        <li>Use a <code>&lt;section&gt;</code> element with an <code>aria-labelledby</code> attribute that points to the hero header <code>id</code>.</li>
      </ul>
      <h4 class="usa-heading">Package information</h4>
      <ul class="usa-content-list">
        <li>
          <strong>Package usage:</strong> <code>@import usa-hero</code>
        </li>
        <li>
          <strong>Requires:</strong> <code>required</code>, <code>global</code>
        </li>
      </ul>
    </div>
  </div>
</section>
