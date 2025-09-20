# BETA RELEASE: Air Traffic Control System

# Air Traffic & Air Defense System — **Beta Release Notes**

## Highlights

* First beta of a comprehensive **ATC & Air Defense** framework.
* Designed to evolve into a full **airport suite** (flight tracking, flight plans, and more).

## What’s in this beta

* **Controller UI:** Custom interface for qualified staff to track aircraft and communicate with pilots.
* **Auto Radio Management:** Players are automatically placed on a standalone radio channel when they enter an aircraft and automatically removed when they exit.
* **Access Control Export:** Supports restricted radio channels via the `isAllowedChannel` export to verify a player’s eligibility.

## Integration notes

* If your radio/walkie system supports **restricted channels**, use `isAllowedChannel` to gate access:

  * Returns whether a player is allowed on ATC channels (and which one, when applicable).

## Roadmap

* Expand to a full **airport operations** system:

  * Persistent flight tracking
  * Flight plans & procedures
  * Additional controller tools and metrics

> Feedback is welcome, this beta will evolve quickly based on real-world server use.
