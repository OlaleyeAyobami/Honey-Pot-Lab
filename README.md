
# Honeypot Lab

## Objective

The primary objective of this project is to deploy and configure a honeypot using TPOT. A honeypot serves as an enticing target for attackers, allowing us to detect and analyze unauthorized activity, gather threat intelligence, and potentially distract malicious actors from actual production systems.

## Skills Utilized

- Deployment and configuration of honeypot infrastructure.
- Familiarity with cloud computing services (Vultr in this case).
- Understanding of cybersecurity concepts related to intrusion detection and threat intelligence.
- Analysis of inbound network traffic using tools like Kibana.
- Utilization of open-source intelligence (OSINT) tools such as CyberChef and SpiderFoot.

## Tools and Services Used

- TPOT, an open-source honeypot solution.
- Vultr, a cloud computing provider for deploying the honeypot.
- Kibana for visualization and analysis of inbound access.
- CyberChef for data manipulation and analysis.
- SpiderFoot for open-source intelligence gathering.

## Process Overview

1. **Deployment and Configuration:**
   - Utilize Vultr to deploy the TPOT ISO image onto a virtual machine instance.
   - ![1](https://github.com/OlaleyeAyobami/Honey-Pot-Lab/assets/167548326/e10c65bb-6084-4aa0-900c-cef45d885fff)

   - Access the console provided by Vultr to interact with the deployed honeypot.
   - Perform initial configuration and installation steps for TPOT.
   - ![2](https://github.com/OlaleyeAyobami/Honey-Pot-Lab/assets/167548326/dcd84666-ba98-4fe4-8478-4677850502d5)


2. **Accessing TPOT Homepage:**
   - Upon successful configuration, access the TPOT homepage via HTTPS on port 64217.
   - Authenticate using provided credentials to gain access to the TPOT dashboard.
   - ![3](https://github.com/OlaleyeAyobami/Honey-Pot-Lab/assets/167548326/fcf50819-87d9-4b1a-9fdc-c5ae5909d036)


3. **Utilizing TPOT Features:**
   - Explore features such as AttackMap, Cockpit, CyberChef, and SpiderFoot available on the TPOT dashboard.
   - ![Screenshot 2024-04-26 224318](https://github.com/OlaleyeAyobami/Honey-Pot-Lab/assets/167548326/9f4a5e10-1de8-4ea6-bc92-dde6af7850c9)

   - Focus on AttackMap and Kibana for analyzing inbound access and monitoring suspicious activities.
   - ![Screenshot 2024-04-26 224440](https://github.com/OlaleyeAyobami/Honey-Pot-Lab/assets/167548326/ec543e31-9abf-4d5b-a651-a3eedc3e87ec)


4. **Configuring Firewall Rules:**
   - Configure firewall rules to allow inbound access to the honeypot on both TCP and UDP.
   - Create rules allowing traffic on ports 1 - 65535 from any source IP address.

5. **Monitoring and Analysis:**
   - Monitor inbound traffic using AttackMap and analyze it further using Kibana.
   - Extract relevant information such as source IP addresses, attack vectors, and geographic origins.
   - ![Screenshot 2024-04-26 224452](https://github.com/OlaleyeAyobami/Honey-Pot-Lab/assets/167548326/56ed8ac2-4529-4cfe-bf71-e362c9700dcc)


6. **Data Ingestion and Analysis:**
   - Allow TPOT and Kibana to ingest data collected over time.
   - Utilize Kibana's querying and visualization capabilities to analyze trends and patterns in the collected data.
   - ![Screenshot 2024-04-26 224644](https://github.com/OlaleyeAyobami/Honey-Pot-Lab/assets/167548326/416f9790-53ac-4b8a-84d8-57bc2b5fafd9)


## Conclusion

Through this project, we have gained valuable experience in deploying and configuring a honeypot infrastructure using TPOT. By monitoring inbound traffic and analyzing potential threats, we enhance our understanding of cybersecurity threats and improve our ability to detect and mitigate them effectively.

