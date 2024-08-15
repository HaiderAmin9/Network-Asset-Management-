# Network-Asset-Management-

## **Overview**
This report documents an inventory of devices connected to a home network, focusing on their characteristics, network access, and the sensitivity of the data they handle. Understanding these devices is crucial for protecting sensitive information and maintaining network integrity. This report is a part of my google cybersecurity certificate 

## **Asset Inventory Details**

### **1. Network Router**
- **Network Access:** Continuous
- **Owner:** Internet Service Provider (ISP)
- **Location:** On-premises
- **Notes:**
  - The router supports both 2.4 GHz and 5 GHz connections.
  - All networked devices in the home connect through this router, making it a critical point for network security.
- **Sensitivity:** Confidential
  - **Reasoning:** The router controls access to the entire network. If compromised, it could expose all connected devices and their data.

### **2. Desktop**
- **Network Access:** Occasional
- **Owner:** Homeowner
- **Location:** On-premises
- **Notes:**
  - The desktop contains private and sensitive information, including personal photos.
  - It is used primarily for personal tasks and occasionally for business-related activities.
- **Sensitivity:** Restricted
  - **Reasoning:** The desktop holds personal data that must be kept secure. Unauthorized access could lead to privacy breaches.

### **3. Guest Smartphone**
- **Network Access:** Occasional
- **Owner:** Friend
- **Location:** On and Off-premises
- **Notes:**
  - The smartphone connects to the home network sporadically, typically during visits.
  - It does not store any critical data related to the network owner.
- **Sensitivity:** Internal-only
  - **Reasoning:** While the smartphone connects to the network, it does not hold sensitive information. However, it could still pose a risk if compromised, especially if it connects to the network frequently.

## **Sensitivity Classification Summary**

- **Confidential:** The network router is classified as confidential due to its critical role in managing all network traffic and maintaining overall network security.
- **Restricted:** The desktop contains sensitive personal information, requiring restricted access to prevent unauthorized disclosure.
- **Internal-only:** The guest smartphone is classified as internal-only, acknowledging its potential to connect to the network but recognizing the limited sensitivity of the data it holds.

## **Conclusion**
This inventory of network-connected devices has highlighted the varying levels of sensitivity and the need for appropriate security measures. The classification of these devices helps in prioritizing security efforts, ensuring that the most sensitive assets are protected from potential threats. Maintaining an up-to-date inventory and reviewing the sensitivity levels regularly is recommended to adapt to any changes in network configuration or usage.
