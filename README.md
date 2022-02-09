# Ethereum Solidity and Vyper Grammars

## for GitHub and SublimeText

[Ethereum][ethereum] is a platform for decentralized applications. Decentralized applications are built with Smart Contracts.

This package contains syntax highlighting for Ethereum's Smart Contract languages [Solidity](https://soliditylang.org) and [Vyper](https://vyper.readthedocs.io).

Solidity is the biggest Ethereum language and has similarity to JavaScript. Solidity was initially proposed in August 2014 by [dr. Gavin Wood](https://en.wikipedia.org/wiki/Gavin_Wood). The language was later developed by the Ethereum project's Solidity team, led by Christian Reitwiessner.

[ethereum]: https://www.ethereum.org/

Version of syntax that GitHub is [using](https://github.com/github/linguist/tree/master/vendor/grammars) for [Solidity grammar](https://docs.soliditylang.org/en/latest/grammar.html) is in [linguist branch](https://github.com/davidhq/SublimeEthereum/tree/linguist). This grammar gives all `.sol` files ([example](https://github.com/ethereum/consensus-specs/blob/dev/solidity_deposit_contract/deposit_contract.sol)) its colors (= does _syntax highlighting_).

Another relevant source for Solidity grammar syntax is [vscode-solidity](https://github.com/juanfranblanco/vscode-solidity) (which was originally based on early versions of SublimeEthereum).

Linguist branch is an implementation [with regexes](https://sublime-text-unofficial-documentation.readthedocs.io/en/latest/reference/syntaxdefs.html) but is satisfactory esp. relating to the fact that GitHub does not support stack-based grammars. Main branch (= used in sublime package to enable `.sol` syntax highlighting for [SublimeText](http://www.sublimetext.com/) editor) uses more advanced [context stack](http://www.sublimetext.com/docs/syntax.html) approach to achieve optimal visual results for Smart Contract developers. 

## Installation in SublimeText editor

1. SublimeText menu / Preferences / Package Control
2. Select: Install Package
3. Type **Ethereum** and press ENTER

This will provide **Solidity** `.sol` and **Vyper** `.vy` syntax highlighting.

[SublimeEthereum](https://packagecontrol.io/packages/Ethereum) on Package Control. 

[package-control]: https://packagecontrol.io/packages/Ethereum

## Features

* Solidity.sublime-syntax: syntax rules for Ethereum Solidity language
   * Ethereum plugin automatically uses *Solidity language syntax* when you are in a Solidity (.sol) file
* Vyper.YAML-tmLanguage: syntax rules for Ethereum Vyper language
   * Ethereum plugin automatically uses *Vyper language syntax* when you are in a Vyper (.vy) file

## License

All of Sublime Ethereum is licensed under the MIT license.

Copyright Ⓒ 2015-2021 [uniqpath](https://github.com/uniqpath)

> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:

> The above copyright notice and this permission notice shall be included in
> all copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
> THE SOFTWARE.
