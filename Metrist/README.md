# Metrist

## Description
Metrist is a neat synthetic monitoring tool that can give you quick access to status / SLA data for common web apps and cloud hosting services.
Better than simple ping checks in that it carries out pretty detailed programmatic checks i.e. it does the stuff you'd do yourself.
It can then show you the Metrist view of status versus the reported status from the service vendor.

## Setup
Grab an API key from https://metrist.io/contact

## Graph Import
Metrist monitors, categorised using the same classifications you'd see in the Metrist app.
Note this is currently a static definition, subject to manual updates, pending an API endpoint that can provide this data dynamically.

## Data Streams
 * Health - currently the only method available via their API. Is the monitor healthy or not.
 