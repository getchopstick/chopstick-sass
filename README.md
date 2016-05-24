Chopstick Design Framework
==========================

Chopstick is a mobile-first responsive Design framework.

It uses the following tools
- [Bower](http://bower.io/) as a dependency manager
- [Sass](http://sass-lang.com/) as a scss preprocessor

## Need  help?
- Ask your question on twitter: [@GetChopstick](https://twitter.com/GetChopstick)
- Join the [Slack channel](https://getchopstick.slack.com)

## Setup and usage

### Install

Install [bower](http://bower.io) and the necessary JavaScript dependencies:

    npm install -g bower
    bower install

Use your prefered workflow to compile the `.scss`.

### Framework

### `.scss` structure.

The Chopstick Scss is maintained in separate repositories which are loaded with [Bower](http://bower.io/). We believe these partials should be easy to update and configurable without writing new code.

#### Partials
We use the following partials according to the [ITCss](http://itcss.io/) structure.
1. [chopstick-settings](https://github.com/getchopstick/chopstick-settings): contains global variables and config switches to get you started. These can be overwritten in your project. Simply duplicate the variables you want to change or replace this file.
2. [chopstick-tools](https://github.com/getchopstick/chopstick-tools):  contains mixins and functions.
3. [chopstick-generic](https://github.com/getchopstick/chopstick-generic): contains ground-zero styles (Normalize.css, resets, box-sizing)
4. [chopstick-elements](https://github.com/getchopstick/chopstick-elements): contains unclassed HTML elements (type selectors)
5. [chopstick-objects](https://github.com/getchopstick/chopstick-objects): contains cosmetic-free design patterns
6. chopstick-components: contains designed components, chunks of UI (these are maintained in the boilerplate as they are specific to this)
6. [chopstick-utilities](https://github.com/getchopstick/chopstick-utilities): contains helper classes

#### Usage
We try to keep the code as modular as possible. So you can comment out what you don’t use.

If you want to change something within the external partials you have 3 options:
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


## What’s in a name
The origin of the Chopstick name:
- Chopstick originated as front-end companion of Fork CMS. Both are developed and maintained by [Wijs](https://wijs.be/en)
- Inspired by the Karate Kid movies, Chopstick is a deadly and precise [fly squating tool](https://www.youtube.com/watch?v=J1gAHil89Z4).
