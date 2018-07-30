# Setup
Setup based on which kind of probes are you going to use. If you don't understand, please read [Concepts and Designs](../concepts-and-designs/README.md) first.

## Language agents in Service 
  - Install agents
    - [Java agent](service-agent/java-agent/README.md). Introduce how to install java agent to your application, without change any codes.
    - [.NET Core agent](https://github.com/OpenSkywalking/skywalking-netcore). See .NET Core agent project document for more details.
    - [Node.js agent](https://github.com/OpenSkywalking/skywalking-nodejs). See Node.js server side agent project document for more details.
  - [Setup backend](service-agent/backend-setup.md). Set the backend for language agents scenario.
  
## On Service Mesh
  - Istio
    - [SkyWalking on Istio](istio/README.md). Introduce how to use Istio Mixer SkyWalking Adapter to work with SkyWalking.