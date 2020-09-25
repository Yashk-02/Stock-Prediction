# Myprojects
This Python program  allows users to consult/analyse/model stock times-series.
It will source its data online, but will optimise the use of downloaded data, to avoid excessive network traffic.

The Code has been made keeping in mind the users are advanced Business Analysts, but without programming knowledge.

The users have the possibility of searching for specific stocks, and query specified time ranges, along with associated
analysis, such as statistical descriptions of prices and/or volume (mean, median, range, etc), technical
indicators, visualisation (of the raw data, but also of transformations, such as moving averages), and even
basic modelling (such as regression).
The program provides a comprehensive but easy to use and intuitive interface (text or graphical).

It provide descriptive analytics of the trading price for any company the user
selects. These include:
• Mean;
• Quartiles;
• Range (=max-min);
• Standard variation;
• Coefficient of variation;
• Normalised price values;
It also provides a way to graphically visualise data related to any company, such as:
• Raw time-series;
• Linear trend lines;
• Moving Averages (e.g. MA(n), with user-selectable n);
• Weighted Moving Averages;
• Moving Average Convergence/Divergence (MACD);

It also helps by providing closing price predictions for companies specified by the user, with regression
models, using the following process (or similar):
1. the user specifies the modelling period (i.e. the training data);
2. They also specify a date for which they require a prediction;
3. A linear model is built, using the specified period;
4. The prediction is produced, along with the model’s RMSE and R2 value (coefficient of determination).

Along with linear regression, it uses polynomial and ARIMA model to train the data and produce results with better accuracy.
