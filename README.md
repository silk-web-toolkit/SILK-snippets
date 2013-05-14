# SILK SUBLIME TEXT 2 SNIPPETS

## About

A collection of [Silk](http://www.silkyweb.org) snippets for Sublime Text 2.

## Install

Use [Package Control](http://wbond.net/sublime_packages/package_control).

## Usage

Type the snippet tabTrigger/shortcode to complete the snippet.

The snippets are listed below in no particular order. The '$1' indicates first editable section of the snippet. Some snippets have been set up so that pressing Tab jumps the caret to the next predefined editable section.

If you want to contribute just fork this repository and submit a pull request, or fire your idea over to our <a href="http://groups.google.com/group/silk-user">mailing list</a>.  The more generic and reusable your contributions/ideas the better.

### Silk Component

*skc*

    <div id="silk-component:${1}">${2}</div>

### Silk View

*skv*

    <html>
      <body>
        ${1}
      </body>
    </html>

### Silk Template

*skt*

    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="utf-8" />
        <title>${1}</title>
      </head>

      <body>

        <!-- some header / nav placeholder -->

        <div id="silk-view">
          <!-- Silk view content goes here -->
        </div>

        <!-- some footer placeholder -->
      </body>
    </html>
