# Session Colored Bars Forex Software for Strategic Trading

This code is a sample implementation of a Forex software that colors bars on a chart based on different trading sessions. It is designed to help traders visually identify trading sessions and strategically plan their trades accordingly.

## How it Works

The code defines a struct called `SessionSettings` that holds the session start and end time, the bar color for the session, and the high and low values for the session. It also defines an enum called `SessionColor` to easily assign colors to each session.

The code then creates three instances of `SessionSettings` for the Asian, London, and US sessions, and sets their respective values.

The main function `ColorBarsBySession()` is responsible for looping through each bar on the chart and determining its trading session based on its timestamp. It uses the helper function `TimeInSession()` to check if the given bar time falls within a specific session.

If the bar is in the Asian session, it sets the session start and end time, colors the bar with the session color, and sets the high and low values for the session. The same process is repeated for the London and US sessions.

The helper function `TimeInSession()` takes a bar time and a session time as parameters. It extracts the start and end hour and minute values from the session time and calculates the session start and end times based on the current time. It then checks if the bar time falls within the calculated session start and end times.

The functions `SetBarColor()`, `SetBarHigh()`, and `SetBarLow()` are helper functions that set the color, high value, and low value of a specific bar on the chart.

The entry point of the program is the `OnStart()` function, which calls the `ColorBarsBySession()` function to color the bars on the chart based on the trading sessions.

## Product Description

The Session Colored Bars Forex Software for Strategic Trading is a powerful tool designed to enhance the trading experience and improve trading strategies. By visually highlighting different trading sessions on the chart, traders can easily identify key trading opportunities and make informed decisions.

Key Features:
- Colors bars on the chart based on different trading sessions (Asian, London, and US sessions).
- Displays the high and low values of each session for easy reference.
- Helps traders identify key trading opportunities and plan their trades strategically.
- Works on multiple timeframes and currency pairs.

This product is developed by Forex Robot Easy Team, a team of experienced traders and developers dedicated to creating innovative and reliable Forex trading tools. For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-session-colored-bars-forex-software-for-strategic-trading/).

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates how this product can work as described. To find the official developer of this product and obtain the full version, please refer to MQL5, the official marketplace for Forex trading tools and indicators.
