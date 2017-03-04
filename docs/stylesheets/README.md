# Open Arrow

Open Arrow is an open-source font which contains 112 arrow symbols between U+2190 and U+21ff

## How to use

1. To embed open arrow, copy this code into the `<head>` of your HTML document.
    ```
    <style>
      @font-face {
        font-family: 'open-arrow';
        src: url('path-to-font-file/OpenArrow-Regular.eot');
        src: url('path-to-font-file/OpenArrow-Regular.eot') format('embedded-opentype'),
             url('path-to-font-file/OpenArrow-Regular.ttf') format('truetype'),
             url('path-to-font-file/OpenArrow-Regular.woff') format('woff'),
             url('path-to-font-file/OpenArrow-Regular.svg') format('svg');
        font-weight: normal;
        font-style: normal;
        unicode-range: U+2190-21ff;
      }
    </style>
    ```
2. Specify open arrow at the top of the font-family