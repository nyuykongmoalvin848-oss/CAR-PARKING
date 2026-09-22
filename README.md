# Car Park

A system for managing vehicle parking in a multi-level parking facility.

## Overview

The car park tracks available spaces across multiple floors, handles entry and exit for vehicles, calculates parking fees based on time and vehicle type, and provides real-time availability through an API.

## Features

- **Space management** — reserve, occupy, and release parking spaces by floor and section
- **Vehicle tracking** — log entry and exit times for each vehicle
- **Pricing** — configurable rates by vehicle type and duration
- **Availability** — real-time count of free spaces per floor
- **Tickets** — issue and validate entry/exit tickets
- **Reporting** — daily revenue, occupancy rates, and turnover

## Exit Procedure

1. Enter the ticket at the exit terminal.
2. The system validates the ticket and computes the total fee.
3. Payment is collected and the barrier opens.
4. The space is marked available again.
