# home

# enertia.io
Decentralized Electric Vehicle Charging Platform

Reference Document : https://docs.google.com/presentation/d/1FWKWbQKrXF7dZ-Qj8igWW0MToMKeRr4tCUqdrgavMvk/edit?usp=sharing

## What are we using to develop the platform ?

[Technology Stack / Code here](https://github.com/enertia-io/www_enertia_io)


## Challenges / Problems

* No open standards 
* Different modes of payments (not secured, cost effective and slow)
* Underutilization of EV InfraStructure
* Inability to integrate private networks.
* No software / application available to show realtime status from Charging points
* Data for EV Charging is unorganized and less meaningful 


## The Project

Enertia is focused on developing an open source charging platform built on top of the ThreeFold platform.
Based in the United Arab Emirates focused on promoting sustainable and energy efficiency by applying threefold technology to improve energy storage, distribution and scalability. 

Part of the [atwg.tech](https://atwg.tech) incubator.

* Live Maps with RealTime Charge Point Status → Atleast we should be able to integrate with Top Providers in the first release(DEWA, GreenParking, Tesla )
* Try to come up with a Universal Charging Card / payment / token mechanism that can apply to all Charging Points.
* Ability add / integrate new Charging points with minimal effort
* Potentially create EV Token backed by Charging Capacity on the Enertia Grid. 
* Have a rewards system (EV Token) for the EV community where they can provide a feedback / verify against a charging point
* A click to chat feature for NearBy EV drivers to communicate
* A feature that could enlist “Available” and Top Rated EV nearby charging points.
* Easy API tools for OEMS like Tesla to add our app for autnomus charging protocols.  

## How will Charge Point Transaction really work ?

* In order to integrate the EV chargers with the ThreeFold block chain. We need to ensure that the chargers run the TFchain client. For that we'll have to talk to the OEMs so that the chargers register them over the Blockchain. 

* All chargers would have an TF embedded wallet that would be binded to the owner's Wallet.

* So when a charging transaction is made, the Charging point will deduct the tokens from the User's wallet. The deducted tokens/money will add up to the ChargePoint's address that will eventually reflect on the owner's wallet.

* We will need to write a Smart contract specifically for this over the blockchain. 

The most challenging part would be the technical Interconnects between OEMs and us!  

## Key Aspects

- Enertia EVToken 1-1 relation with TF Token
- Target 500 nr of charging stations in Dubai
- OEM partnerships (Car Manufacturers)
- Governmental support. 

