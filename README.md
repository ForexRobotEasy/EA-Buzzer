# EA Buzzer ReadMe File

This ReadMe file provides a brief overview of the code for the EA Buzzer Expert Advisor. Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## Table of Contents
1. [Global Variables](#global-variables)
2. [Opening New Series of Orders](#opening-new-series-of-orders)
3. [Trading Function for Buying or Selling](#trading-function-for-buying-or-selling)
4. [Managing Manual Orders](#managing-manual-orders)
5. [Expert Advisor Start Function](#expert-advisor-start-function)
6. [Expert Advisor Tick Function](#expert-advisor-tick-function)
7. [Expert Advisor Deinitialization Function](#expert-advisor-deinitialization-function)

## Global Variables<a name='global-variables'></a>
- `openNewSeries`: Enable/disable the opening of another series of orders.
- `tradeBuy`: Enable buying in the market.
- `tradeSell`: Enable selling in the market.
- `manageManualOrders`: Enable EA Buzzer to manage manual orders.

## Opening New Series of Orders<a name='opening-new-series-of-orders'></a>
The function `OpenNewSeries()` is responsible for opening a new series of orders. You can add your specific code for opening new series of orders inside this function.

## Trading Function for Buying or Selling<a name='trading-function-for-buying-or-selling'></a>
The function `Trade()` is responsible for executing the buying or selling trades. If `tradeBuy` is enabled, you can add your code for buying inside the if statement. If `tradeSell` is enabled, you can add your code for selling inside the if statement.

## Managing Manual Orders<a name='managing-manual-orders'></a>
The function `ManageManualOrders()` is responsible for managing manual orders. If `manageManualOrders` is enabled, you can add your code for managing manual orders inside this function.

## Expert Advisor Start Function<a name='expert-advisor-start-function'></a>
The `OnInit()` function is the start function of the Expert Advisor. You can add your initialization code inside this function.

## Expert Advisor Tick Function<a name='expert-advisor-tick-function'></a>
The `OnTick()` function is called on every tick of the market. This function is responsible for executing the main logic of the Expert Advisor. It calls the `OpenNewSeries()`, `Trade()`, and `ManageManualOrders()` functions based on the specified conditions.

## Expert Advisor Deinitialization Function<a name='expert-advisor-deinitialization-function'></a>
The `OnDeinit()` function is called when the Expert Advisor is being deinitialized. You can add your deinitialization code inside this function.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - EA Buzzer Review](https://forexroboteasy.com/forex-robot-review/review-ea-buzzer-advanced-night-scalping-system-for-precise-entries/).
