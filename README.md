# HFT Pass Prop Firm MT4

This repository contains the code for the HFT Pass Prop Firm MT4 software. This software is developed by Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com).

## Product Description

HFT Pass Prop Firm MT4 is a high-frequency trading (HFT) software designed for the MetaTrader 4 platform. It aims to provide profitable trading opportunities by executing buy and sell orders based on current market conditions.

#### Features:
- Uses a predefined magic number to identify its own trades
- Executes trades with a fixed volume of 0.01 lots
- Sets a stop loss at 50 pips and a take profit at 100 pips
- Monitors available funds and checks for insufficient balance
- Checks for existing positions and avoids opening duplicate trades
- Places buy and sell orders based on current market bid and ask prices
- Calculates profit/loss by summing up the profits of all open positions
- Implements risk management actions through the OnTimer() function
- Monitors trade transactions through the OnTradeTransaction() function

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample that demonstrates how the software can work as described. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [this link](https://forexroboteasy.com/forex-robot-review/hft-pass-prop-firm-mt4-software-unbiased-review-real-results/).

## Installation

To use this software, follow the steps below:

1. Open the MetaTrader 4 platform.
2. Go to 'File' -> 'Open Data Folder'.
3. Open the 'MQL4' folder.
4. Create a new folder and name it 'Experts'.
5. Place the source code file (HFT_Pass_Prop_Firm_MT4.mq4) into the 'Experts' folder.
6. Restart MetaTrader 4.
7. Open a chart for the desired symbol and timeframe.
8. Drag and drop the software onto the chart.
9. Make sure the 'Allow Automated Trading' option is enabled in the platform settings.

## Usage

Once the software is installed and attached to a chart, it will start executing trades based on the defined parameters. It will check for available funds, existing positions, and current market conditions before placing buy and sell orders. Profit/loss calculation and risk management actions are also performed.

Please note that this software is provided as is and does not guarantee profitable trading results. It is recommended to test the software on a demo account before using it with real funds.

## Support

For any inquiries or technical support regarding this software, please contact the official developer through their website [forexroboteasy.com](https://forexroboteasy.com).

## License

This software is distributed under the [MIT License](LICENSE).
