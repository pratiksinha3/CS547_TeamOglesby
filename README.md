# CS547 Deep Dive Project - Gasoline Price Prediction

### Team Name
Oglesby

### Team Members
- Pallav Ranjan
- Dimitrios Bralios
- Pratik Sinha
- Siva Kumar Valluri

### Problem Statement
Due to the recent economic and supply-chain turmoil gasoline prices across the world have been on the rise. This has impacted the price of every commodity, and contributed to inflation which in turn feeds back to further impact gas prices. Thus, the ability to predict future gasoline prices would be crucial to prepare and device measures to ameliorate the situation. We have identified that gasoline prices are primarily driven by classical economic theory of supply and demand. The supply of gasoline to the US is primarily from domestic crude oil wells and imports from other nations. The US also maintains a strategic petroleum reserve to handle the disruptions in the crude oil supply chain. Demand of gasoline is primarily reflected by domestic consumption. Other than these, inflation limits the purchasing power thus affecting both production/import and consumtion of gasoline. It is usually measured as Consumer Price Index (CPI) by the Federal Bank of the US. Further, changes in taxation at federal and state level will also impact the prices, however it remains constant over a long duration. Finally, we will also use historical trends in gasoline prices to capture any missing features. To summarize, we are building a Recurrent Neural Network (RNN) to predict the weekly gasoline price based on the following features:
- Weekly crude oil import (Supply)
- Strategic Petroleum Reserve (Supply)
- Domestic Production (Supply)
- Domestic Consumption of Gas (Demand) 
- Domestic Inflation as CPI
- Historical Price of Gasoline


### License
Copyright 2022 University of Illinois Team Oglesby

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
