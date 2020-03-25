---
layout: default
title: Booking assessments in Practica 
nav_order: 3
---

# Customization
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Introduction
Practica (assessments) are 10-minute blocks that are intended for students who want to get assessed on their learning
objectives for their next rank. Students can reserve a spot in this class for dedicated 1-on-1 time with an instructor.

To reserve a spot you must use MindBody, the software that manages our sign-in and customer account management.

There are two ways that to reserve a spot using MindBody: using the mobile app or using your a web browser.
Note that, regardless of which option you use, you must still sign-in to “Practica | assessments” on our iPads.

**Note**: you must have a MindBody account to access the system. If you have not created an account yourself please speak
to our staff to get your login and set a temporary password.
 
## Method 1: Using the MindBody mobile app

### Before you begin###
Make sure the mobile app is installed on your phone. You can obtain it from the [MindBody website][https://mindbody.io/]

1. Click on the search bar
2. Enter 'Academie Duello'
3. Click on 'View Schedule'
4. On the date scroller near the top of the screen, navigate to the date and class that you want
5. Click 'Book'
6. Click 'Book' again
7. Click 'Book' a third time
  
And that's it. You're space has been reserved!
  
  
## Color schemes
{: .d-inline-block }

New
{: .label .label-green }

Just the Docs supports two color schemes: light (default), and dark.

To enable a color scheme, set the `color_scheme` parameter in your site's `_config.yml` file:

#### Example
{: .no_toc }

```yaml
# Color scheme currently only supports "dark" or nil (default)
color_scheme: "dark"
```
<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

<script type="text/javascript" src="{{ "/assets/js/dark-mode-preview.js" | absolute_url }}"></script>

## Specific visual customization

To customize your site’s aesthetic, open `_sass/custom/custom.scss` in your editor to see if there is a variable that you can override. Most styles like fonts, colors, spacing, etc. are derived from these variables. To override a specific variable, uncomment its line and change its value.

For example, to change the link color from the purple default to blue, open `_sass/custom/custom.css` and find the `$link-color` variable on line `50`. Uncomment it, and change its value to our `$blue-000` variable, or another shade of your choosing.

#### Example
{: .no_toc }

```scss
// ...
//
// $body-text-color: $grey-dk-100;
// $body-heading-color: $grey-dk-300;
$link-color: $blue-000;
//
// ...
```

_Note:_ Editing the variables directly in `_sass/support/variables.scss` is not recommended and can cause other dependencies to fail.

## Override styles

For styles that aren't defined as a variables, you may want to modify specific CSS classes. To add your own CSS overrides at the end of the cascade, edit `_sass/overrides.scss`. This will allow for all overrides to be kept in a single file, and for any upstream changes to still be applied.

For example, if you'd like to add your own styles for printing a page, you could add the following styles.

#### Example
{: .no_toc }

```scss
// Print-only styles.
@media print {
  .side-bar, .page-header { display: none; }
  .main-content { max-width: auto; margin: 1em;}
}
```
