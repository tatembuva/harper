# Harper

![Harper](./assets/harper.jpeg)

> Half a yard...let's see where this takes us!

Harper is a simple crypto-trading bot/bot network? Harper monitors and manages instances of [Freqtrade](https://www.freqtrade.io/en/stable/), while attempting to hide away a lot of the setup & config complexity; Stream-lining the process of developing a viable trading algo/bot/bot network, from simple strategy ideas to full on `half a yard` bot armies...
This is an exploratory project, the ultimate goal being to gain sufficiant skills and understanding of trading bots/bot networks using our friendly neighbourhood programming languages 🕸 js and python🕸 then eventually rewriting the whole thing in [Rust](https://www.rust-lang.org)

## Feature Wishlist?

_🤷‍♂️_

- [ ] Cool lil tui hero section...
  - Shows cli name, version, author etc
  - A Harper quote
- [ ] Checks if freqtrade is avaliable, uses its own version of the freqtrade software...?maybe as a git submodule?
  - sets up the required python enviroment
  - downloads and installs freqtrade for the user...
  - this process should have a fancy loading sequence
- [ ] Comes with a few basic strategies
  - strategies are just python files, freqtrade strats
  - strats are copied into the custom folders when saved,
    - this is to abstract away every annoying setup step,
    - the user should from anywhere write a strat file and pass it through Harper...
    - ?? what about libraries ey ??

## Install

```bash
$ npm install --global harper
```

## CLI

```
$ harper --help

  Usage
    $ harper

  Options
    --name  Your name

  Examples
    $ harper --name=Jane
    Hello, Jane
```
