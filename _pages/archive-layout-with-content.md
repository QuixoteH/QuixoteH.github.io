---
title: "Archive Layout with Content"
layout: archive
permalink: /archive-layout-with-content/
---

A variety of common markup showing how the theme styles them.

# Header one

## Header two

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Quotes are cool.

## Tables

| Entry            | Item   |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | 2016   | Description of the item in the list                          |
| [Jane Doe](#)    | 2019   | Description of the item in the list                          |
| [Doe Doe](#)     | 2022   | Description of the item in the list                          |

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

#dowork
:   Coined by Rob Dyrdek and his personal body guard Christopher "Big Black" Boykins, "Do Work" works as a self motivator, to motivating your friends.

Do It Live
:   I'll let Bill O'Reilly [explain](https://www.youtube.com/watch?v=O_HyZ5aW76c   "We'll Do It Live") this one.

## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.btn` class.

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://github.com   "GitHub").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.

{% include base_path %}
{% for post in site.pages %}
{% include archive-single.html %}
{% endfor %}

# Biography

I'm an undergraduate student majoring in IoT Engineering at Northeast Agricultural University. Passionate about software development and data analysis, I am proficient in multiple programming languages and tools, and possess a solid foundation in AI. I have actively participated in various projects and competitions during my academic journey, accumulating extensive practical experience.

# News

- [Jul-Sep 2025] Interning at China Unicom Chengdu Branch as an AI solutions intern, participating in projects such as automated generation of probation recommendations and low-altitude police applications using drones, and contributing to the "Blossom Cup" 5G Application Collection Competition.
- [Mar 2025] The paper "Performance Improvement of Collaborative Filtering Algorithms Based on Deep Learning" was accepted by the 2025 3rd International Conference on Mechatronics, IoT and Industrial Informatics.
- [Apr 2024] Our team secured a silver medal in the Kaggle Competition: Home Credit - Credit Risk Model Stability, ranking in the top 0.5%.
- [Mar 2024] Successfully completed the Biological Informatics Sample Management Big Data Service Platform project, which is now in use at the university's biological informatics laboratory and has obtained copyright registration from the Copyright Bureau of China.
- [Jul-Aug 2024] Completed a technology R&D internship at Chengdu JIKEDAO Software, where I was responsible for the water station management system, gaining an understanding of the SaaS system architecture and maintenance.
- [Jul 2023] Completed a front-end development internship at Harbin ChinaSoft Technology Co., Ltd., mastering the basics of front-end development and the Vue 3 framework, and received an internship certificate.

<div class="two-column-container">
  <div class="column">
    ## Interests

    - Data Analysis and Processing
    - Machine Learning for quantitative finance
    - Medical image segmentation
  </div>
  <div class="column">
    ## Education Background

    **Northeast Agricultural University** - IoT Engineering  
    **Time**: Sep 2022 - June 2026  
    **Main Courses**: Data Structures, Scientific Computing, Python Programming, Embedded Development, IoT industry application, etc.  
    **Academic Performance**: 86/100 over the first six semesters, IELTS 7.0
  </div>
</div>
