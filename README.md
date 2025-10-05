# 🏋️ **GymLink** | Network Infrastructure and Management Application

***

## **Project Summary**

This repository contains the full documentation and implementation details for **GymLink**, a project focused on designing and implementing a robust, segmented **Local Area Network (LAN)** infrastructure for a new gym, coupled with the concept for a **customisable Gym Management Application**.

The primary goal was to create a secure, fast, and reliable network that supports modern fitness facility operations—including internal staff communication, a file server, and segregated customer Wi-Fi access—while applying practical network security measures like **VLAN segmentation** and **Access Control Lists (ACLs)**.

![GymLink Network Topology](https://res.cloudinary.com/df9vvy76v/image/upload/v1759662570/GymLink-Network-Topology/GymLink-Network-Topology_wjzss5.png)

***

## **Key Features & Technologies**

### **Network Implementation (Cisco Packet Tracer Simulation)**
* **Segmented LAN Design:** Implementation of a core/distribution network layer using one router and multiple switches.
* **VLAN Configuration:** Five distinct Virtual Local Area Networks (VLANs) were created to separate traffic for enhanced security and performance:
    * `VLAN 10` (Management)
    * `VLAN 20` (Staff)
    * `VLAN 30` (Customer Service)
    * `VLAN 40` (IT)
    * `VLAN 50` (Guest Wi-Fi)
* **Security Measures:** Configuration of **Router-on-a-Stick** for inter-VLAN routing and rigorous implementation of **Standard and Extended ACLs** to control traffic flow and isolate the Guest VLAN (`VLAN 50`) from the internal network.
* **Firewall Simulation:** Extended ACLs were configured on the external interface (`GigabitEthernet0/1`) to deny access from unauthorised private IP addresses, simulating a router firewall function against external attacks.
* **IP Addressing:** Utilisation of a private addressing scheme (`192.168.X.0/24`) with DHCP services deployed per VLAN.

### **Management Application Concept**
* **System Goal:** A scalable solution for streamlining administrative tasks (e.g., member management, class scheduling, progress monitoring) to enhance staff productivity and member experience.
* **Development Methodology:** Project development followed the **SCRUM** methodology, prioritising flexibility and iterative progress based on feedback.

***

## **Project as a Business (GymLink)**

This project was extended into a fictitious **Tech Start-up** based in London, UK, named **GymLink**. This section demonstrates the commercial viability and strategic planning for the solution.

### **Business Strategy Highlights**
| Section | Key Outcome |
| :--- | :--- |
| **Legal Classification** | Chosen as a **Limited Company (Ltd)** in the UK for limited liability and investment readiness. |
| **Target Market** | Independent gyms and fitness studios, with potential expansion to larger franchises. |
| **Value Proposition** | Providing a scalable, integrated solution (network + custom software) that optimises operations and improves customer retention. |
| **PEST Analysis** | Evaluated macroeconomic factors including UK **Government Health Initiatives**, **UK GDPR Compliance**, and the impact of rising **Health and Wellness Trends**. |
| **Social Impact** | Aimed at fostering a pervasive culture of health by enabling smaller facilities to compete and providing personalized fitness tools. |

***

## **Project Documentation**

The following sections summarise the technical and conceptual detail, as originally presented in the project report.

### **1. Practical Prototype Development / Implementation**
* Detailed breakdown of network components, VLAN topology, and the **Cisco IOS commands** used to configure ACLs for security (e.g., denying Staff/Customer Service access to Management/IT VLANs, and complete isolation of the Guest VLAN).
* Demonstration of the external network **attacking test** to validate firewall ACL effectiveness.

### **2. My Project as a Business**
* Exploration of business strategy, including **Marketing and Sales**, **Product Development (Scrum)**, and **Funding Initiatives**.

### **3. Project Reflection**
* **Lessons Learned:** Significant development of skills across **Network Design, Software Development Methodologies (SCRUM, V-Model), Project Management (Gantt Charts, Time Management),** and **Technical Communication**.
* **Positive Social Impact (PSI):** Discussion on how the project's efficiencies can promote health outcomes and how acquired skills can be leveraged for future community-focused tech solutions (e.g., a personalised fitness application).

***

## **Project Details**

| Category | Detail |
| :--- | :--- |
| **Module Name** | Changemakers: Creativity and Value Creation (ACCA5033_LON) |
| **Student Name** | Pedro Gaetjens Molongua |
| **Lecturer** | Koushik Modak |

*** 

##  **Original Assessment** 
For whoever interested, I will leave here a direct link to my assessment report made for this project: 
* https://pdf.ac/S-FBM3Em54 
* [**Assessment PDF**](http://pdf.ac/S-FBM3Em54 "**Assessment PDF**")

***

## **Contact**

For any queries about this project or to discuss potential collaboration, please feel free to reach out.

* **Pedro Gaetjens Molongua**
* [LinkedIn](https://linkedin.com/in/pedro-g-a81978214) | [GitHub](https://github.com/PedrxG) 🌱
* *\[pedrogaetjensmolongua@gmail.com]* 📧
