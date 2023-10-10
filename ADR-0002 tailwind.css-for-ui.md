# Use Tailwind for styling UI elements

* Status: proposed
* Deciders: James
* Date: 2023-10-10
---
## Context and Problem Statement

How can we style our application so that it provides a consistent cross-platform experience?

We need a UI that looks good on both iOS and Android devices, so that all users share the same experience while using our app.

## Decision Drivers 

* needs to be customizable
* cross-platform accessibility 
* easy to navigate


## Considered Options

* React Native
* Tailwind
* Material

## Decision Outcome

Chosen option: "Tailwind"

Tailwind was chosen as the UI system to mesh with the teams html and css background. 

### Positive Consequences 

* integrates well with JavaScript systems
* relies on past work with html and css so low learning curve
* can be highly customized

### Negative Consequences 

* can take longer to develop if custom css components are built
* can result in html bloat due to class names
  