## Overview

This library provides the necessary Debezium drivers required for the CDC (Change Data Capture) connector in Ballerina.
It enables listening to changes in MSSQL databases seamlessly within Ballerina projects.

## Compatibility

| |     Version     |
|:---|:---------------:|
|Ballerina Language |  **2201.12.0**   |
|Debezium MSSQL Driver | **3.0.8.Final** |

## Usage

To include the `mssql.cdc.driver` dependency in your project, simply import the module as shown below:

```ballerina
import ballerinax/cdc;
import ballerinax/mssql.cdc.driver as _;
```

The `mssql.cdc.driver` library is bundled with the required drivers, so no additional configuration is needed.
