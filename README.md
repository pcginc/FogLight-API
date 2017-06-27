# FogLight-API
API examples of oeFogLight features
## What It Is ##
FogLight is a Java 8 functional API for embedded systems that's built on top of [GreenLightning](https://github.com/oci-pronghorn/GreenLightning), a small footprint, garbage free compact 1 Java web server and message routing platform, 

FogLight is...
- Fast - Built on top of GreenLightning, FogLight is a garbage-free, lock-free and low latency way to talk directly to hardware.
- Simple - Taking advantage of the latest Java 8 APIs, FogLight has a clean and fluent set of APIs that make it easy to learn and apply with minimal training.
- Secure - By taking advantage of the compile-time graph validation system, all FogLight applications can be compiled and compressed to a point where injecting malicious code into the final production JAR would prove difficult, if not impossible.

## How It Works ##
Every FogLight application starts with an `FogApp` implementation which initializes the `FogRuntime` by defining various hardware connections and behaviors for handling state changes in those connections.  

## What You Need Befor You Start:
### Hardware
- [Raspberry Pi](https://www.raspberrypi.org/)
- [GrovePi+ Board](https://www.dexterindustries.com/shop/grovepi-board/)
### Software
- [Java 8](https://docs.oracle.com/javase/8/docs/technotes/guides/install/install_overview.html)
- [Maven](https://maven.apache.org/install.html)
- [Git](https://git-scm.com/)
## Starting Your Maven Project
[Starting a mvn project](https://github.com/oci-pronghorn/FogLighter/blob/master/README.md)
## Information and Demos 
- CommandChannel
  - demo - Coming Soon!
- CustomDevice
  - demo - Coming Soon!
- HTTPClient
  - demo - Coming Soon!
- HTTPServer
  - demo - Coming Soon!
- PubSub
  - [demo](https://github.com/oci-pronghorn/FogLight-API/blob/master/PubSub/PubSub.md)
- PubSubStructured
  - demo - Coming Soon!
- Shutdown
  - demo - Coming Soon!
- Startup
  - [demo](https://github.com/oci-pronghorn/FogLight-API/blob/master/Startup/Startup.md)
- StateMachine
  - [demo](https://github.com/oci-pronghorn/FogLight-API/blob/master/StateMachine/StateMachine.md)
- Timer
  - [demo](https://github.com/oci-pronghorn/FogLight-API/blob/master/Timer/Timer.md)
