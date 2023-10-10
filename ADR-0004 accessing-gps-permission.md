# Get GPS permission

* Status: proposed
* Deciders: James
* Date: 2023-10-10
---
## Context and Problem Statement

What hardware services and device permissions will our food delivery app need to access in order to meet our customers needs?

Our app needs to be able to find restaurants near to the device, as well as provide a way to indicate the estimated delivery time from the restaurant.

## Decision Drivers 

* location-based deals
* estimation of the distance from the restaurant
* information accuracy

## Considered Options

* User-entered location
* GPS from phone

## Decision Outcome

Chosen option: "GPS from phone"

Getting the location data from the phone will provide user's with the smoothest experience, as the data will be pulled in the background while the app is running rather than requiring the user to stop and enter the location manually

### Positive Consequences 

* snappy user experience

### Negative Consequences 

* user privacy
* increased load on device battery
