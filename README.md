Chopstick Design Framework
==========================

Chopstick is a mobile-first responsive design framework.

It uses the following tools
- [Sass](http://sass-lang.com/) as a scss preprocessor

## Need  help?
- Ask your question on twitter: [@GetChopstick](https://twitter.com/GetChopstick)
- Join the [Slack channel](https://getchopstick.slack.com)

## Setup and usage

### Install
Use your prefered workflow to compile the `.scss`.

### Framework

### `.scss` structure.
We use the following layers according to the [ITCSS](http://itcss.io/) structure.
1. Settings: contains global variables and config switches to get you started. These can be overwritten in your project. Simply duplicate the variables you want to change or replace this file.
2. Tools: contains mixins and functions.
3. Generic: contains ground-zero styles (Normalize.css, resets, box-sizing)
4. Elements: contains unclassed HTML elements (type selectors)
5. Objects: contains cosmetic-free design patterns
6. Components: contains designed components, chunks of UI (these are maintained in the boilerplate as they are specific to this)
7. Plugins: contains third-party plugin styles
8. Utilities: contains helper classes
9. Shame: nasty, hacky, quick-fix CSS

#### Usage
We try to keep the code as modular as possible. So you can comment out what you don’t use.

If you want to change something you have 3 options:
1. Change the settings and default appearance by overriding the variables in your project.
2. Create a pull request on the source code in the correct repository.
3. Copy the original file in you own project. This means you will have to do manual updates in the future.

## Browser support
Chopstick aims to support all modern browsers. This includes latest versions of Chrome, Firefox and Safari and the latest mobile browsers on Android, iPhone and Windows Phone. Internet explorer is currently supported starting from IE10 and up.

## What is the Chopstick framework
Chopstick is a framework based on the [ITCSS](http://itcss.io/) architecture and a series of principles. It creates a structure to easily set-up and build bespoke web projects.

## Why do we make Chopstick framework
- Maintain sensible defaults
- Enforce a global coding style
- Create a scalable system for both small and big web projects

## Chopstick principles
Chopstick is built upon the following principles. Please keep these in mind when contributing and/or using this framework.

### Low specificity
A single-depth-class-based architecture based on the [BEM](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/) naming methodology.

### Highly decoupled
Avoid reliance on other bits.
- Separation of Concerns: let each piece of code solve its own problems
- Single Responsibility Principle: one thing, one thing only, one thing well
- Open/Closed Principle: add via extension, not modification

### Highly composable
- We build the bits that build the bits
- Make everything opt-in and configurable: expose API-like CSS

### Keep it simple
- The Principle of Least Surprise: make sure expectations are met, and nothing else
- Murphy’s Law: Pick the option that is the most resilient, even if it is the most boring one

## Credits

You are free to contribute to Chopstick via GitHub Pull Requests. We have a couple of simple guidelines we try to follow, of which most are taken from the [CSS Tricks Sass Style Guide](http://css-tricks.com/sass-style-guide). Please refer to the [CONTRIBUTING.md](https://github.com/getchopstick/chopstick-boilerplate/blob/master/CONTRIBUTING.md) for more information

We owe a ton of credits to the following projects for inspiration:

* [ITCSS](http://itcss.io/)
* [SMACSS](https://smacss.com/)
* [OOCSS](http://oocss.org/)
* [HTML5 Boilerplate](https://html5boilerplate.com/)
* [Inuit CSS](http://inuitcss.com/), [Foundation](http://foundation.zurb.com/) and [Bootstrap](http://getbootstrap.com/)
