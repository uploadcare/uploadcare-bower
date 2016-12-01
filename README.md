Uploadcare Widget
=================

[Uploadcare](https://uploadcare.com) is a PaaS for file uploads,
cloud storage, and on-the-fly image transformations.

This package contains a compiled version of the widget.

  * [Source code](https://github.com/uploadcare/uploadcare-widget)
  * [Issues](https://github.com/uploadcare/uploadcare-widget/issues)
  * [License](https://github.com/uploadcare/uploadcare-widget/blob/master/LICENSE)
  * [Widget documentation](https://uploadcare.com/documentation/widget/)
  * [JavaScript API documentation](https://uploadcare.com/documentation/javascript_api/)

## Files

Uploadcare library, requiring jQuery as a dependency:

  * uploadcare.js
  * uploadcare.min.js

Standalone Uploadcare library with no external dependencies:

  * uploadcare.full.js
  * uploadcare.full.min.js

## Using Uploadcare Widget

There's a simple two-step process that drives
you into Uploadcare experience.

Step 1. Add the following code to your web page header:

    <script>
        // Widget settings
        UPLOADCARE_PUBLIC_KEY = 'your_public_key';
    </script>
    <script src="/bower_components/jquery/jquery.js" charset="utf-8"></script>
    <script src="/bower_components/uploadcare/uploadcare.min.js" charset="utf-8"></script>

Step 2. Add the tag where you'd like the widget to be displayed:

    <input type="hidden" role="uploadcare-uploader">

Check out our [docs](https://uploadcare.com/documentation/)
for more info.

## Contributors

* [@Zmoki](https://github.com/Zmoki)
* [@homm](https://github.com/homm)
* [@avsd](https://github.com/avsd)

Current maintainers: [@Zmoki](https://github.com/Zmoki),
[@homm](https://github.com/homm).
