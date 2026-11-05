# event-dispatch

A Node program that tells another system about an event.

That system is sometimes down. Sending the notice again can apply it twice, and that is also wrong. The goal is to deliver the notice and apply it once. A stand-in for the other system is in this folder, so the project runs without anything else.
