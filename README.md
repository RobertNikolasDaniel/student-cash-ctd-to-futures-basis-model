# student-cash-ctd-to-futures-basis-model
This project is a simplified educational model designed to demonstrate how the cash U.S. Treasury market interacts with CME Treasury futures pricing through the Cheapest-to-Deliver (CTD) mechanism.

Overview

The spreadsheet allows a student to manually input:

CTD cash bond prices
Conversion factors
CME futures prices
Discount / financing assumptions
Carry assumptions over time

Using those inputs, the model calculates:

Dirty bond prices
Cash-to-futures basis
Basis in 32nds
Projected basis behavior over time

The project also visualizes the projected basis using an automatically updating chart.

Educational Goal

The purpose of this project is not to build a production trading system, but to help students understand the intuition behind:

CME Treasury futures pricing
Cheapest-to-Deliver (CTD) dynamics
Conversion factors
Implied financing and carry
Basis trading
Cash vs futures convergence

Many discussions around Treasury futures remain highly theoretical. This project attempts to make the mechanics visual and interactive using a simple Excel framework.

Important Concepts
Cheapest-to-Deliver (CTD)

CME Treasury futures are deliverable futures contracts backed by a basket of eligible Treasury securities.

Because multiple securities can be delivered into the contract, the market naturally gravitates toward the bond that is economically cheapest to deliver.

This creates the concept of the CTD bond.

Conversion Factors

Since different Treasury securities have different coupons and maturities, CME uses conversion factors to standardize delivery economics.

The futures-adjusted bond value is approximately:

Adjusted Futures Value=Futures Price×Conversion Factor

Cash-to-Futures Basis

The basis represents the spread between the cash Treasury market and the implied futures-adjusted Treasury value.

Simplified educational basis relationship:

Basis=Dirty Cash Price−(Futures Price×Conversion Factor)

Positive or negative basis relationships can emerge due to financing conditions, delivery optionality, repo dynamics, and market positioning.

Features
Manual CTD data input
Simplified carry assumptions
Automatic basis calculations
Basis in price and 32nds
Projected basis visualization
Educational student-friendly design
Expandable CTD rows
Limitations

This is intentionally a simplified educational project.

The model does NOT fully account for:

Repo specialness
Delivery option value
Coupon reinvestment timing
Exact accrued interest settlement mechanics
Invoice price settlement nuance
Dynamic yield curve modeling
Full carry decomposition

Professional rates desks use significantly more advanced infrastructure and real-time market data systems.

Why This Project Exists

This project was built to bridge the gap between:

textbook fixed income theory,
futures contract mechanics,
and actual market intuition.

The goal is to provide a clean, understandable framework for students learning rates trading and Treasury futures products.

As strange as it sounds, simplicity is often more educational than overengineered complexity.

Technologies
Microsoft Excel
Fixed income mathematics
CME Treasury futures concepts
Basis trading intuition
Disclaimer

This project is for educational purposes only.

It is NOT financial advice, trading advice, or institutional-grade pricing infrastructure.
