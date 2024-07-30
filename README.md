- [intro](#intro)
  - [Note](#note)
- [Table](#table)
- [Weird Tokens](#weird-tokens)
  - [KAMALA HARRIS](#kamala-harris)
    - [About](#about)
    - [Special Functionalities](#special-functionalities)
      - [Add Bot(Blocking Users)](#add-botblocking-users)
      - [Transaction Fees](#transaction-fees)
      - [Creating Pool](#creating-pool)
- [Owner Oriented Tokens](#owner-oriented-tokens)
  - [Gravity](#gravity)
    - [About](#about-1)
    - [Special Functionalities](#special-functionalities-1)
      - [Pauseable](#pauseable)
      - [Burnable](#burnable)
      - [Name Changing](#name-changing)
      - [Giving access to users for minting](#giving-access-to-users-for-minting)
- [Standard Tokens](#standard-tokens)
  - [ZKLink](#zklink)
    - [About](#about-2)
    - [Special Functionalities](#special-functionalities-2)
      - [Upgradeable](#upgradeable)
      - [ERC20Capped](#erc20capped)
      - [EIP-2612(ERC20Permit)](#eip-2612erc20permit)
- [Simple Tokens](#simple-tokens)
  - [Mr Miggles](#mr-miggles)
    - [About](#about-3)
    - [Special Functionalities](#special-functionalities-3)
- [Conclusion](#conclusion)
  - [Questions](#questions)
- [Thank You](#thank-you)

# intro

I've searched over 100 recently listed tokens according to [LBank New Listings Page](https://support.lbank.com/hc/en-gb/sections/20838597248025-New-Listing). From all these, I divided them into four categories, Weird Tokens, Owner Oriented Tokens, Standard Tokens and Simple Tokens that we will talk about. In each category, I discussed one token and explained its functionalities, and also mentioned some similar ones.

## Note

Please keep in mind that this is just a simple example; not all tokens follow this category division and many are a combination of all these.

# Table

<table border="1" style="border-collapse: collapse;">
    <thead>
        <tr>
            <th>Token Category</th>
            <th>Token Name</th>
            <th>Browser</th>
            <th>Exchanges</th>
            <th>Launched date</th>
            <th>External Functionality</th>
            <th>Similar Tokens</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1_ <a href="#weird-tokens">Weird Tokens</a></td>
            <td><a href="#KAMALA-HARRIS" target="_blank">KAMALA HARRIS</a></td>
            <td><a href="https://etherscan.io/address/0x155788dd4b3ccd955a5b2d461c7d6504f83f71fa#writeContract" target="_blank">HARRIS Browser</a></td>
            <td><a href="https://www.lbank.com/en-US/trade/harris_usdt/" target="_blank">LBank</a>, <a href="https://www.xt.com/en/trade/harris_usdt" target="_blank">XT.COM</a></td>
            <td>
            <a href="https://etherscan.io/tx/0x182111e9f8808babb49dd5fa6fe47a5bdb695ea94a17a665e400b61114db3bae"target="_blank">Jul-02-2024</a>
            </td>
            <td>
           <a href="#add-botblocking-users">add bot(blocking users)</a>, <a href="#transaction-fees">transaction fees</a>, <a href="#creating-pool">creating pool</a>
            </td>
            <td><a href="https://etherscan.io/token/0xED40aB79a3225902435C26233ed84Fb74bd8FFB8">Gram Slam</a>, <a href="https://etherscan.io/token/0x45804880de22913dafe09f4980848ece6ecbaf78">Paxos Gold</a></td>
        </tr>
         <tr>
         <td>2_ <a href="#owner-oriented-tokens">Owner Oriented Tokens</a></td>
            <td><a href="#Gravity" target="_blank">Gravity</a></td>
            <td><a href="https://etherscan.io/token/0x9C7BEBa8F6eF6643aBd725e45a4E8387eF260649" target="_blank">Gravity Browser</a></td>
            <td><a href="https://www.binance.com/en/trade/G_USDT?ref=40896146" target="_blank">Binance</a>, <a href="https://bingx.com/en-us/spot/GUSDT" target="_blank">BingX</a>, <a href="https://www.coinex.com/exchange/g-usdt" target="_blank">CoinEx</a> and...</td>
            <td>
            <a href="https://etherscan.io/tx/0x737492fba9caf3eba8488978f7a6e9a0eaf76d17579b37d745dbb80c1a04a4d2"target="_blank">May-13-2024</a>
            </td>
            <td><a href="#pauseable">pauseable</a>, <a href="#burnable">burnable</a>, <a href="#name-changing">name changing</a>, <a href="#giving-access-to-users-for-minting">giving access to users for minting</a></td>
            <td><a href="https://polygonscan.com/token/0x3af2dd7b91d8faceccc26d21a065267817213d37">Ribus</a>, <a href="https://etherscan.io/token/0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48">USDC</a></td>
        <tr>
        <td>3_ <a href="#standard-tokens">Standard Tokens</td>
            <td><a href="#ZKLink" target="_blank">ZKLink</a></td>
            <td><a href="https://etherscan.io/token/0xfc385a1df85660a7e041423db512f779070fcede#writeProxyContract" target="_blank">ZKLink Browser</a></td>
            <td><a href="https://www.bybit.com/en-US/trade/spot/ZKL/USDT" target="_blank">Bybit</a>, <a href="https://bingx.com/en-us/spot/ZKLUSDT" target="_blank">BingX</a>, <a href="https://www.lbank.com/en-US/trade/zkl_usdt/" target="_blank">LBank</a> and...</td>
            <td>
            <a href="https://etherscan.io/tx/0xf19d9535cefe1c5dae66d26c28a7bcfc1cdd09512b0d684832f2c8a01e40b62f"target="_blank">Apr-12-2024</a>
            </td>
            <td><a href="#Upgradeable">upgradeable</a>, <a href="#ERC20Capped">ERC20Capped</a>, <a href="#EIP-2612ERC20Permit">EIP-2612(ERC20-Permit)</a></td>
            <td><a href="https://etherscan.io/token/0xbe0Ed4138121EcFC5c0E56B40517da27E6c5226B#writeContract">Aethir</a>, <a href="https://etherscan.io/token/0x1f9840a85d5af5bf1d1762f925bdaddc4201f984#writeContract">UNI</a></td>
        </tr>
        <tr>
        <td>4_ <a href="#simple-tokens">Simple Tokens</a></td>
            <td><a href="#mr-miggles" target="_blank">Mr Miggles</a></td>
            <td><a href="https://basescan.org/token/0xb1a03eda10342529bbf8eb700a06c60441fef25d" target="_blank">Mr Miggles Browser</a></td>
            <td><a href="https://www.coinex.com/exchange/miggles-usdt" target="_blank">CoinEx</a>, <a href="https://bingx.com/en-us/spot/MIGGLESUSDT" target="_blank">BingX</a>, <a href="https://www.lbank.com/en-US/trade/miggles_usdt/" target="_blank">LBank</a> and...</td>
            <td>
            <a href="https://basescan.org/tx/0xafe90827147e28e21ce747dd112c962d5fcf33823accfde7e99fa14af51f6d90"target="_blank">Jul-16-2024</a>
            </td>
            <td><a href="#special-functionalities-3">Nothing!!!</a></td>
            <td><a href="https://etherscan.io/address/0x6135177a17e02658df99a07a2841464deb5b8589#readContract">Fear Not</a>, <a href="https://cronoscan.com/address/0x3b41B27E74Dd366CE27cB389dc7877D4e1516d4d">Mistery</a>, <a href="https://etherscan.io/token/0x03a9D7c8CAf836De35666c5f7e317306B54fDd4E#writeContract">JC Coin</a> and many more...</td>
        </tr>
    </tbody>
</table>

# Weird Tokens

These tokens is more common in memecoins. They allows owner or owners of the Token to blocking users, getting transaction fees, open and close trading and etc. These contracts can cause centralization issues. They're not safe and it is not recommended to use them as a reference. For more information about weird tokens click [here](https://github.com/d-xo/weird-erc20)

## KAMALA HARRIS

### About

HARRIS is a memecoin centered around Kamala Harris, the 49th vice president of the United States and presumptive nominee of the Democratic Party in the 2024 presidential election.

### Special Functionalities

#### Add Bot(Blocking Users)

The `addBot` function in this token is a way to prevent from unusual performance of bots. If a user is recognized as a bot, the owner can block the user by calling the `addBot` function, rendering them unable to perform any actions.. It could be very useful, however it can cause centralization issues. Also there is a `delBot` function for unblocking users. It is like `blacklist`, which is very common(like USDT).

#### Transaction Fees

This contract has given an ability to owner, for getting extra fees per every transaction(keep in mind that these fees are calculated more complicated than what I said, but the main idea is the same).

#### Creating Pool

This functionality is not actually weird (compare to what we saw in previous ones). The `openTrading` function creates a pool pair to WETH.

# Owner Oriented Tokens

These tokens gives the owner some abilities, but not self-interested like Weird Token category. These methods make owner able to manage the token easier.

## Gravity

### About

G is the native token on Gravity and the utility token for both Gravity and the Galxe ecosystem. G powers transactions as the gas token and secures the network through staking. As the primary utility token across both ecosystems, G drives governance decisions, incentivizes growth, and facilitates payments.

### Special Functionalities

#### Pauseable

The Pausable contract in OpenZeppelin is a utility that allows you to pause and unpause certain functions in your smart contract. This can be particularly useful in scenarios where you need to temporarily suspend contract operations due to maintenance, upgrades, or security concerns.

#### Burnable

The ERC20Burnable contract in OpenZeppelin is an extension of the ERC20 standard that adds the ability to irreversibly destroy ("burn") tokens. This can be useful for various reasons, such as reducing the total supply of tokens in circulation, implementing deflationary tokenomics, or removing tokens from specific accounts.

#### Name Changing

This token, has a special function named `setName` that allows the owner to change the token name.

#### Giving access to users for minting

In general, minting process must be controlled by owner or owners of the contract. This Contract has done this action with giving users a _minting limit_, that allows them to mint the token.

# Standard Tokens

These tokens use standard libraries for developing. Although they use useful options, they are completely safe. It is recommended to use these tokens as a reference.

## ZKLink

### About

zkLink aggregates and unifies liquidity across Layer 2 rollups and Layer 1 blockchains. zkLink offers two core solutions: zkLink Nova and zkLink X, using zero-knowledge technology to unify liquidity access across connected blockchains and rollups.

### Special Functionalities

#### Upgradeable

Thanks to the upgradeability of proxy contracts, we can have a bit more peace of mind about the future and potential challenges.
However, it can cause many security and centralization issues that can influence the auditing process.

#### ERC20Capped

The ERC20Capped contract in OpenZeppelin is an extension of the standard ERC20 contract that sets a cap on the total supply of
tokens that can be minted. This is useful for token projects that want to enforce a maximum limit on the number of tokens that
can ever be created.

#### EIP-2612(ERC20Permit)

The ERC20Permit is an extension of the ERC20 standard that adds the ability to perform approvals via signatures, as defined in the EIP-2612 proposal. This allows for gasless approvals, meaning that token holders can approve token transfers with a signature, without needing to send an on-chain transaction themselves.

# Simple Tokens

Totally simple Tokens! They use only ERC20 functions, maybe a bit additional options but not very effective.(_80% of tokens that I reviewed was in this category_)

## Mr Miggles

### About

The official cat Coinbase mascot.

### Special Functionalities

As you can see in this token contract, there is no special option, method, or functionality, yet it is still a high market cap token listed on many well-known exchanges.. However, it is still one of the most resent launched tokens!

# Conclusion

Finally, I suggest you first understand what you want to do For this purpose, I've prepared a list of questions. Please read and answer them carefully, then give me the answers.

## Questions

_1 Do you think you will need to upgrade your token later?_<br>
_2 Do you want your token to be mintable? if so, do you want to set a maximum limit of supply?_<br>
_3 Do you want your token to be burnable?_<br>
_4 Do you want your token to be pauseable?_<br>
_5 Do you want to have an ability to block the bad users?_<br>
_6 Do you want to get external Fees?_<br>
_7 Do you want to use EIP-2612 Standard?_<br>

# Thank You
