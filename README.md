# [Waggle](https://waggle.eth.link)

A spam-free, privacy-preserving and encrypted communication protocol on top of [Swarm](https://www.ethswarm.org/).

## The Name

[Waggle dance](https://en.wikipedia.org/wiki/Waggle_dance) is a term used for a dance made by the honey bee to share information about the direction and distance of foraging sites and colony nest locations with other members of the colony.
Similarly, this project aims to provide a way for senders to share the locations of where the recipients can download their messages.

## About

This project is inspired by the idea of a mail-transfer protocol proposed by Daniel J. Bernstein at the end of the 20th century named [IM2000](https://cr.yp.to/im2000.html), in which the sender and not the recipient is responsible to store the email messages. A recipient must deliberately request messages from senders he has pre-approved, thus making spamming effectively impossible.

In our design, recipients subscribe to receive messages by agreeing on a outbox of the sender. We are currently implementing the Waggle protocol in Swarm using its unique features Feeds and PSS.

## Timeline

Waggle is currently under active development and the prototype was presented in the Swarm One mainnet release event.

We expect to release Waggle in 2021. Please follow us to receive updates about the project.

## Protocol Overview

### Notifications

![notification][notification_simple]

[notification_simple]: diagrams/notification_simple.png "Notification"

### Message Exchange

![message][message_simple]

[message_simple]: diagrams/message_simple.png "Message"
