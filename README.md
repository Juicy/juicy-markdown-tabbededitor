# &lt;juicy-markdown&gt;

> Polymer Element with GitHub Flavored Markdown (GFM) editor with file drop, paste functionality and a preview window

## Demo
![Preview](preview.png?raw=true "Preview")

[Check it live!](http://Juicy.github.io/juicy-markdownedit)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install juicy-markdownedit --save
```

Or [download as ZIP](https://github.com/Juicy/juicy-markdownedit/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/juicy-markdownedit/juicy-markdownedit.html">
    ```

3. Start using it!

    ```html
    <juicy-markdownedit></juicy-markdownedit>
    ```

## Options

Attribute      | Options   | Default  | Description
---            | ---       | ---      | ---
`value`        | *string*  | ``       | Markdown to render.
`placeholder`  | *string*  | ``       | Input placeholder.
`uploadurl`    | *string*  | ``       | URL to files storage server, see [`<juicy-filedrop url>`](https://github.com/Juicy/juicy-filedrop#options).
`index`        | *number*  | ``       | Index of a tab to be shown by default.
`footer`       | *string*  | ``       | Text/HTML to be shown as a footer.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/Juicy/juicy-markdownedit/releases).
