![cover](E:\github仓库\contracts-main\cover.jpg)

# ERC 404

## I. Purpose of Introducing ERC404
100K NFT 404 on Merlin Chain  Launching the First MEME ERC-404 NFT Collection: "HTML Hello World" !

PreSell: 0x1b2f6deb1ef260404f542bd084e381cafe000419

## II. Key Features
1. Conversion Formula: 1 NFT (ERC721) = 1000 Tokens (ERC20).
2. Self-service Conversion Method:
Transferring a quantity of 1000n tokens to the token contract will yield n NFTs, and any remaining tokens less than 1000 will be automatically refunded.
Transferring NFTs to the token contract will yield 98% of the tokens, with the remaining 2% automatically sent to a black hole address for burning.
The purpose of the destruction mechanism are: to increase the value of scarce attribute NFTs and to facilitate the economic model of blind boxes and collectibles gameplay.
3. Significantly reduced gas fees when transferring tokens.
4. NFT IDs are stored in a queue and reused, ensuring that the ID number does not continually increase during minting, thereby preserving the scarcity of attributes.
5. Partial implementation of the IERC721Enumerable.sol interface provides convenience for DApp development.
6. Simple Fair Minting is achieved through token transfers to the token contract.

# MIT License

Copyright (c) 2024 erc404

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
