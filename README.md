# &lt;juicy-markdown-tabbededitor&gt;

> Polymer Element with GitHub Flavored Markdown (GFM) editor with file drop, paste functionality and a preview tab

## Demo
![Preview](preview.png?raw=true "Preview")

[Check it live!](http://Juicy.github.io/juicy-markdown-tabbededitor)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install juicy-markdown-tabbededitor --save
```

Or [download as ZIP](https://github.com/Juicy/juicy-markdown-tabbededitor/archive/gh-pages.zip).

## Usage

1. Import Web Components' polyfill, if needed:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/juicy-markdown-tabbededitor/juicy-markdown-tabbededitor.html">
    ```

3. Start using it!

    ```html
    <juicy-markdown-tabbededitor></juicy-markdown-tabbededitor>
    ```

## Options

Attribute      | Options   | Default  | Description
---            | ---       | ---      | ---
`index`        | *number*  | ``       | Index of a tab to be shown by default.
`footer`       | *string*  | ``       | Text/HTML to be shown as a footer.

This component extends [`<juicy-markdown-editor>`](https://github.com/Juicy/juicy-markdown-editor) so check its [options](https://github.com/Juicy/juicy-markdown-editor#options)

Attribute      | Options   | Default  | Description
---            | ---       | ---      | ---
`value`        | *string*  | ``       | Markdown to render.
`placeholder`  | *string*  | ``       | Input placeholder.
`uploadurl`    | *string*  | ``       | URL to files storage server, see [`<juicy-filedrop url>`](https://github.com/Juicy/juicy-filedrop#options).
`customheader` | *string*  | `x-file` | Name for custom header that contains JSON with file meta data, see [`<juicy-filedrop customheader>`](https://github.com/Juicy/juicy-filedrop#options).
`ghcss`        | *boolean* | `false`  | Should ghithub-markdown.css be imported? see [`<juicy-markdown ghcss>`](https://github.com/Juicy/juicy-markdown#options).

## See also

 - [`<juicy-markdown>`](https://github.com/Juicy/juicy-markdown) - Markdown viewer
 - [`<juicy-filedrop>`](https://github.com/Juicy/juicy-filedrop) - just file drop panel
 - [`<juicy-markdown-tabbededitor>`](https://github.com/Juicy/juicy-markdown-editor) - simpler Markdown editor

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/Juicy/juicy-markdown-tabbededitor/releases).

## License

MIT
