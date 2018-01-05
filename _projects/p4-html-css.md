---
title: "HTML/CSS: Developing Your Data-Story"
collection: projects
permalink: /projects/p4-html-css/
points: "350"
startdate: 2017-11-13
enddate: 2017-12-20
imgurl: /images/wireframe-main.png
---

<ul class="project-top-info">
  <li>
    <b>Timeframe</b>: 11/13 &ndash; 12/20</li>
  <li>
    <b>Points</b>: 350</li>
</ul>

## Description

In this final project, you will make decisions about how all of your media elements come together into a cohesive narrative that we have been calling your "Datastory." You will learn about some fundamental HTML elements and their relationships and behaviors programmed with CSS. In short, you will write a web-ready narrative within a single-page website format.

<figure id="twitter-css-body" class="figure-inline">
  <img src="/engl3844s18/images/wireframe-main.png" alt="Wireframe example of a single-page website." />
  <figcaption>
    Caption: Wireframe example of a single-page website.
  </figcaption>
</figure>

## General process

1. Learn how to set up and use a web-writing environment: Git and Github and writing in a code editor.
2. Learn about and apply basic architectural and folder-naming and file-naming conventions for a single-page website.
3. Learn about and apply basic HTML <code>&lt;head&gt;</code> elements, and the <code>&lt;body&gt;</code>, how there are block and inline elements, how those elements can be written into hierarchies, and how they have <code>display</code> properties and behaviors.
4. Learn about and apply basic CSS element selection and styling (box model), the CSS cascade, &amp; the CSS <code>Grid</code>, which will enable you to create a mobile-first website layout.
5. Develop and refine content for your datastory.

## Rubric

<table class="table striped">
  <thead>
    <tr>
      <th class="sixty">
        R<span>ubric Criteria</span>
      </th>
      <th class="fifteen">
        P<span>oints</span>
      </th>
    </tr>
  </thead>
  <tbody>

    <tr>
      <td class="sixty">
        Website Content:
        <ul>
          <li>
            Reviews insights about your online practices and how digital data are intertwined with it. Essentially, does it demonstrate that you have learned more about data, writing, and digital media in your life?
          </li>
          <li>
            Integrates pertinent text, visuals, and videos to your datastory.
          </li>
        </ul>
      </td>
      <td class="fifteen">
        20
      </td>
    </tr>

    <tr>
      <td class="sixty">
        HTML:
        <ul>
          <li>
            Conveys knowledge of block-level vs. inline-level elements.
          </li>
          <li>
            Demonstrates knowledge of parent and child block relationships, i.e. element hierarchies.
          </li>
          <li>
            Passes HTML5 validation test. To test your site, copy/paste the URL of it within this tester: <a href="https://validator.w3.org/" target="_blank">https://validator.w3.org/</a>. Some "Warnings" are okay, but fix the noted "Errors."
          </li>
        </ul>
      </td>
      <td class="fifteen">
        40
      </td>
    </tr>

    <tr>
      <td class="sixty">
        CSS:
        <ul>
          <li>
            Well-planned responsive grid with CSS3 Grid. Grid is written cleanly (spacing, syntax, and structure) and has aptly named tags, IDs, and classes.
          </li>
          <li>
            Structure of CSS document adheres to learned conventions:
            <ul>
              <li>
                General styles up top and modifiers below, due to the cascade.
              </li>
              <li>
                Alike elements are grouped together, e.g., typography scheme, media, header elements, section elements, footer elements, etc.
              </li>
            </ul>
          </li>
          <li>
            Provides consistent commenting scheme.
          </li>
          <li>
            Simple and readable typography styles and hierarchy. Aesthetic matches your narrative.
          </li>
        </ul>
      </td>
      <td class="fifteen">
        40
      </td>
    </tr>

    <tr>
      <td class="sixty" style="text-align:right;">
        <b>Total</b>
      </td>
      <td class="fifteen">
        <b>100</b>
      </td>
    </tr>

  </tbody>
</table>

**CSS**:

## Writing tools

- Github <a href="https://github.com/" target="_blank">account</a> & <a href="https://desktop.github.com/" target="_blank">desktop application</a> for hosting and versioning your website.
- <span id="localhost-install">Localhost web server via Python in the Terminal (Mac) / CommandPrompt (Windows):</span> <code>python -m SimpleHTTPServer 8000</code> for Python 2.7 &amp; <code>python -m http.server 8000</code> for Python 3.
  - <b>For Mac computers</b>, you should have Python pre-installed. If not, follow the directions below:
    - Open the Terminal
    - Install HomeBrew -- a package manager -- by following the instructions in this video: <a href="https://www.youtube.com/watch?v=lI_2DWnYo8o" target="_blank">https://www.youtube.com/watch?v=lI_2DWnYo8o</a>.
    - After installing Homebrew, while still in the open terminal, install Python 3 by simply typing the following command: <code>brew install python3</code>. This will take a minute or two.
  - <b>For Windows</b>, follow the <em>Python 3</em> installation instruction on this page: <a href="https://www.howtogeek.com/197947/how-to-install-python-on-windows/" target="_blank">How to Geek</a>.<br/><br/><em>Be sure to choose the option to add a PATH variable</em>.<br/><br/><img style="width=70%" src="/images/python-install-win.png" />
- Code editor: <a href="https://atom.io/" target="_blank">Atom</a> (Mac/PC), <a href="https://itunes.apple.com/us/app/textwrangler/id404010395?mt=12" target="_blank">TextWrangler</a> (Mac), <a href="https://notepad-plus-plus.org/" target="_blank">Notepad++</a> (Win)
- Online code editor for practice lessons: <a href="https://codepen.io/" target="_blank">Codepen.io</a> account. Find and follow me as <a href="https://codepen.io/lndgrn/" target="_blank">lndgrn</a>. We will be using the following collection that I've curated on Codepen: <a href="https://codepen.io/collection/DdNPVo/" target="_blank">3844-examples</a>
