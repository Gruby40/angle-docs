---
description: How to mint and burn agTokens using Angle app
---

# Minting & Burning agTokens

## Approving tokens

To interact with Angle protocol, you will need to approve tokens for each collateral/stablecoin pool. You can learn more about approving tokens [here](app-faq/#why-do-i-need-to-approve-the-same-token-multiple-times).

![Approving tokens](../.gitbook/assets/approving-tokens.png)

## Minting

1. Go to [app.angle.money](https://app.angle.money).
2. Make sure that you have ETH to pay for gas fees, as well as some of the tokens accepted as collateral.
3. Select the collateral you want to send, and the stablecoin you want to mint/receive.
   * Supported collaterals: DAI, USDC
   * Available agTokens: agEUR
4. Approve your collateral. You will need to approve your collateral for every collateral/agToken pair (more details [here](app-faq.md)).
5. Mint your stablecoins against collateral.

You now have stable tokens that mirror the value of the assets they are pegged to (EUR for agEUR for example).

![Minting agEUR](../.gitbook/assets/mint-usdc-agEUR.png)

## Burning

Burning agTokens is a similar process than minting.

1. Click on the `Burn` tab.
2. Select the agToken you want to burn and the collateral you want to receive.
3. All the agTokens are approved by default on Angle.
4. Send your agTokens, and you will get back the corresponding amount of collateral you selected.

![Burning agEUR](../.gitbook/assets/burn-agEUR-DAI.png)
