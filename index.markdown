---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
featured_count: 6
---

{% assign featured_items = site.products | sample: page.featured_count %}
{% include masonry_grid.html featured_items=featured_items brick_height='120px' brick_padding='0.4rem' font_color='rgba(241, 241, 241, 0.8)' %}

<div class="hero">
    <img class="hero-image" src="./assets/icons/site_icon.png" alt="humanity stones logo">
</div>
<style>
    .post-header {
        display: none;
    }
    .hero {
        text-align: center;
    }
    .hero-image {
        /* max-width: 350px; */
        max-width: 213px;
        scale: 1.1;
        margin-bottom: -60px;
    }
</style>