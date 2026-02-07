# Wi-Fi goes long range on new WiLo approach

**Author:** Michelle Hampson
**Date:** October 10, 2024
**Source:** https://www.indiehackers.com/post/4CnaRJvIIuLQhf1QLNMj

---

Researchers have created a hybrid wireless technology combining Wi-Fi with LoRa (Long Range) networking protocol, called WiLo. The approach aims to extend Wi-Fi's range while maintaining low power consumption typical of LoRa systems.

The technology targets Internet of Things applications in smart cities and agricultural sensor networks. According to Demin Gao from Nanjing Forestry University, "This reduces costs, complexity, and potential points of failure, making IoT deployments more efficient and scalable."

The hybrid system works by manipulating Wi-Fi's OFDM data transmission to emulate LoRa's chirp-spreading signals. This allows standard Wi-Fi devices to communicate across long distances without additional hardware. Testing covered both indoor (lab, hallway) and outdoor environments up to 500 meters, achieving a 96 percent successful transmission rate.

The research team included members from universities across Hong Kong, China, South Korea, the United States, and the United Kingdom, plus Intel employees in Germany. They used Semtech's SX1280 LoRa transceiver for experiments.

Future development priorities include improving energy efficiency, increasing data rates, enhancing interference resistance, ensuring industry standard compliance, and integrating security measures.

## Key Lessons

- Existing hardware can be leveraged without additional infrastructure
- Cost-effective IoT deployment is achievable through software-based solutions

**Tech Stack:** SX1280 LoRa transceiver (Semtech), OFDM, CSS (chirp-spreading), 2.4 GHz band
