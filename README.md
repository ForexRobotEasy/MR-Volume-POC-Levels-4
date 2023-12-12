# MR Volume POC Levels 4 - ReadMe File

This ReadMe file provides information about the code for the MR Volume POC Levels 4 indicator, developed by the Forex Robot Easy Team. 

## Indicator Inputs
The indicator has the following input parameters:
- `period`: The period for POC (Point of Control) calculation
- `dynamicPOCPoints`: The number of Dynamic POC Points to display

## Global Variables
The indicator uses the following global variables:
- `POCLevels[]`: An array to store the calculated POC levels
- `dynamicPOCPointsArray[]`: An array to store the POC values for Dynamic POC Points

## Custom Indicator Initialization
The `OnInit()` function is called during indicator initialization. It sets the index style and buffer for the POC levels and sets the indicator's short name.

## Custom Indicator Calculation
The `OnCalculate()` function is called for each bar to calculate the POC levels. It loops through the bars and calls the `CalculatePOC()` function to calculate the POC for each bar. The POC values are stored in the `POCLevels[]` array. The POC values for the Dynamic POC Points are stored in the `dynamicPOCPointsArray[]` array.

## CalculatePOC() Function
The `CalculatePOC()` function is responsible for calculating the POC levels based on a proprietary methodology. The function takes two parameters: the bar index and the period. It should be customized to calculate the POC levels based on the specific methodology of the indicator and return the POC value for the specified bar.

## Product Description
**MR Volume POC Levels 4** is an indicator developed by the Forex Robot Easy Team. It is designed to calculate and display the Point of Control (POC) levels on the chart. POC represents the price level at which the highest volume of trades occurred. This indicator helps traders identify key support and resistance levels based on volume analysis.

The indicator allows users to customize the period for POC calculation and also provides the option to display a specified number of Dynamic POC Points on the chart. These Dynamic POC Points represent recent POC values and can be used as additional reference levels.

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/mr-volume-poc-levels-4-review-master-your-forex-trades/).

