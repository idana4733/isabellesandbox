---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://cdil.lib.uidaho.edu/images/palouse_sm.jpg" %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## About the Collection

This is a table:
|Thing|First|Second|Third|
|----|----|----|----|
|Fruit|Apple|Bannana|Pear|
|Tree|Oak|Spruce|Ginkgo|

| Thing | First | Second  | Third  |
|-------|-------|---------|--------|
| Fruit | Apple | Banana  | Pear   |
| Tree  | Oak   | Spruce  | Ginkgo |

|First|Second|
|-----|-----|
|a|
<ul>
  <li>abc</li>
  <li>def</li>
</ul>|


<table class="table" markdown="1">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
