헬륨 핫스팟 md 신청서입니다. 내용들은 Guardian 기준으로 작성되었고  Image link 는 교체해야합니다.

## COMPANY NAME
### Guardian ENG 
//<img src="https://github.com/hyeonsfather/hotspot-manufacturers/blob/main/img/plnetworks_logo.png">   

## Summary
Guardian E&G Co., Ltd. is a specialized IT convergence company combining electric / electronic and wireless communication technologies. Based on LoRa module, we create LoRa Device, LoRa Gateway and LoRaWAN Network Server.  


## Company Information (required)
* What is your company name?   
**Guardian E&G Co., Ltd. (Guardian Electronic and Global)** 
* How long has the company been in business?    
**founded on March 4, 2014 and has been operating for 8 years to date.**
* What kind of products have you created? (list specific products)

    1.	**remote control and failure monitoring system** for the street-light and security-light 
	<img src="https://github.com/hyeonsfather/hotspot-manufacturers/blob/main/img/plnetworks_plm100s.png" width="30%">

    2.	**water meter reading system**
	<img src="https://github.com/hyeonsfather/hotspot-manufacturers/blob/main/img/plnetworks_plm100s.png" width="30%">

    3.	**Environmental information notification system** for fine dust measurement, temperature and humidity, wind speed, current time
	<img src="https://github.com/hyeonsfather/hotspot-manufacturers/blob/main/img/plnetworks_plm100s.png" width="30%">

    4.	**Electric vehicle charger**
	<img src="https://github.com/hyeonsfather/hotspot-manufacturers/blob/main/img/plnetworks_plm100s.png" width="30%">

    5.	**Smart pole for traffic and general public safety** 
	<img src="https://github.com/hyeonsfather/hotspot-manufacturers/blob/main/img/plnetworks_plm100s.png" width="30%">

* How many have you sold?    
   **More than 50,000 units of the above products have been sold to Korea central government and municipal local governments.**
 
* What brought you to the Helium Network?    
	From starting LoRa RF transceiver without LoRaWAN standard, we thought that this kind of RF feature is innovative and another part of RF solutions which is not existed in the world so that traditional building a network is not suitable to LoRa network construction and the business way of Helium network is innovative like LoRa RF transceiver. 

## Product Information (required)
* What is this product's model name?     
	**GDLR_S100**
* Is this is a Light Hotspot or a 5G Hotspot? (Due to the time required for the HIP19 process, new applications should be for Light Hotspots or 5G Hotspots)    
	**Light Hotspot**
* Is this model for indoor, outdoor, or both? (If there are two different models for indoor and outdoor, list them separately)    
	**Indoor**
* Provide a brief description of the product:

  **GDLR_S100 Brief Specification**
  |Title                  | Description                                                                        |
  |--------------------|-----------------------------------------------------------------------------|
  |CPU| Broadcom BCM2711C0 quad-core ARM Cortex-A72|
  |RAM| 533Mhz 64MB DDR2|
  |Flash| 8GB EMMC|
  |LoRa Interface| SX1303 (RAK 5146)<br>LoRaWAN, KR920/AS923/US915<br>Frequency: 902~928MHz<br>TxPower: 23dBm<br>DataRate: 0.3kbps ~ 20kbps(upto SF5)|
  |Networking| 10/100/1000B-Tx 1 Port for LAN/WAN(802.3 AT PoE)<br>USB Type LTE Modem|
  |GPS| GPS L1:1575.42±1.023MHz, BeiDou B1:1561.098±2.046MHz, GLONASS L1:1597.78~1605.66MHz|
  |Operation Voltage| DC 12V to 24V input with POE Power (DC 37-57V) or DC power jack|

* What is your approximate price point?    
	**about USD 400~500 range per item**  
* What is your expected production and delivery timeline?     
	**o	Q4. 2022. HIP19 application**
	**o	Q2. 2023. Pre-order sales** 
	**o	Q3. 2023. 1st order production and delivery**

## Previous shipments (required)
* Have you shipped anything in the past?    
   **Korea and Vietnam**

* What types of products have you shipped?    
	**LED Street Light controller (GDS-100T)**
	<img src="https://github.com/hyeonsfather/hotspot-manufacturers/blob/main/img/plnetworks_plm100s.png" width="30%">

* Which countries have you previously shipped regulatory approved products? (FCC, CE, etc.)     
	**LED Street Light Controller - Korea - KC**
	**LED Street Light Controller - Korea - CE**    
	<img src="https://github.com/hyeonsfather/hotspot-manufacturers/blob/main/img/plnetworks_plm100s.png" width="30%">

## Which countries do you plan to ship to and get regulatory certifications for? (required) 
Please list specific countries, "worldwide" or "global" are not acceptable.    
  **Our plan is to start with South Korea and expand to USA, Singapore, Malaysia, India, Turkey, Dubai, Jordan, Algerie and so on.** 
  **We will obtain necessary certification KC, FCC, SIRIM, BIS and so on**

## Customer Support (required)
* How will your customers be able to contact you for support for your products?     
	**homepage: www.gdnet.co.kr** 
	**E-mail : support@gdnet.co.kr / service@gdnet.co.kr** 
	**Inquiry :+82 31-344-0177 (line 1 : Sales Inquiries / line 2 : product or support Inquiries)**

