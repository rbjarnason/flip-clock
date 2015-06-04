# &lt;flip-clock&gt;

A flip clock, timer and countdown made with [Polymer](http://polymer-project.org) and [Moment.js](https://github.com/moment/momentjs.com)

See the [component page](http://Granze.github.io/flip-clock) for more information.

## Screenshot 

![Flip Clock](http://i.imgur.com/r5RBxL1.png)

## Demo

> [Check it live](http://granze.github.io/flip-clock/components/flip-clock/demo).

## Installation

Install using [Bower](http://bower.io):

```shell
 bower install flip-clock
```

##test

Install [web-component-tester](https://github.com/Polymer/web-component-tester) globally

```shell
 npm install -g web-component-tester
```

cd in the flip-clock folder and run ```wct```. That's it!

## Options

| Attribute    | Type    | Default   | Description                         |
|--------------|---------|-----------|-------------------------------------|
| `displayMode`       | string  |    clock       | Display the element as clock, timer or countdown    |
| `showButtons`         | boolean  | false | Display start/stop and reset buttons |
| `hideSeconds` | boolean | false     | Show or hide seconds         |
| `startFrom` | int | null     | Set the minutes to start from for the countdown mode    |
| `auto`   | boolean | false     | Auto start timer and/or countdown            |

## License

[MIT License](http://opensource.org/licenses/MIT)
