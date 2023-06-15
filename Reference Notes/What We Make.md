# What We Make 👩🏽‍💻

## In Use 🌎
### mSupply 
**Type**: Licensed  
**Repo**: [mSupply](https://github.com/openmsupply/msupply)

[mSupply](https://msupply.org.nz/) is an electronic Logistics Management Information System (eLMIS) for health supply chains in low- and middle-income countries, with deployments in over 30 countries across the Pacific, Asia and Africa. 

At the heart of mSupply is an inventory control system which records each receipt and issue of stock, tracking the movement of health supplies throughout the supply chain – from the central warehouse to rural clinics and individual patients. 

mSupply is designed to work in limited-resource settings, allowing users to continue working seamlessly in environments with intermittent power and internet connections. It is available in both desktop and mobile versions, and can be configured or customised to meet local health system requirements.

### mSupply Mobile 
**Type**: Open Source <br />
**Repo**: [openmsupply/mobile](https://github.com/openmsupply/mobile)

A user-friendly, offline-first mobile app for use with mSupply

### Universal Codes Server 
**Type**: Open Source <br />
**Repo**: [openmsupply/unified-codes](https://github.com/openmsupply/unified-codes)

The [Universal Codes Server](https://codes.msupply.foundation/) is a system for linking country-specific codes for medicines and consumables in mSupply to a set of standard ‘universal’ codes. Once linked, countries will have access to an item’s clinical category, drug interactions and reference pricing for procurement activities. This important data is sourced from other international coding systems and references including the WHO Model Essential Medicines List, NZULM, RxNav and UNSPC, and will allow for regional reporting and cross-country supply chain activities to occur.

The following external system codes have been linked to the Universal Code Server:
* NZULM:  This will eventually allow us to incorporate PHARMAC reference pricing (to provide benchmarking of prices being paid by PICT mSupply using countries) and GS1 barcodes for approved medicines.
* WHO Essential Medicines List Category: These categories are used by almost all countries for classification and reporting, but the initial work of classification has been onerous enough that many PICTs have not undertaken it. There is now no longer any need for them to do so, as the classification system is provided automatically.
* RxNav RxCUI: This code links to the National Library of Medicine database that provides the world’s most comprehensive and up-to-date drug interactions database.
* UNSPC: United Nations Standard Products and Services Codes are the sanctioned coding system used by the UN.


## Currently Working On 👷🏽
###  Open mSupply
**Type**: Open Source<br />
**Frontend Repo**: [openmsupply/openmsupply-client](https://github.com/openmsupply/remote-server)<br />
**Backend Repo**: [openmsupply/remote-server](https://github.com/openmsupply/openmsupply-client)

An open source rebuild of mSupply, in a modern stack (Rust and Typescript) and with the intent of improving the intuitivity of use from the original mSupply.


### Health Supply Hub 
**Repo**: [openmsupply/health-supply-hub](https://github.com/openmsupply/health-supply-hub)

Health Supply Hub is a central, digital space for countries to liaise with pharmaceutical suppliers for procurement-related activities. It syncs with the Tender Module in mSupply for seamless management of tenders and will include a price-sharing tool displaying the PHARMAC-subsidised price for each item as a regional benchmark. This will help flag when countries are paying excessive prices for items and aim to reduce those occurrences. The Health Supply Hub is currently in development.

The COVID-19 pandemic has illustrated how valuable such a system will be, as simple information on availability of essential medicines from regional suppliers was both valuable and hard to obtain during the year.
