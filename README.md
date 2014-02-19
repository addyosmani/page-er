# &lt;x-paginator&gt;

A Polymer element for paginating model data

> Maintained by [Addy Osmani](https://github.com/addyosmani).

## Demo

> [Check it live](http://addyosmani.github.io/x-paginator).

## Installation

Using [Bower](http://bower.io), run:

```shell
bower install x-paginator
```

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/x-paginator.html">
    ```

3. Start using it!

    ```html
    <x-paginator><x-paginator>
    ```

## Examples

Basic usage:

```
<x-paginator></x-paginator>
```

Set items per page:

```
<x-paginator perpage="5"></x-paginator>
```

Set current page and items per page:

```
<x-paginator currentpage="3" perpage="5"></x-paginator>
```

Customize next and previous labels:

```
<x-paginator previous="Previous!" next="Next!" ></x-paginator>
```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [NodeJS](http://nodejs.org/download/).
2. Install [GruntJS](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`perpage`      | *number*                  | `10`               | Items to display per page
`currentpage`      | *number*                  | `0`               | The default page to display
`next`      | *string*                  | `Next >>`               | Label for the next button
`previous`      | *string*                  | `<< Prev`               | Label for the previous button

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)