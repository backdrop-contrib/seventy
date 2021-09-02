Seventy
=======

Seventy extends Seven, the default admin theme in Backdrop. More precisely, it
doesn't do much on its own, but it provides a place which lets you extend Seven
easily. Seventy provides a good start to give the administration and editorial
interface in Backdrop a different look.

Seventy as a sub-theme
----------------------

Seventy is a sub-theme of Seven, and Seven serves as base theme for Seventy.
As a sub-theme, Seventy inherits most resources of Seven. When you start to use
Seventy, your administration pages will look exactly like Seven. However,
Seventy comes with an empty `skin-seventy.css` which makes it easy to override
the CSS styles of Seventy and/or to add your custom styles.

Installation
------------

- Install and enable Seventy using the official Backdrop CMS instructions at
https://backdropcms.org/guide/themes.
- Go to *Administer > Site building > Themes*, scroll down a bit, and choose
Seventy as Administration theme.

Usage
-----

Open the file `css/skin-seventy.css`, and add your styles.

### Override a Seven style
Example: Override Seven's gray header background color with a light blue.

```
.l-header::before {
  background-color: #e3f2fd;
}
```

### Add your own custom style
Example: Add some margin for a content form field.

```
.field-type-text-with-summary {
  margin-bottom: 2em;
}
```

Advanced usage
--------------

Apart from CSS styles, Seven includes template files, images and more. To
override template, JavaScript or PHP files in Seventy, refer to the Documentation
about sub-theming: https://docs.backdropcms.org/documentation/creating-sub-themes

Alternatives to Seventy
-----------------------

### Write your own Seven sub-theme

Writing your sub-theme from scratch can be fun, you will learn a lot, and it
gives you the most freedom. Please refer to the sub-theming documentation
mentioned above.

### Install the CSS Injector module
CSS Injector allows you to add CSS to Backdrop based on configurable rules.
It's useful for adding simple CSS tweaks without modifying the theme.
Project: https://backdropcms.org/project/css_injector

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/seventy/issues

Current Maintainers
-------------------

- [Olaf Grabienski](https://github.com/olafgrabienski)

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for the complete text.
