# code-refactor

In computer programming and software design, code refactoring is the process of restructuring existing computer code without changing its externar behavior. [Wikipedia](https://en.wikipedia.org/wiki/Code_refactoring)

## Description

In this project, the landing page of Horiseo website was updated, refactoring the HTML and CSS: adding accesibilities elements, implementing semantic elements to the existing HTML and eliminating redundancies in the CSS.

The changes will create a website more accesible for people with disabilities, and easy to edite in the future.


## Increasing accesibility

The HTML of the website consist in a lot of images. By simple adding an "alt" atribute to the images, it make easy for assistive technologies like video captions, screen readers, and braile keyboards to access to the content shown in the website.

It is also good for the companie because some search engines like Google or Microsoft Bing rank higher website with accessibilities.

## Including semantics elements

Semantics elements are a useful self-describe tag very used in HTML.

Instead of using in the HTML a div tag with a header class, its simplier to use a header tag.

For that reason the HTML in this project was changed, implementing semantic element to the code, without changing the final output.

## Redundancies in CSS

In this code in particular, a lot of atributes was constantly repeated in similars classes. The objective was to consolidate those atributes and making the CSS file easy to read for future changes.