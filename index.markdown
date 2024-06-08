---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
featured_count: 6
---

{% assign featured_items = site.products | sample: page.featured_count %}
{% include masonry_grid.html featured_items=featured_items brick_height='170px' brick_padding='0.4rem' font_color='rgba(241, 241, 241, 0.8)' %}

### Welcome to Humanity Stones and thank you for visiting!

Rooted in centuries of tradition, Humanity Stones reimagines the artistry of handcrafted apparel.

Crocheting, a textile craft dating back to the 19th century, has long been cherished for its versatility and intricate designs. Thread crochet in particular is notable for its invested time, generally 3 simple crochet rows, wrist to wrist average length, equaling one hour of time spent stitching. We honor this heritage by creating unique, wearable pieces that showcase the timeless heirloom beauty of crochet.

Complementing our crochet apparel, we offer a curated selection of stone crafts and hand-etched glass, among many other unique handcrafted trinkets. These ancient art forms, honed over millennia, add a touch of natural elegance and personalized charm to any space.

At Humanity Stones, we believe in the power of craftsmanship to tell stories and connect us to our past. Our passion for these time-honored techniques drives us to create one-of-a-kind pieces that inspire and delight.

We invite you to explore our collection and discover the beauty of handcrafted artistry.

#HumanityStones #ArtisanCreations #ArtisanGifts #crochetlove #stonework #glassworks #BeTheChange

<!-- 
<div class="hero">
    <img class="hero-image" src="./assets/icons/site_icon.png" alt="humanity stones logo">
</div>
-->
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
    .post-content h1, .post-content h2, .post-content h3 {
        text-align: center;
    }
</style>