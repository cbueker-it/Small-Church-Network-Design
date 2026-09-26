**Small-Church-Network-Design**

Conceptual church network design covering VLAN segmentation, managed switching, PoE, wireless access, firewall policy, and scalable infrastructure planning.

This project explores how I would design a structured network for a growing church environment. The design accounts for staff and administrative systems, pastoral and leadership devices, AV and production equipment, security systems, wireless access, and guest internet access.

The goal is to move beyond a basic flat network and create an environment that is easier to secure, troubleshoot, document, and expand. The design uses managed switching, VLAN segmentation, 802.1Q trunks, PoE infrastructure, multiple wireless SSIDs, and firewall policy to separate different types of network traffic.

The project also focuses on implementation and long-term operation. An organization's network should be designed around current requirements. Additionally, the network design ought to show a clear path for additional users, devices, access points, security systems, and other technology as the organization grows.

**Operational Value**

A church network may support many different types of systems that do not need the same level of access. Staff workstations, leadership devices, AV equipment, security cameras, printers, building systems, and guest devices can all have different operational and security requirements.

Segmenting those systems provides better control over how traffic moves through the network. It also creates a cleaner environment for troubleshooting, security policy, documentation, and future expansion.

The purpose is not to add unnecessary complexity. The purpose is to create infrastructure that is reliable, secure, understandable, and able to grow with the organization.

**Objectives**

- Design a physical and logical network topology for a growing church environment.
- Use VLANs, subnets, access ports, and 802.1Q trunks to separate major network functions.
- Incorporate managed switching, PoE infrastructure, and multiple wireless SSIDs into the design.
- Define firewall and inter-VLAN routing concepts that control access between internal networks and guest traffic.
- Develop an implementation and growth model that includes validation, documentation, monitoring, maintenance, and future expansion.

**Growing Church Network Design**

This topology shows a conceptual church network divided into five VLANs for staff and administration, pastoral and leadership, AV and production, security and building systems, and guest Wi-Fi. Each segment has its own subnet and security purpose, while shared managed switching and 802.1Q trunks carry traffic between the network devices.

The router/firewall provides the default gateways and controls inter-VLAN access. Internal VLANs can reach only the resources they are authorized to use, while the guest Wi-Fi VLAN is allowed Internet access but is isolated from the internal church networks.

![Growing Church Network Design](images/01-network-topology.png)

**Growing Church Network Implementation and Growth Roadmap**

This roadmap shows how I would approach implementing and growing the network in stages. The process begins with assessing the existing environment and documenting users, devices, and operational needs before introducing managed switching, VLAN segmentation, wireless access, and firewall policy.

The final stage focuses on operating the network over time through validation, documentation, monitoring, maintenance, and controlled expansion as the church adds more users, devices, access points, security systems, or other technology.

![Growing Church Network Implementation and Growth Roadmap](images/02-growth-roadmap.png)

**Lessons Learned**

- Network design should begin with understanding the users, devices, traffic types, and operational requirements before selecting equipment or changing configurations.
- VLANs and subnets provide logical separation while allowing multiple groups to share the same managed switching infrastructure.
- Access ports, 802.1Q trunks, default gateways, and inter-VLAN routing each have different roles in determining how traffic moves through the network.
- Wireless SSIDs can map users into different VLANs, allowing staff, leadership, and guest wireless traffic to follow different security policies.
- Network design continues after installation through validation, monitoring, documentation, maintenance, and controlled expansion.

**Summary**

In this project, I designed a conceptual physical and logical network for a growing church environment.

The design uses managed switching, VLAN segmentation, 802.1Q trunks, PoE infrastructure, multiple wireless SSIDs, subnetting, inter-VLAN routing, and firewall policy to separate staff, leadership, AV and production, security, and guest traffic.

I also developed an implementation and growth roadmap that moves from assessment and planning through segmentation, security, validation, documentation, monitoring, and future expansion.

This project helped me connect individual networking concepts into a complete design and think more deeply about how a network can be implemented, secured, maintained, troubleshot, and expanded over time.

**Navigation**

[`Back to GitHub Profile`](https://www.github.com/cbueker-it)
