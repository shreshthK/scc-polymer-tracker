# &lt;Suuply Chain Connect polymer tracker&gt;

> scc-polymer-tracker
>

## Demo

[Check it live!](http://my-user.github.io/my-repo)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install scc-polymer-tracker --save
```

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/scc-polymer-tracker/scc-polymer-tracker.html">
    ```

3. Start using it!

    ```html
    <scc-polymer-tracker></scc-polymer-tracker>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`foo`         | *string*    | `bar`        | Lorem ipsum dolor.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

    ```sh
    $ npm install -g bower polyserve
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/my-repo/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.build.ge.com/212601662/scc-polymer-tracker/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
