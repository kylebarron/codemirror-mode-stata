# codemirror-mode-stata
> A CodeMirror mode for the Stata language

## Installation

```console
npm install codemirror codemirror-mode-stata --save
```

## Usage

1. Include `codemirror-mode-stata` into your project.

    ```html
    <!-- You can simply add stata.js as a script tag: -->
    <script src="js/codemirror.js"></script>
    <script src="js/codemirror-mode-stata/dist/stata.js"></script>
    ```

    or

    ```js
    // If you're using frontend build tools like Webpack and Babel,
    // you can simply import the module and register the mode:
    import CodeMirror from 'codemirror'
    import registerStataMode from 'codemirror-mode-stata'
    ```

1. Set 'stata' as the mode when creating the CodeMirror editor.

    ```js
    CodeMirror.fromTextArea(document.getElementById('code'), { mode: 'stata' })
    ```

## License

MIT - See [LICENSE][licenseUrl]

&nbsp;

Created by [Ian Walter](https://iankwalter.com)

&nbsp;

<a href="https://www.netlify.com">
  <img src="https://www.netlify.com/img/global/badges/netlify-light.svg">
</a>

[licenseUrl]: https://github.com/ianwalter/codemirror-mode-stata/blob/master/LICENSE
