Uploadcare Widget
=================

[Uploadcare](https://uploadcare.com) is an IaaS for file uploads,
cloud storage and on-the-fly image transformations.

This package contains HTML5 widget and JavaScript API:

  * [Widget documentation](https://uploadcare.com/documentation/widget/)
  * [JavaScript API documentation](https://uploadcare.com/documentation/javascript_api/)


## Files

Uploadcare library, requiring jQuery as a dependency:

  * uploadcare.js
  * uploadcare.min.js

Standalone Uploadcare library with no external dependences:

  * uploadcare.full.js
  * uploadcare.full.min.js

## How to use it

Add following code to header of your web page:

    <script src="/bower_components/jquery/jquer.js"></script>
    <script src="/bower_components/uploadcare/uploadcare.js"></script>

    <script>
        UPLOADCARE_PUB_KEY = "<public-key>";
    </script>

Add the tag in the place where widget needs to be displayed:

    <input type="hidden" role="uploadcare-uploader">
