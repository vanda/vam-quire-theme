---
title: Styleguide
layout: page
order: 9999
outputs:
  - html
---


# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

***

This is a starter theme for [Quire](https://gettypubs.github.io/quire/), a multiformat digital publishing framework. An example of _italic text_. Quire can be used to generate a web book, EPUB and MOBI e-books, and a PDF optimized for print; all from a single set of text files. [Link sample](#). Here is an example of **bold text**

> Blockquote - What do I want to do? ... I know now is the time for picture books. An American city is the best, Pittsburgh better than Washington. I know more about such a place. I would want to visit several besides Pittsburgh before deciding. Something perhaps smaller. Toledo, Ohio, maybe. Then I’m not sure a book of photos should be identified locally.

***

Unordered List
- Modern and Classic type styles
- Cover and splash page images
- Background colors
  - Indented list item
  - Indented list item
  - Indented list item

Ordered List
1. Modern and Classic type styles
2. Cover and splash page images
4. Background colors
    1. Indented list item
    2. Indented list item
    3. Indented list item

***

## Figures

#### Image
{% figure 'fig-1' %}

#### Video
{% figure 'vid-1' %}

#### Audio
{% figure 'audio-1' %}

#### Table
{% figure 'table-1' %}

#### Pull Left/Right
{% figure 'lange' 'is-pulled-right' %}
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce mollis ut massa vitae euismod. Donec auctor, tortor a ultrices ultrices, tellus nisl luctus sapien, non egestas massa felis non augue. Sed sit amet euismod magna. Nunc vel elit accumsan, elementum sapien eu, ultricies odio. Nullam fermentum sollicitudin tellus, nec tincidunt felis elementum non. Aliquam sed mi id tortor placerat dictum vitae a nisl. Duis cursus sodales ipsum vitae imperdiet. Vivamus nec augue malesuada, iaculis tellus ut, varius arcu. Aenean aliquam nec sem sagittis tristique. Integer at augue condimentum, tempor odio a, volutpat leo. Morbi imperdiet est sed orci faucibus malesuada.</p>

{% figure 'lange' 'is-pulled-left' %}
<p>Aenean ac ante urna. Fusce in porttitor diam. Fusce massa arcu, eleifend suscipit vulputate ut, aliquet dignissim massa. Aenean ultricies felis lacus. Vivamus ultrices molestie metus, sed hendrerit quam dictum eget. Phasellus cursus cursus arcu pretium tempor. Nullam nec arcu id quam tempus venenatis sed at tortor. Sed venenatis, risus quis dictum gravida, nibh nunc vestibulum augue, eu pulvinar purus nunc nec lectus. Maecenas vel massa ut ex porta dictum in id odio. Morbi varius, diam sed pretium placerat, nibh velit luctus lorem, quis porta lorem tellus et tellus.</p>

***

## Icons
<style>
 .svg-list {
  display: flex;
  gap: 1rem;
  margin-bottom: 4rem;
 }
 .svg-list svg {
  width: 36px;
  height: 36px;
 }
</style>
<div class="svg-list">
 {% icon type="home" %}
 {% icon type="left-arrow" %}
 {% icon type="right-arrow" %}
 {% icon type="search" %}
 {% icon type="nav" %}
 {% icon type="arrow-forward" %}
 {% icon type="start" %}
 {% icon type="down-arrow" %}
 {% icon type="link" %}
 {% icon type="close" %}
 {% icon type="download" %}
 {% icon type="plus" %}
 {% icon type="fullscreen" %}
</div>

## Contributors
{% contributors context=publicationContributors format='bio' %}
