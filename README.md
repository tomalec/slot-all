# &lt;slot-all&gt;

A custom element to distribute all elements regardless of their slot name

## Demo

[Check it live!](http://Juicy.github.io/slot-all)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install slot-all --save
```

Or [download as ZIP](https://github.com/Juicy/slot-all/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponent-lite.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/slot-all/slot-all.html">
    ```

3. Start using it!

    ```html
    <div>
        #shadow-root
            <slot-all></slot-all>
        <div slot="foo">Named slot</div>
    </div>
    ```

## [Contributing and Development](CONTRIBUTING.md)

## History

For detailed changelog, check [Releases](https://github.com/Juicy/slot-all/releases).

## License

MIT
