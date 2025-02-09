---

title: Liquidity Pools
nav_order: 6
has_children:

---

# Liquidity Pools


Equalizer is an AMM which uses the traditional liquidity pool system to create tradable pairs. The system we have deployed is, in our opinion, an improvement on the uniswap system that uses fees to incentivize these pools. Instead, we use a continuous loop system to utilise tokens tied to the fees to incentivize our system. This system creates an equalized situation which can allow for token utility and growth.

The reason we have selected this model is to empower the use of our token and create a system where people lock the token for the benefits it provides. 

The incentive system will provide a steady loop of incentives to ensure a low slippage trade can be completed with fair fee charges.

## Fees

Equalizer has set the fees at a rate of 0.2% per trade for volatile pairs and 0.02% for stable pairs. This fee with the acceptance of the community on either type of pair can be increased to 0.3%. This fee structure supports the promotion and retention of liquidity, which is essential for maintaining low slippage trades. 

Most of the AMM's in the market use a similar fee amount to reward Liquidity Providers. From our detailed research, we have found that this fee is necessary to sustain a healthy environment for attracting liquidity. One should not focus only on the fee amount, but the efficiency of the trade that they can complete on the AMM. For this reason, the Equalizer model is the first of its kind to create a sustainable dex that supports the equilibrium required to maintain an effective balance to LP providers and token holders for stable and volatile assets.

## Stable Pools

Stable pools are designed for assets which have little to no volatility. This means that the formula used for pricing the assets allows for low slippage, even on large traded volumes.

x³y + y³x = k

## Variable Pools

Variable pools are designed for assets with high price volatility. These pools use a generic AMM formula.

x × y = k
