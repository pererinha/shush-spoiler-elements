## What is this?

It is just a simple example of how to build a webcomponent. I mean it is really simple, the possibilities of what you can do are infinte.

### About this webcomponent

A simple webcomponent to prevent us to read spoilers around the web. I know, it is a lifesaver!

No, no, no need to thank me. It's my pleasure to help.

## Demo

[demo demo demo](http://pererinha.github.io/shush-spoiler-elements)

## Options

The component has some options:

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`warning`         | *string*    | `spoiler detected`        | The phrase that user will see that indicates that the text has spoilers.
`spoiler`         | *string*    | `no spoilers for you`        | The spoiler

## Development

You can use [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/) to run it locally.
 
Run this command to install the dependencies.

```sh
$ bower install && npm install
```

Run Grunt or other webserver to run it

```sh
$ grunt connect
```

## License

[MIT License](http://opensource.org/licenses/MIT)
