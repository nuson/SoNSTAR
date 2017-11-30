# nuson-SoNSTAR &mdash; Sonification of Networks for SiTuational AwaReness

Maintaining situational awareness of what is happening within a computer network is
challenging, not least because the behaviour happens within computers and communications
networks, but also because data traffic speeds and volumes are beyond human ability to
process. Visualisation techniques are widely used to present information about the
dynamics of network traffic dynamics. Although they provide operators with an overall
view and specific information about particular traffic or attacks on the network, they
often still fail to represent the events in an understandable way. Also, visualisations
require visual attention and so are not well suited to continuous monitoring scenarios
in which network administrators must carry out other tasks. Situational awareness is
critical and essential for decision-making in the domain of computer network monitoring
where it is vital to be able to identify and recognize network environment behaviours.

Here we present SoNSTAR (Sonification of Networks for SiTuational AwaReness), a
real-time sonification system to be used in the monitoring of computer networks to
support the situational awareness of network administrators. SoNSTAR provides an
auditory representation of all the TCP/IP protocol traffic within a network based on the
different traffic flows between between network hosts. SoNSTAR narrows the gap between
network administrators and the cyber environment so they can more quickly recognise and
learn about the way the traffic flows within their network behave and change. SoNSTAR
raises situational awareness levels for computer network defence by allowing operators
to achieve better understanding and performance while imposing less workload compared to
visual techniques. SoNSTAR identifyies the features of network traffic flows by
inspecting the status flags of TCP/IP packet headers. Different combinations of these
features define particular traffic events and these these events are mapped to recorded
sounds to generate a soundscape that represents the real-time status of the network
traffic environment. Listening to the sequence, timing, and loudness of the different
sounds within the soundscape allows the network administrator to monitor the network and
recognise anomalous behaviour quickly and without having to continuously look at a
computer screen.

## Contents of the repository
```
. [root]
├── [  67]  README.md
├── [ 340]  docs
│   ├── [ 888]  README.md
│   ├── [ 44K]  S1_Appendix.pdf
│   ├── [110K]  S2_Appendix.pdf
│   ├── [ 14K]  S3_Appendix.txt
│   ├── [186K]  S4_Appendix.txt
│   ├── [ 36K]  S5_Appendix.pdf
│   └── [  25]  _config.yml
├── [ 340]  examples - sonifications of the network
│   ├── [ 10M]  S1-Audio.aif
│   ├── [ 17M]  S2-Audio.aif
│   ├── [ 17M]  S3-Audio.aif
│   ├── [ 15M]  S4-Audio.aif
│   ├── [ 14M]  S5-Audio.aif
│   ├── [ 14M]  S6-Audio.aif
│   ├── [ 22M]  S7-Audio.aif
│   └── [ 21M]  S8-Audio.aif
└── [  68]  src - Python and Max/MSP source for SoNSTAR
```

| Audio File | Description |
| ------------- | --------------- |
| [`examples/S1-Audio.aif`](examples/S1-Audio.aif) | **Normal traffic behaviour:**  SoNSTAR normal events sounds.|
| [`examples/S2-Audio.aif`](examples/S2-Audio.aif) | **FIN behaviour:**  SoNSTAR FIN scan audio file. The scan was performed using `hping3`. |
| [`examples/S3-Audio.aif`](examples/S3-Audio.aif) | **Xmas behaviour:**  SoNSTAR heavy Xmas scan audio file. The scan was performed using `Nmap`. |
| [`examples/S4-Audio.aif`](examples/S4-Audio.aif)| **NULL behaviour:**  SoNSTAR low NULL scan audio file. The scan was performed using `hping3`.|
| [`examples/S5-Audio.aif`](examples/S5-Audio.aif) | **NULL behaviour:**  SoNSTAR heavy NULL scan audio file. The scan was performed using `hping3`. |
| [`examples/S6-Audio.aif`](examples/S6-Audio.aif) | **SYN behaviour:**  SoNSTAR heavy full connection SYN scan audio file. The scan was performed using `Nmap`. |
| [`examples/S7-Audio.aif`](examples/S7-Audio.aif) | **Ping behaviour:**  SoNSTAR SYN-Flood-DoS audio file. Sounds of SYN flood attack behaviour for denial of service; performed using `hping3`. |
| [`examples/S8-Audio.aif`](examples/S8-Audio.aif) | **Ping behaviour:**  SoNSTAR Null-DDoS audio file. DDoS (distributed denial of service) using null packet types; performed using `hping3`. |

## Installing SoNSTAR
Instructions for how to install it go here. List any dependencies that need to be installed first.

## Running SoNSTAR
Instructions on how to get it going.

## Authors  
* [**Mohamed Debashi**](https://)
* [**Paul Vickers**](https://paulvickers.github.io)