# Open Arrow

Open Arrow is an open-source font that contains 112 arrow symbols from U+2190 to U+21ff

## How to use

1. To embed `open-arrow`, copy this code into the `<head>` of your HTML document.
    ```html
    <style>
      @font-face {
        font-family: 'open-arrow';
        src: url('path-to-font-file/OpenArrow-Regular.eot') format('embedded-opentype'),
             url('path-to-font-file/OpenArrow-Regular.woff2') format('woff2'),
             url('path-to-font-file/OpenArrow-Regular.woff') format('woff'),
             url('path-to-font-file/OpenArrow-Regular.otf') format('opentype'),
             url('path-to-font-file/OpenArrow-Regular.ttf') format('truetype');
        font-weight: normal;
        font-style: normal;
        unicode-range: U+2190-21ff;
      }
    </style>
    ```
2. Specify `open-arrow` at the top of the `font-family`
    ```css
    font-family: 'open-arrow', Helvetica, sans-serif;
    ```