# CroupierPy: A Python Data Socket Bridge
**Technologies:** Python, Sockets

Croupier.apk (One-Check Mode) https://www.youtube.com/watch?v=REShrnKKy_s

Croupier.apk (Two-Check Mode) https://www.youtube.com/watch?v=32vL1JOkKmM

### Overview

CroupierPy is a companion project to the `Croupier` Android framework. It consists of a simple Python server that demonstrates cross-platform data communication.

The primary purpose of this bridge is to:
* Listen for incoming data connections (via Sockets) from the Android application.
* Receive real-time data packets (e.g., JSON payloads) streamed from the device.
* Print the received data to the console, simulating a desktop application, a data logger, or a remote analysis endpoint.

### Use Case

This server acts as a proof-of-concept, showing how an on-device mobile app (like `Croupier`) can stream its processed data to another machine or application for further processing, logging, or visualization.
