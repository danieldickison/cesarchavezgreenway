---
toc:
  - id: about-anchor
    title: About
  - id: faq-anchor
    title: FAQ
  - id: news-anchor
    title: News
  - id: contact-anchor
    title: Contact & Give
---

<a id="about-anchor"></a>
## About

Hi Everyone, thanks for taking a moment to check out our exciting project!

We are a group of neighbors that have been working towards activating a community space on abandoned city land on the southwest corner of Cesar Chavez and the outbound 101 on-ramp, that has been an eyesore and fire hazard for decades.  Our plans include a fenced dog park, planted gardens, bike racks, and overall a beautiful and inviting space for the entire community.  We have spent two years getting to this point, through which we have engaged with multiple city agencies, and winning the 2023 City Community Challenge Grant for using this land,  and now we need your help to reach the finish line.

We are seeking to [raise $200,000][give], to properly build, irrigate, fence, resurface, illuminate, and so much more.  We will also need volunteers to help with fundraisers, getting the word out, potential manual labor, and any other type of help because this site belongs to all of us so let's look after it together.

<a id="faq-anchor"></a>
## Frequently Asked Questions

Who are you?
: we are so and so
and so.

When will the park open?
: 2025 or so, hopefully.

<a id="news-anchor"></a>
## News and Updates
<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.date | date_to_string }} – {{ post.title }}</a></li>
{% endfor %}
</ul>

<a id="contact-anchor"></a>
## Contact Us

Reach out to [{{ site.email }}](mailto:{{ site.email }}) for information and to stay in touch.

You can contribute to our fundraiser via our [Givebutter page][give]. Donations are tax deductible.

[give]: https://givebutter.com/cesar-chavez-greenway
