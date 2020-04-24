# NET-emulator
Network EmulaTor (NET) : emulating arbitrary sync/async network like client-server, p2p, blockchain, et al.

## How to Use
TBA

## Spec.
- minimal time unit: 1 µs
- minimal data unit: packet (in a network layer)
- treating async as sync network through node/edge state snapshot per time-unit
- considering distribution
    - connection between nodes
    - latency
    - packet loss
    - packet forgery/falsification
- supporting multi-threading
- saving setting, snapshot, history, log for replaying
- visualization
    - network structure
    - node connection/data-flow heatmap
    - data share graph

# TODO
- overhead of network initialization: 3-way-handshakes
- (Pareto) distribution of maximum throughput of devices
- multiple network layers: app, transport, network, link, HW, et al. (OSI)
- routing and linking
- presets of various devices/protocols
- GUI (far future work)

# Contact
:email: lukepark327@gmail.com
