---
toc:
  - id: about-anchor
    title: About
  - id: gallery-anchor
    title: Gallery
  - id: faq-anchor
    title: FAQ
  - id: news-anchor
    title: News
  - id: contact-anchor
    title: Contact & Give
---

{::options parse_block_html="true" /}

<section>
<a id="about-anchor"></a>
{% include about.markdown %}
</section>

<section class="gallery">
<a id="gallery-anchor"></a>

## Gallery
{% include gallery.html asset_path="main-gallery" %}
</section>

<section>
<a id="faq-anchor"></a>

## Frequently Asked Questions
{% include faq.markdown %}
</section>

<section>
<a id="news-anchor"></a>

## News and Updates

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.date | date_to_string }} – {{ post.title }}</a></li>
{% endfor %}
</ul>
</section>

<section>
<a id="contact-anchor"></a>

## Contact Us
{% include contact.markdown %}
</section>

[give]: https://givebutter.com/cesar-chavez-greenway
