## Task Pre-study notes

### Preparation

1. Inspiration
   I'm somewhat excited about project work. Don't really have inspirations for particular projects.
2. Journey of a Packet
   The Application-layer that TCP/IP uses is not as easily separated into three distinct layers as OSI Model makes it seem.
   **TCP/IP is not addressed in the mandatory videos, only in the optional ones.**
3. Network Discovery:
   1. Local IP (v4) 192.168.2.*:-)*, Subnet Mask: 255.255.255.0, Router: 192.168.2.1
   2. It takes 6 hops to reach Cloudflare DNS. The transition to public IPs happens almost immediately.
   3. What is my motivation for doing this? This does not follow from any prior step.


### Guiding Questions

1. An interesting IoT-scenario: A refrigeration system for a supermarket. I expect there to be network of refrigerators with temperature sensors either built into the refrigerators or added into the network. And then there's an additional computer who apparently not only reads the sensor data but can also regulate the temperature control on the refrigerators instead of just sending notifications to another device in case of irregularities.
2. An IP-address is a unique identifier for a device inside a network. A subnet mask defines the address-space of the network as opposed to the address of a singular device. Two devices on a local subnet cannot have the same IP-address, since it would create inconsistencies and disruptions inside the network. **nb: Subnet masks have been mentioned, but have not been explained in the videos.**
3. I don't know. I know nothing about real-world IoT-systems. Is this supposed to be about packet size? Headers are big and sensor data isn't? 
4. There has been no information given about MQTT, the pub/sub process or how this relates to http. **Is this supposed to be common knowledge?**
5. I cannot ping their device directly, no. **In regards to mesh overlay networks: I have no idea what you're talking about.**

## Task Datasheet reading

## Task Simulation

## Task Project abstract
