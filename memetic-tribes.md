---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: tribe
---

<section id="tribes">

  <div id="content">

    <h1>The memetic tribes of culture wars 2.0</h1>
    <h2>Sourced from Intellectual Explorers’ Club</h2>
    <p>The information war is more than an allegory. We’re immersed in an evolving, ongoing conflict in which state actors, terrorists, and ideological extremists are using social media to sow discord and erode shared reality. We need good maps to make sense of 2019’s messy political landscape.</p>

    <ul>
    {% for item in site.data.tribes %}
      <li><a href="{{ item.url }}">{{ item.name }}</a></li>
    {% endfor %}
    </ul>

  </div>

</section>
