# Develop the app as a hybrid system

* Status: proposed 
* Deciders: James
* Date: 2023-10-08
---
## Context and Problem Statement

What type of application should we use for our food delivery system?

The development team needs to make a decision on what kind of application to develop in order to know what languages and tools are available, as well as what device features the app will have access to.

## Decision Drivers 

* needs to be responsive
* will need to access device features 


## Considered Options

* Native
* Web-based
* Hybrid

## Decision Outcome

Chosen option: "Hybrid"

Hybrid apps provide a consistent experience across different device platforms, and can provide better access to device features compared to completely web based applications. This means the team only needs to develop and maintain a single app, rather than many different device specific apps.

### Positive Consequences 

- cross-platform development
- access to native features

### Negative Consequences

- requires existing frameworks and API's to access device features
- some specific platform constraints 

# Links

* [ADR-0005 accessing-gps-permission](obsidian://open?vault=Notes&file=Software%20Dev%2F23%20-%20Fall%20Sem%202%2FMobile%20App%20Development%2Fadrs%2FADR-0005%20user-reviews)