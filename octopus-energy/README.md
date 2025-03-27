# Octopus Energy

## Description
Visualize your Octopus Energy consumption data and track their tariff prices.

## Setup
Connecting to Octopus Energy requires the following information to be supplied when configuring the data source.

Head to your [developer dashboard](https://octopus.energy/dashboard/developer/) to get the following:

 * API Key
 * Electricity Meter MPAN
 * Electricity Meter Serial Number
 * Gas Meter MPRN
 * Gas Meter Serial Number

## Graph Import
This plugin will create graph objects for your electricity and gas meters, along with each of the current Octopus energy products.

## Data Streams
 * Consumption - returns the usage for your energy meters.
 * Electricity Standard Rates - returns the prices over time for the electricity products.
 * Gas Standard Rates - returns the prices over time for the gas products.
 