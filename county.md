---
layout: default
title: County Policies
add_to_nav: false
order: 3
---

Here are links to information by county in Illinois.

<!--
<div class="autoComplete_wrapper">
  {% assign counties_list = "" | split: "" %}
  {% for region in site.data.regions_counties %}
    {% assign counties_list = counties_list | concat: region[1] %}
  {% endfor %}
  {% assign counties = counties_list | join: ", " %}
  <input type="text" id="autoComplete" placeholder="Search by county..." class="{{ site.data.styles.input }}" autofocus data-collection="{{ counties }}" />
</div>
-->

<!--<iframe class="airtable-embed margin-top--l" src="https://airtable.com/embed/shrCqe8cuKc52Bqgb?backgroundColor=grayLight&viewControls=on" frameborder="0" onmousewheel="" width="100%" height="98%" style="background: transparent; border: 1px solid #ccc;"></iframe>-->

<iframe class="airtable-embed" src="https://airtable.com/embed/shrtbY8C0cUGwdAuV?backgroundColor=grayLight&viewControls=on" frameborder="0" onmousewheel="" width="100%" height="533" style="background: transparent; border: 1px solid #ccc;"></iframe>
