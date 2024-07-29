<table border="1" style="border-collapse: collapse;">
    <thead>
        <tr>
            <th>Token Name</th>
            <th>Browser</th>
            <th>Exchanges</th>
            <th>Launched date</th>
            <th>External Functionslity</th>
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
            Block bots, weird transaction fees and owner access
            </td>
        </tr>
         <tr>
            <td><a href="#Gravty" target="_blank">Gravity</a></td>
            <td><a href="https://etherscan.io/token/0x9C7BEBa8F6eF6643aBd725e45a4E8387eF260649" target="_blank">Gravity Browser</a></td>
            <td><a href="https://www.binance.com/en/trade/G_USDT?ref=40896146" target="_blank">Binance</a>, <a href="https://bingx.com/en-us/spot/GUSDT" target="_blank">BingX</a>, <a href="https://www.coinex.com/exchange/g-usdt" target="_blank">CoinEx</a> and...</td>
            <td>
            <a href="https://etherscan.io/tx/0x737492fba9caf3eba8488978f7a6e9a0eaf76d17579b37d745dbb80c1a04a4d2"target="_blank">May-13-2024</a>
            </td>
            <td></td>
        <tr>
            <td><a href="#ZKLink" target="_blank">ZKLink</a></td>
            <td><a href="https://etherscan.io/token/0xfc385a1df85660a7e041423db512f779070fcede#writeProxyContract" target="_blank">ZKLink Browser</a></td>
            <td><a href="https://www.bybit.com/en-US/trade/spot/ZKL/USDT" target="_blank">Bybit</a>, <a href="https://bingx.com/en-us/spot/ZKLUSDT" target="_blank">BingX</a>, <a href="https://www.lbank.com/en-US/trade/zkl_usdt/" target="_blank">LBank</a> and...</td>
            <td>
            <a href="https://etherscan.io/tx/0xf19d9535cefe1c5dae66d26c28a7bcfc1cdd09512b0d684832f2c8a01e40b62f"target="_blank">Apr-12-2024</a>
            </td>
            <td><a href="#Upgradeable">Upgradeable</a>, <a href="#ERC20Capped">ERC20Capped</a>, <a href="#EIP-2612ERC20Permit">EIP-2612(ERC20-Permit)</a></td>
        </tr>
    </tbody>
</table>

# KAMALA-HARRIS

## About

HARRIS is a memecoin centered around Kamala Harris, the 49th vice president of the United States and presumptive nominee of the Democratic Party in the 2024 presidential election.

## Functionality Detale

### Bot Blocking

This method allowes owner to block addresses that were diagnoesed as robot. Also there is an access to unblock blocked addresses.

# Gravty

# ZKLink

## About

zkLink aggregates and unifies liquidity across Layer 2 rollups and Layer 1 blockchains. zkLink offers two core solutions: zkLink Nova and zkLink X, using zero-knowledge technology to unify liquidity access across connected blockchains and rollups.

## Functionality Details

### Upgradeable

Thanks to the upgradeability of proxy contracts, we can have a bit more peace of mind about the future and potential challenges.
However, it can cause many security and centrlization issues that can influence the auditing process.

### ERC20Capped

The ERC20Capped contract in OpenZeppelin is an extension of the standard ERC20 contract that sets a cap on the total supply of
tokens that can be minted. This is useful for token projects that want to enforce a maximum limit on the number of tokens that
can ever be created.

### EIP-2612(ERC20Permit)

The ERC20Permit is an extension of the ERC20 standard that adds the ability to perform approvals via signatures, as defined in the EIP-2612 proposal. This allows for gasless approvals, meaning that token holders can approve token transfers with a signature, without needing to send an on-chain transaction themselves.
