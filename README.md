# Dataset Files for the Paper: *NetMOS: Topology-Aware VoIP MOS Prediction via Attention–Recurrent GNNs*

## Dataset Format

Each sample is stored as an individual PyTorch (`.pt`) file and can be loaded using the `torch.load()` function.


### Input (`x`)

`x` is a dictionary containing network topology information and traffic-related features:

* `link_features`: Tensor containing link features.
* `flow_features`: Tensor containing flow features.
* `flow_to_link`: Dictionary mapping each flow to the list of links traversed by that flow.
* `link_to_flow`: Dictionary mapping each link to the list of flows traversing that link.
* `voip_flows`: Indices of VoIP flows for which Mean Opinion Score (MOS) values are computed.

### Target (`y`)

`y` is a tensor containing the average MOS values measured for the VoIP flows during the network simulation.

---

## Datasets for NSF, GEANT2, and GBN Topologies

### G.729 Codec

* [30 seconds of network activity](https://drive.google.com/file/d/199dUoWBRvaan2qLej2T_p88fRYTzJr-S/view?usp=sharing)
* [120 seconds of network activity](https://drive.google.com/file/d/1UchS-Pl5-tDPuN5bjKT2vbmqb7G2iigV/view?usp=sharing)

### G.723.1 Codec

* [30 seconds of network activity](https://drive.google.com/file/d/1bxuVeM2YqJTuJmPzwpOzZ14TCjjkon6T/view?usp=sharing)
* [120 seconds of network activity](https://drive.google.com/file/d/1Krabkt0JO1scBseVjm3RbOSwxamiDOUE/view?usp=sharing)

### G.711 Codec

* [30 seconds of network activity](https://drive.google.com/file/d/12a8tOMf5OPKJTLdv6YuQDng9r-N5vJ2f/view?usp=sharing)
* [120 seconds of network activity](https://drive.google.com/file/d/1VjQ9hEG3HL3F7oSv0hwUVA6_m-ZOwcxH/view?usp=sharing)

---

## Datasets for Large-Scale Topologies

### G.729 Codec

* [120 seconds of network activity](https://drive.google.com/file/d/1zSYspHnuycnGB5ECzyxCXwQON6InnB8r/view?usp=sharing)

### G.723.1 Codec

* [120 seconds of network activity](https://drive.google.com/file/d/1guhSnr7nPOQsk4CIbQfijA-oMj_5J9GY/view?usp=sharing)

### G.711 Codec

* [120 seconds of network activity](https://drive.google.com/file/d/1T7_02KvKAnt-6hlTNi_jpSXQQOAQt5Vr/view?usp=sharing)
