# student-cash-ctd-to-futures-basis-model

Educational Excel model for understanding CME Treasury futures basis trading and Cheapest-to-Deliver (CTD) mechanics.

## Overview

This project is a simplified educational model showing how U.S. Treasury cash securities interact with CME Treasury futures pricing.

The spreadsheet allows manual input of:

- CTD cash prices
- Futures prices
- Conversion factors
- Discount / financing assumptions

The model then calculates:

- Dirty prices
- Cash-to-futures basis
- Basis in 32nds
- Projected basis movement over time

A simple chart visualizes projected basis behavior.

---

## Concepts Covered

### Cheapest-to-Deliver (CTD)

CME Treasury futures are backed by a basket of eligible Treasury securities.

Because multiple bonds may be delivered into the contract, the market tends to favor the bond that is economically cheapest to deliver.

This becomes the CTD security.

---

### Conversion Factors

CME uses conversion factors to normalize bonds with different coupons and maturities.

Simplified relationship:

Basis Adjusted Futures Value = Futures Price × Conversion Factor

---

### Cash-to-Futures Basis

Simplified basis relationship:

Basis = Dirty Cash Price − (Futures Price × Conversion Factor)

This spread is commonly referred to as the Treasury futures basis.

---

## Features

- Manual CTD input
- Simplified financing assumptions
- Automatic basis calculations
- Basis in price and 32nds
- Projected basis chart
- Expandable CTD rows
- Student-friendly structure

---

## Educational Purpose

This project was built to help students better understand:

- Treasury futures pricing
- CTD mechanics
- Futures carry
- Basis trading intuition
- Cash vs futures convergence

The goal was simplicity and intuition rather than institutional complexity.

---

## Limitations

This is a simplified educational model.

It does not fully account for:

- repo specialness
- delivery optionality
- coupon reinvestment timing
- settlement nuances
- dynamic curve modeling
- real-time market data

---

## Technologies

- Microsoft Excel
- Fixed income mathematics
- CME Treasury futures concepts

---

## Disclaimer

This project is for educational purposes only.

It is not financial advice or institutional trading infrastructure.

It is NOT financial advice, trading advice, or institutional-grade pricing infrastructure.
