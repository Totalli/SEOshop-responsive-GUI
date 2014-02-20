SEOshop-responsive-GUI
=============

Files for a responsive GUI in the SEOshop platform.

Installing
-------

Upload all files to your assets folder under GENERAL > Design > Template Editor.

**1.  Viewport meta tag**

Be sure to add the viewport meta tag in the head of your page to control the layout of mobile devices.

    <meta name="viewport" content="width=device-width, initial-scale=1.0">


**2.  Include the GUI stylesheet files.**

The original `gui.css` needs to be inserted first. The `gui-responsive.css` overwrites this file.

    <link rel="stylesheet" href="{{ 'gui.css' | url_core }}" /> 
    <link rel="stylesheet" href="{{ 'gui-responsive.css' | url_asset }}" />


**3.  Include the GUI javascript files.**

The `gui-responsive.js` adds a little adjustments for mobile users in terms of UX.

    <script type="text/javascript" src="{{ 'gui.js' | url_core }}"></script>
    <script type="text/javascript" src="{{ 'gui-responsive.js' | url_asset }}"></script>

Help
------------

If you need any help regarding this subject please do not hesitate to get in touch. You can reach us via frontend@getseoshop.com.
