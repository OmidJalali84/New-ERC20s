- [Chart](#chart)
- [KAMALA HARRIS](#kamala-harris)
  - [About](#about)
  - [Special Functionalities](#special-functionalities)
    - [Bot Blocking](#bot-blocking)
    - [weird Transaction Fees And Owner Access](#weird-transaction-fees-and-owner-access)
- [Gravity](#gravity)
  - [About](#about-1)
  - [Special Functionalities](#special-functionalities-1)
    - [Pauseable](#pauseable)
    - [Burnable](#burnable)
    - [Name Changing](#name-changing)
    - [Giving access to users for minting(by owner)](#giving-access-to-users-for-mintingby-owner)
- [ZKLink](#zklink)
  - [About](#about-2)
  - [Special Functionalities](#special-functionalities-2)
    - [Upgradeable](#upgradeable)
    - [ERC20Capped](#erc20capped)
    - [EIP-2612(ERC20Permit)](#eip-2612erc20permit)
- [Mr Miggles](#mr-miggles)
  - [About](#about-3)
  - [Special Functionalities](#special-functionalities-3)

# Chart

<table border="1" style="border-collapse: collapse;">
    <thead>
        <tr>
            <th>Token Name</th>
            <th>Browser</th>
            <th>Exchanges</th>
            <th>Launched date</th>
            <th>External Functionality</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="#KAMALA-HARRIS" target="_blank">KAMALA HARRIS</a></td>
            <td><a href="https://etherscan.io/address/0x155788dd4b3ccd955a5b2d461c7d6504f83f71fa#writeContract" target="_blank">HARRIS Browser</a></td>
            <td><a href="https://www.lbank.com/en-US/trade/harris_usdt/" target="_blank">LBank</a>, <a href="https://www.xt.com/en/trade/harris_usdt" target="_blank">XT.COM</a></td>
            <td>
            <a href="https://etherscan.io/tx/0x182111e9f8808babb49dd5fa6fe47a5bdb695ea94a17a665e400b61114db3bae"target="_blank">Jul-02-2024</a>
            </td>
            <td>
            <a href="#bot-blocking">block bots</a>, <a href="#weird-transaction-fees-and-owner-access">weird transaction fees and owner access</a>
            </td>
        </tr>
         <tr>
            <td><a href="#Gravity" target="_blank">Gravity</a></td>
            <td><a href="https://etherscan.io/token/0x9C7BEBa8F6eF6643aBd725e45a4E8387eF260649" target="_blank">Gravity Browser</a></td>
            <td><a href="https://www.binance.com/en/trade/G_USDT?ref=40896146" target="_blank">Binance</a>, <a href="https://bingx.com/en-us/spot/GUSDT" target="_blank">BingX</a>, <a href="https://www.coinex.com/exchange/g-usdt" target="_blank">CoinEx</a> and...</td>
            <td>
            <a href="https://etherscan.io/tx/0x737492fba9caf3eba8488978f7a6e9a0eaf76d17579b37d745dbb80c1a04a4d2"target="_blank">May-13-2024</a>
            </td>
            <td><a href="#pauseable">pauseable</a>, <a href="#burnable">burnable</a>, <a href="#name-changing">name changing</a>, <a href="#giving-access-to-users-for-mintingby-owner">giving access to users for minting(by owner)</a></td>
        <tr>
            <td><a href="#ZKLink" target="_blank">ZKLink</a></td>
            <td><a href="https://etherscan.io/token/0xfc385a1df85660a7e041423db512f779070fcede#writeProxyContract" target="_blank">ZKLink Browser</a></td>
            <td><a href="https://www.bybit.com/en-US/trade/spot/ZKL/USDT" target="_blank">Bybit</a>, <a href="https://bingx.com/en-us/spot/ZKLUSDT" target="_blank">BingX</a>, <a href="https://www.lbank.com/en-US/trade/zkl_usdt/" target="_blank">LBank</a> and...</td>
            <td>
            <a href="https://etherscan.io/tx/0xf19d9535cefe1c5dae66d26c28a7bcfc1cdd09512b0d684832f2c8a01e40b62f"target="_blank">Apr-12-2024</a>
            </td>
            <td><a href="#Upgradeable">upgradeable</a>, <a href="#ERC20Capped">ERC20Capped</a>, <a href="#EIP-2612ERC20Permit">EIP-2612(ERC20-Permit)</a></td>
        </tr>
        <tr>
            <td><a href="#ZKLink" target="_blank">Mr Miggles</a></td>
            <td><a href="https://basescan.org/token/0xb1a03eda10342529bbf8eb700a06c60441fef25d" target="_blank">Mr Miggles Browser</a></td>
            <td><a href="https://www.coinex.com/exchange/miggles-usdt" target="_blank">CoinEx</a>, <a href="https://bingx.com/en-us/spot/MIGGLESUSDT" target="_blank">BingX</a>, <a href="https://www.lbank.com/en-US/trade/miggles_usdt/" target="_blank">LBank</a> and...</td>
            <td>
            <a href="https://basescan.org/tx/0xafe90827147e28e21ce747dd112c962d5fcf33823accfde7e99fa14af51f6d90"target="_blank">Jul-16-2024</a>
            </td>
            <td><a href="#special-functionalities-3">Nothing!!!</a></td>
        </tr>
    </tbody>
</table>

# KAMALA HARRIS

## About

HARRIS is a memecoin centered around Kamala Harris, the 49th vice president of the United States and presumptive nominee of the Democratic Party in the 2024 presidential election.

## Special Functionalities

### Bot Blocking

This method allows owner to block addresses that were diagnoses as robot. Also there is an access to unblock blocked addresses.

### weird Transaction Fees And Owner Access

Some tokens contracts give some unusual access to the owner of token, like blocking users (black list), getting transaction fees, open and close trading and etc. It more appears in memecoins and it recommended not to use these options.

# Gravity

## About

G is the native token on Gravity and the utility token for both Gravity and the Galxe ecosystem. G powers transactions as the gas token and secures the network through staking. As the primary utility token across both ecosystems, G drives governance decisions, incentivizes growth, and facilitates payments.

## Special Functionalities

### Pauseable

The Pausable contract in OpenZeppelin is a utility that allows you to pause and unpause certain functions in your smart contract. This can be particularly useful in scenarios where you need to temporarily suspend contract operations due to maintenance, upgrades, or security concerns.

### Burnable

The ERC20Burnable contract in OpenZeppelin is an extension of the ERC20 standard that adds the ability to irreversibly destroy ("burn") tokens. This can be useful for various reasons, such as reducing the total supply of tokens in circulation, implementing deflationary tokenomics, or removing tokens from specific accounts.

### Name Changing

This token, has a special function named `setName` that allows owner to change the token name.

### Giving access to users for minting(by owner)

In general, minting process must be controlled by owner or owners of the contract. This Contract has done this action with giving users a _minting limit_, that allows them to mint the token.

# ZKLink

## About

zkLink aggregates and unifies liquidity across Layer 2 rollups and Layer 1 blockchains. zkLink offers two core solutions: zkLink Nova and zkLink X, using zero-knowledge technology to unify liquidity access across connected blockchains and rollups.

## Special Functionalities

### Upgradeable

Thanks to the upgradeability of proxy contracts, we can have a bit more peace of mind about the future and potential challenges.
However, it can cause many security and centralization issues that can influence the auditing process.

### ERC20Capped

The ERC20Capped contract in OpenZeppelin is an extension of the standard ERC20 contract that sets a cap on the total supply of
tokens that can be minted. This is useful for token projects that want to enforce a maximum limit on the number of tokens that
can ever be created.

### EIP-2612(ERC20Permit)

The ERC20Permit is an extension of the ERC20 standard that adds the ability to perform approvals via signatures, as defined in the EIP-2612 proposal. This allows for gasless approvals, meaning that token holders can approve token transfers with a signature, without needing to send an on-chain transaction themselves.

# Mr Miggles

## About

The official cat Coinbase mascot.

## Special Functionalities

As you can see in this token contract, there is no special option or method or functionality and it is still a high marker kap token, listed in many known exchanges. However, it is still one of the most resent launched tokens! Also the [Fear Not](https://etherscan.io/address/0x6135177a17e02658df99a07a2841464deb5b8589#readContract) token is like this.

