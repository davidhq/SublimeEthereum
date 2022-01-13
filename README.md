# Ethereum Solidity Grammar

## Description

[Ethereum][ethereum] is a platform for decentralized applications. Decentralized applications are built with Smart Contracts.

This package contains syntax highlighting for Ethereum's **Smart Contracts** language [Solidity](https://soliditylang.org).

Solidity was initially proposed in August 2014 by [dr. Gavin Wood](https://en.wikipedia.org/wiki/Gavin_Wood). The language was later developed by the Ethereum project's Solidity team, led by Christian Reitwiessner. Solidity is similar in syntax to JavaScript.

Solidity is also used in most Ethereum [rollups](https://l2beat.com/) and some other EVM-compatible L1 distributed systems like [Fantom](https://fantom.foundation/).

[ethereum]: https://www.ethereum.org/

Version of syntax that GitHub is [using](https://github.com/github/linguist/tree/master/vendor/grammars) for [Solidity grammar](https://docs.soliditylang.org/en/latest/grammar.html) is in [linguist branch](https://github.com/davidhq/SublimeEthereum/tree/linguist). This grammar gives all `.sol` files ([example](https://github.com/ethereum/consensus-specs/blob/dev/solidity_deposit_contract/deposit_contract.sol)) its colors (= does _syntax highlighting_).

Another relevant source for Solidity grammar syntax is [vscode-solidity](https://github.com/juanfranblanco/vscode-solidity) (which was originally based on early versions of SublimeEthereum).

Linguist branch is an implementation [with regexes](https://sublime-text-unofficial-documentation.readthedocs.io/en/latest/reference/syntaxdefs.html) but is satisfactory esp. relating to the fact that GitHub does not support stack-based grammars. Main branch (= used in sublime package to enable `.sol` syntax highlighting for [SublimeText](http://www.sublimetext.com/) editor) uses more advanced [context stack](http://www.sublimetext.com/docs/syntax.html) approach to achieve optimal visual results for Smart Contract developers. 

### Languages 👅

Someone once said that the entire human world consists of language and now it is turning out that programming languages are also constructs that make our world. Smart Contracts are becoming a basic human primitive for many digital interactions and their use will radically increase in coming years.  Having a syntax highlighter that faithfully covers the language grammar is important and we are going to keep it up to date and further improve it until it reaches the quality that **Ethereum** deserves. It is not much work time-wise but is honest work and it took considerable effort in the initial steps. Now the burden is less and as Smart Contracts once deployed are permanent so this syntax is more or less permanent, evolving only slightly.

## Installation

[SublimeEthereum](https://packagecontrol.io/packages/Ethereum) on Package Control. 

By following this link you can also see the total number of installs for this package (growing steadily as [more developers join the web3 movement](https://medium.com/electric-capital/electric-capital-developer-report-2021-f37874efea6d)).

**SublimeText** is not the most used editor (got some decent competition lately) but it is still one of the best and will probably never go away. This editor is a viable alternative to [VSCode](https://code.visualstudio.com/) and is not controlled by a [big corporation](https://microsoft.com/) but rather more community based. We should be happy to have both options!

Will document the number of installs each start of year starting from 2021:

- **2021** → 53K installs

[package-control]: https://packagecontrol.io/packages/Ethereum

## Features

* Solidity.sublime-syntax: syntax rules for Ethereum Solidity language
   * Ethereum plugin automatically uses *Solidity language syntax* when you are in a Solidity (.sol) file
* Vyper.sublime-syntax: syntax rules for Ethereum Vyper language
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