* How long will the company provide customer support?     
	**official warranty is 1 year and extend warranty possible for 2 years (total 3 years) with SLA contract**
* How are you planning to handle repairs and replacements?     
	**We will manufacture 5% additional stocks available for exchange**
	**We will work with regional telecom equipment partners in the target countries for local tech support and repair**

## Hardware Security Element (required)
* The community is concerned about devices that can be easily hacked, specifically by copying their swarm_key files. Applications should include plan for how the devices will be secured. The approved security element is an ECC608. If you would like to use an alternative security element your HIP19 will require additional review, please email the Helium Foundation (christina@helium.foundation).
* Are you using an ECC608. Yes or No?    
	**Yes. Built-in ECC608 crypto chip will be applied on GDLR_S100**
* Encrypted/locked-down firmware. Yes or No?     
	**Yes**
* Encrypted storage of the miner swarm_key, either via disk encryption or hardware measures. Yes or No?    
	**Yes , secured in ECC608 chip**
* Encrypted buses, potting and other anti-tampering measures. Yes or No? (Please note, the final design will be audited against this statement. Do not answer 'yes' unless the design will have these features and a description of where they are implemented can be provided.)    
**Yes, by ECC608 chip**
* Willingness to submit a prototype for audit, and sharing those audit results publicly (pass or fail) Yes or No?    
	**Yes**

## Hardware Information (required) Please provide detailed hardware designs, including relevant parts.
Evidence of a functioning prototype - photos/videos. Renderings are OK but physical prototypes are much, much better.     
  <img src="https://github.com/hyeonsfather/hotspot-manufacturers/blob/main/img/plg420_shape_diagram.png" width="70%">

1.  **CPU Part: RPI Compute Module 4 with Wifi**
2. **Estimated size: 130 x 130 mm**
3. **LoRa RF: SPI Interface with CPU and SX1303 (RAK 5146) will be applied.**
4. **Ethernet: 10/100/1000BaseT PoE**
5. **Microchips ECC608 on I2C Interface**

* What are your plans for software setup and configuration for the devices?    
	**Web UI interface for setup and firmware upgrade is supported by LAN/WAN network interface which includes WiFi as well.** This would includes remote updates and the ability for hosts to change wifi settings, via Helium's official app or otherwise. 

* Which security implementation (ECC608, TPM, TrustZone, other) are you using?     
	**ECC608-TNGHNT**
* Which LoRa chipset are you planning to use in your gateway? (We recommend you don't use the SX1301 in new designs.)    
	**SX1303 (RAK 5146)**
* What is the CPU?    
	**32KB I-Cache an 32KB D-cache 64bit RISC CPU**
* Other Hardware Specifications:     
  <img src="https://github.com/hyeonsfather/hotspot-manufacturers/blob/main/img/plg420_shape_diagram.png" width="70%">

## Manufacturing Information (required)
* Have you built and delivered radio hardware products before?    
	**Yes, our company has been manufacturing and supplying wireless communication hardware products since 2014, we built Zigbee, Bluetooth, and Wi-Fi, LoRaWan products.** 
* Have you built gateways before?    
	**Yes**
* How many gateways did you make?    
	**100 LoRa gateways** 
* If you have not built gateways before, are you using a third party manufacturer or working with a partner? This is the single largest risk with most hardware ventures. If possible please provide information about your manufacturing partners and supply chain.
* Where are you sourcing your components from?     
	**Local chip agency such as STMicro, Semtech, RAK wireless**
* How many radio modules/ concentrators can you procure?     
	**We don't need any type of radio module and concentrators. we put Semtech chips on board directly.**   

## Proof of Identity:
Per typical KYC/AML procedures, proof of identity for major shareholders (25%+ ownership) will be expected to be provided privately to representatives from the Helium Foundation. This will be attested and publicly confirmed by those representatives. Details for this will be provided after your application has been submitted on GitHub. 

## Budget & Capital (required)
* How many hotspots are you planning to manufacture and sell within the first six months of sales?     
	**over 2000**
* How much money will be required up-front? How much money do you have on-hand, and how much do you have access to?     
	**There is no issue for budget.**
* What is your plan for additional financing if required? (This is the second biggest risk in new hardware ventures, getting almost over the line and then running out of cash.)     
	**If the demand for hotspots is high and we need more budge than we expected, we have an investment company which will back us on the manufacturing costs**

## Risks & Challenges (required)
Please tell us about some of the challenges that would prevent these products from becoming a reality and how you might address them.    
	**None**

## Other information (if you do not provide contact information we cannot review your proposal)
## Contact Info: 
* Contact Email (required) - justinkim1393@gdnet.co.kr
* Website (required) - www.gdnet.co.kr
* Twitter profile -
* Facebook profile -
* Discord - 
* Other social profiles -
* Tech Service Support: support@gdnet.co.kr / service@gdnet.co.kr (+82-31-344-0177)
* Korea Local Address : Hanlimventuretown 301-1Ho, 284 Gongdan-ro, Gunpo-si, Gyeonggi-do, Republic of Korea (15809)

## Payment methods available (required):
**Bank Transfer, Credit Card, Cash**