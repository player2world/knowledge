---
description: Introducing Player 2’s Primary Currency
---

# The Deo

## **What is it?** <a href="#2a2d" id="2a2d"></a>

The Deo will serve as the primary currency of Player 2. The name “Deo” is derived from the Greek word δύο (pronounced dýo) which means “two”. We also think the name “Deos” rolls off the tongue naturally and makes for a great currency name.

## **The Problem with Fiat Money** <a href="#cee6" id="cee6"></a>

Fiat money is money that is backed by the issuing government. It has no intrinsic value and is purely dependent on the stability of the government itself.

In the worst case scenario, the government can collapse entirely, rendering its money worthless. Or the government can print copious amounts of its money, also rendering its money essentially worthless; this has happened in many countries such as Hungary (1945), Zimbabwe (2007), and most recently Venezuela (2019). In these scenarios, entire life savings of their citizens were wiped out.

Barring extreme situations, even supposedly AAA money have seen their governments turn to excessive printing in times of duress. The biggest fiat currency in the world is the US Dollar, and between 2020-2021 the US Federal Reserve grew its balance sheet from about US$4 trillion to slightly south of US$9 trillion due to COVID-19. The result is the country experiencing its highest inflation in 40 years.

## **The Problem with Stablecoins** <a href="#96d5" id="96d5"></a>

Stablecoins are generally seen as a safe way to keep one’s assets in cryptocurrency without the risk of volatility.

The unfortunate common denominator is that they are pegged to the US Dollar. While the US Dollar is less volatile than cryptocurrencies in general, we have established that fiat has many problems. Hence, that is not something we should be pegging our Deo to in the long run.

## **What should Good Money Look Like?** <a href="#a3f6" id="a3f6"></a>

Good money should have the following characteristics:

1. It cannot be counterfeited
2. It is widely accepted
3. It is fully backed
4. It has the ability to maintain purchasing power parity

While none of the traditional fiat currencies hold all these qualities, it is very possible to create such a currency using cryptography.

Cryptocurrencies inherently tackles point 1. As cryptocurrencies gain adoption, that will likely increase acceptance, taking care of point 2. This leaves the last two points.

## **A Weighted Reserve** <a href="#23e3" id="23e3"></a>

In order to fulfill both points 3 and 4, we endeavor to have the Deo collateralized by a Reserve consisting of a basket of cryptocurrencies that broadly represents the crypto market.

As an example, let us assume that the crypto market only consists of three cryptocurrencies: C1, C2, and C3. If C1 commands 50% of the market, and C2 and C3 commands 25% each, our Reserve would contain 50% C1, 25% C2, and 25% C3. This backing allows us to create a peg between Deos and the underlying basket of cryptocurrencies.

This weighted Reserve ensures that our Deos are fully backed and maintains purchasing power parity with the broader crypto market.

## Responding to Demand

With the peg setup, the core job of those managing the Reserve would be to keep the peg within a small range. If demand for the Deo rises, then the Deo would trade at a premium to the peg. Reserve should mint and sell new Deos, and use the proceeds to purchase the basket of cryptocurrencies.

This does two things:

1. Allows the newly minted Deos to be properly collateralized and
2. Brings the Deo back to its peg.

Conversely, if demand for the Deo falls, the Reserve should buy back Deos from the open market and sell the equivalent value from their basket of cryptocurrencies. The Deos that were purchased should then be burnt. This brings the Deo back to its peg while still maintaining the correct collateralization.

This is how the Deos will remain pegged while allowing for the expansion and contraction of the Player 2 economy.

## **The Perfect Money** <a href="#42ad" id="42ad"></a>

Our design allows for three of the four characteristics to be fulfilled, but whether the Deo becomes widely accepted is something we have to work hard on. However, if it does, **the Deo will be perfect money**.
