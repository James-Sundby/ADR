# Push notifications through Firebase

* Status: proposed
* Deciders: James
* Date: 2023-10-10
---
## Context and Problem Statement

How can we communicate information to users including order confirmations, as well as delivery and marketing updates?

Our application will need to provide users with some form of notification to notify them of changing information inside the app.

## Decision Drivers 

* Scalability as app expands
* Security of user information
* Cross-platform features

## Considered Options

* OneSignal
* Firebase
* Leanplum
* Airship

## Decision Outcome

Chosen option: "Firebase"

Firebase was chosen to handle the app notifications due to its free basic tier that can be scaled up depending on the size of the app without too much addition work. 

### Positive Consequences 

* integrates with Google Cloud services
* uses NoSQL for the database

### Negative Consequences 

* limited options on free tier
* relies on existing google architecture



## Links 

* [Push notification systems](https://www.mobiloud.com/blog/best-push-notification-services)
* [Google Firebase](https://firebase.google.com/pricing)