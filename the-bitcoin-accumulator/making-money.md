---
description: How does the protocol make money, and how do Players holding $BTCA benefit?
---

# Making Money

## How does the protocol make money?

The protocol makes money based on the mispricing between $wrBTC and $BTC. In theory, $wrBTC and $BTC should trade at the same price. However, due to market volatility the prices between the two tokens is likely to vary. The protocol can generate a profit in two different ways depending on whether $wrBTC trades above or below $BTC.

#### If $wrBTC trades above $BTC, the protocol profits by selling bonds.

Take for example that bonds are currently priced at 1.2 $BTC. If a Player purchases 1.2 $BTC worth of bonds, the Player will get 1.0 $wrBTC in return.

Since the 1.0 $wrBTC is backed by 1.0 $BTC, there is an excess of 0.2 $BTC. This 0.2 $BTC is the profit the protocol makes from the bond purchase.

![](../.gitbook/assets/Hunter\_Idle\_FullAnimation.gif)

#### If $wrBTC trades below BTC, the protocol profits by buying $wrBTC.

Take for example that $wrBTC is currently trading at 0.9 $BTC.

In this scenario, the protocol will use 0.9 $BTC from its treasury to purchase 1.0 $wrBTC. The newly acquired 1.0 $wrBTC is then burnt.

Since only 0.9 $BTC was used in this operation, there is an excess of 0.1 $BTC. This 0.1 $BTC is the profit the protocol makes from the $wrBTC purchase.

## How do Players holding $BTCA benefit?

The Bitcoin Accumulator protocol shares the profits it makes with Players holding $BTCA tokens. Each time the protocol makes a profit, it distributes it immediately.

Profits are distributed by increasing the backing of the $BTCA tokens; this backing amount is represented via an index.

For example if the $BTCA1 index is currently at 3.5, this means one $BTCA1 token is backed by 3.5 $wrBTC tokens. When the protocol distributes the profits, the index grows. If it grows to 3.6, that means the same one $BTCA1 token is now backed by 3.6 $wrBTC tokens. In this example, the Player holding one $BTCA1 token has effectively accumulated an additional 0.1 bitcoin; this is how Players holding $BTCA passively accumulates more bitcoins over time.

## Profit Sharing

When the protocol makes a profit, it shares the profit between the Players holding $BTCA and Player 2. The current profit split is 50:50. However, as the protocol grows, Player 2 is targeting to scale the profit split to an eventual 80:20 where Players holding $BTCA will get the 80% profit share.

## Additional Reading

Please read our [Token Accumulators Whitepaper](../press-kit/white-papers.md) for more on the profit mechanics and the math behind the index growth.&#x20;
