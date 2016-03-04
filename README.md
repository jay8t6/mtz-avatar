# &lt;mtz-avatar&gt;

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install mtz-avatar --save
```

Or [download as ZIP](https://github.com/jay8t6/mtz-avatar/archive/master.zip).

#### Recommended Install
```bash
npm install semantic-ui  # Use themes, import build/watch tasks into your own gulpfile.
```

Semantic UI includes an interactive installer to help setup your project
![Getting Started](https://dl.dropboxusercontent.com/u/2657007/install.gif)

```bash
cd semantic
gulp build
```

* For more details on setup visit our [getting started guide](http://semantic-ui.com/introduction/getting-started.html).
* To learn more about theming please read our [theming guide](http://www.semantic-ui.com/usage/theming.html)

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/mtz-avatar/mtz-avatar.html">
    ```

3. Start using it!

    ```html
    <mtz-avatar></mtz-avatar>
    ```

## Options

Attribute    | Options                   | Default             | Description
---          | ---                       | ---                 | ---
`fetch`      | *object*                  | ``                  | Pass in the username, title, recognition and points

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

3. Start development server and open `http://localhost:8080/components/mtz-avatar/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.com/jay8t6/mtz-avatar/releases).

## License

[MIT License](http://webcomponentsorg.mit-license.org/) © WebComponents.org
