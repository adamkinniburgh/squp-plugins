# Geodata

## Description
This is a pretty simple plugin that creates graph objects representing places and currencies.

Each of the geographical nodes contains a `latitude` and `longitude` property to denote where it is.
Other plugins may choose to provide Data Streams that can surface geographical data using these properties.
OpenWeatherMap is a good example, scoping to say `London, UK` from this plugin lets you get weather stats.

Locations and currencies are also decorated with their standard ISO codes which may prove useful to other plugins too.
A plugin providing Foreign Exchange rates, for example, could be scoped to the currency objects from this plugin.

## Setup
Nothing special, just pick which types of objects you want to import

## Graph Import
 * AWS and Azure cloud regions
 * Countries
 * Capital Cities
 * US State Capital Cities
 * Currencies

## Data Streams
None
