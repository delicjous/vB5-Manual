# v0.7.0
## 05/17/2018

1. [](#improved)
    * Restored coding with base64.

# v0.6.0
## 05/15/2018

1. [](#bugfix)
    * Fix characters that do not appear in Russian [#8](https://github.com/iusvar/grav-plugin-printfriendly/issues/8) and Turkish [#7](https://github.com/iusvar/grav-plugin-printfriendly/issues/7) language. 

# v0.5.0
## 08/03/2017

1. [](#improved)
    * Added parameter param_sep in url construction.
    * New site with working [demo](http://iusvar.alwaysdata.net/grav/). [Snappygrav](https://github.com/iusvar/grav-plugin-snappygrav)'s demo also works: On the Alwaysdata hosting server, wkhtmltopdf works wonderfully.

# v0.4.0
## 07/13/2017

1. [](#new)
    * Newly added nonce features also to identify html div.
1. [](#bugfix)
    * The data to be printed is created only when requested

# v0.3.3
## 07/10/2017

1. [](#bugfix)
    * Simplified procedure
    * Eliminated Nonce features
    * Maybe we're with [#2](https://github.com/iusvar/grav-plugin-printfriendly/issues/2) and [#4](https://github.com/iusvar/grav-plugin-printfriendly/issues/4) bugs.

# v0.3.2
## 07/07/2017

1. [](#bugfix)
    * Fix right version
    * Improved slug selection. It may be the cause of the [#4](https://github.com/iusvar/grav-plugin-printfriendly/issues/4) error.

# v0.3.1
## 07/06/2017

1. [](#bugfix)
    * Deleted event onCollectionProcessed: only for debugging
    * Fix Twig_Error_Runtime: An exception has been thrown during the rendering of a template ("Only variables should be passed by reference").[#3](https://github.com/iusvar/grav-plugin-printfriendly/issues/3)

# v0.3.0
## 07/06/2017

1. [](#new)
    * Added Nonce features for printing
    * Added pf_implode Twig filter
    * Added configuration option to get breadcrumbs
    * Added configuration option to get tags
    * Added configuration option to get first image
    * Added configuration option to set Close On Escape
    * Added configuration option to set Close Icon
    * Added configuration option to set Confirm and Cancel Buttons Text
    * Added animated icon
    * Added icons on the buttons
1. [](#improved)
    * Improved printfriendly Twig function
    * Updated jQuery UI library to v1.12.1
    * Updated Font Awesome library to v4.7.0
    * English and Italian languages improvements
    * Deleted superflue javascript library
1. [](#bugfix)
    * Fix Broken internal anchors [#2](https://github.com/iusvar/grav-plugin-printfriendly/issues/2). All information to be printed is entered in a hidden input field

# v0.2.1
## 08/29/2016

1. [](#improved)
    * Print directly avoiding the window

# v0.1.1
## 08/23/2016

1. [](#improved)
    * Added french (@MATsxm) language
1. [](#bugfix)
    * Correct README.md link

# v0.1.0
##  08/23/2016

1. [](#new)
    * Initial release.
