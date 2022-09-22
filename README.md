## SublimeText syntax highlighting for Solidity, Vyper, Yul and Cairo

<img src="./img/logos.svg">

Version of syntax that GitHub is [using](https://github.com/github/linguist/tree/master/vendor/grammars) for [Solidity grammar](https://docs.soliditylang.org/en/latest/grammar.html) and [Vyper](https://vyper.readthedocs.io) is in [linguist branch](https://github.com/davidhq/SublimeEthereum/tree/linguist). This grammar gives all `.sol` / `.vy` files ([example](https://github.com/ethereum/consensus-specs/blob/dev/solidity_deposit_contract/deposit_contract.sol)) its colors (= does _syntax highlighting_).

### Ethereum

[Ethereum][ethereum] is a platform for decentralized applications. Decentralized applications are built with Smart Contracts.

### StarkNet

[StarkNet](https://starkware.co/starknet/) is a permissionless decentralized ZK-Rollup operating as an L2 network over Ethereum, where any dApp can achieve unlimited scale for its computation, without compromising Ethereum’s composability and security.

### Included grammars

This package contains syntax highlighting for Ethereum's Smart Contract languages [Solidity](https://soliditylang.org), [Vyper](https://vyper.readthedocs.io), [Yul](https://docs.soliditylang.org/en/latest/yul.html) as well as StarkNet [Cairo](https://www.cairo-lang.org/docs/index.html) language.

Solidity is the biggest Ethereum language and has similarity to JavaScript. Solidity was initially proposed in August 2014 by [dr. Gavin Wood](https://en.wikipedia.org/wiki/Gavin_Wood). The language was later developed by the Ethereum project's Solidity team, led by Christian Reitwiessner.

Vyper is a contract-oriented, pythonic programming language that targets the Ethereum Virtual Machine (EVM) as well. It lacks some general features and through this strives to be more secure by default.

Yul is an intermediate EVM programming language that is compiled to bytecode for addressing the needs of different backends. The Solidity compiler has an experimental implementation that uses Yul as an intermediate language.

Cairo is a programming language for writing provable programs, where one party can prove to another that a certain computation was executed correctly. Cairo and similar proof systems can be used to provide scalability to blockchains.

[ethereum]: https://www.ethereum.org/

[Linguist branch](https://github.com/davidhq/SublimeEthereum/tree/linguist) has an implementation [with regexes](https://sublime-text-unofficial-documentation.readthedocs.io/en/latest/reference/syntaxdefs.html) and is used in GitHub. Main branch (= used in sublime package to enable `.sol` syntax highlighting for [SublimeText](http://www.sublimetext.com/) editor) uses more advanced [context stack](http://www.sublimetext.com/docs/syntax.html) approach to achieve optimal and more detailed results from what is possible with regex based approach.

## Installation in SublimeText editor

1. SublimeText menu / Preferences / Package Control
2. Select: Install Package
3. Type **Ethereum** and press ENTER
4. With a `.sol` / `.vy` / `.cairo` file open, select: View -> Syntax (-> Open all with current extension as) -> Ethereum -> Cairo / Solidity / Vyper / Yul
5. Close and re-open any files to activate the syntax highlighting

This will provide **Solidity** `.sol`, **Vyper** `.vy` and **Cairo** `.cairo` syntax highlighting.

[SublimeEthereum](https://packagecontrol.io/packages/Ethereum) on Package Control. 

[package-control]: https://packagecontrol.io/packages/Ethereum

## Features

* Solidity.sublime-syntax: syntax rules for Ethereum Solidity language
   * Ethereum plugin automatically uses *Solidity language syntax* when you are in a Solidity (.sol) file
   * [vscode-solidity](https://github.com/juanfranblanco/vscode-solidity) is another good grammar implementation, it was originally derived from SublimeEthereum
* Vyper.YAML-tmLanguage: syntax rules for Ethereum Vyper language
   * Ethereum plugin automatically uses *Vyper language syntax* when you are in a Vyper (.vy) file
* Yul.YAML-tmLanguage: syntax rules for Ethereum Yul language
   * Ethereum plugin automatically uses *Yul language syntax* when you are in a Yul (.yul) or Yul+ (.yulp) file
* Cairo.YAML-tmLanguage: syntax rules for StarkNet Cairo language
   * Ethereum plugin automatically uses *Cairo language syntax* when you are in a Cairo (.cairo) file
   * Cairo language grammar is derived from Atom grammar in [this repository](https://github.com/xshitaka/atom-language-cairo) by GitHub user _xshitaka_.

## License

All of Sublime Ethereum is licensed under the MIT license.

Copyright Ⓒ 2015-2222 [uniqpath](https://github.com/uniqpath)

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
