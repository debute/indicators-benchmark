# JavaScript trading indicators benchmark
## Latest Report

|    Indicator    	|  @debut/indicators (ops/sec)  	| technicalindicators (ops/sec) 	| trading-signals (ops/sec) 	|  ta.js (ops/sec)  	|
|:---------------:	|:---------------------------------:|:---------------------------------:|:-----------------------------:|:-----------------:	|
| AwesomeOscillator |            335,315            	|             24,547             	|             732             	|         x         	|
|       ATR       	|            954,257            	|             141,003             	|            2.56             	|         x         	|
| Bollinger Bands 	|             392,649            	|              10,813            	|             62.93            	|         x         	|
|       CCI       	|             235,552            	|              9,268              	|             x             	|         x         	|
|       EMA       	|            2,451,966            	|             322,287            	|            4.90           	|      740,489      	|
|       MACD      	|            1,146,681            	|             48,323             	|             2.10             	|         x         	|
|       ROC       	|            2,256,411            	|             49,253             	|            617             	|         x         	|
|       RSI       	|            1,207,454            	|             21,272             	|            148             	|         x         	|
|       SMA       	|            2,034,006            	|             45,479             	|            1,506            	|       1,670       	|
|    Stochastic   	|             189,514            	|             20,914             	|             197             	|         x    	        |
|      WEMA     	|             937,491            	|            296,787             	|             x             	|         x    	        |
|       WMA     	|             97,807            	|            22,617             	|             x             	|         x    	        |
|      PSAR     	|             1,084,123            	|            166,158             	|             x             	|         x    	        |
|       ADX      	|              356,637             	|              26,581           	|             x             	|         x


## Contribute guide

### Step 1: Add you library to `suter.js` sources object
### Step 2: Add you library to `suret.js` columns list
### Step 3: Implement benchmark sutes for library indicator

## Report generation

Run command `npm run bench` to generate new report.

Then copy report to main file `ReadMe.md`
