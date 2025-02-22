# dil14-oscillator
A DIL-16 oscillator using a 3225 SMD crystal. Originally I made this for Commodore Amigas, because the 28.6363MHz and 28.37516MHz oscillators are becoming hard to get. Most modern oscillators now are 3.3V types

I found that while they're not common, it IS possible to get crystals of those frequencies in SMD format. For example Mouser have [CTS 403C35D28M37500](https://www.mouser.co.uk/ProductDetail/CTS-Electronic-Components/403C35D28M37500?qs=tjlMjqRIEYSI3TNJCnGYSw%3D%3D) and [ECS 520-286.3-18-33-JGNT](https://www.mouser.co.uk/ProductDetail/ECS/ECS-286.3-18-33-JGN-TR?qs=wd5RIQLrsJjqi%252B%2F66hueEA%3D%3D). These are suitable for use with an Amiga, but they need an oscillator circuit to work. This was easily achievable with the usual Pierce oscillator configuration using logic gates. 

I chose to use a "picogate" type part to keep the size small, the 74LVC2GU04. This is a SOT23-6 part (aka SOT457 o TSOP6) and perfect for the job. 

# Whats in this repo? 

In here you can find EAGLE 7.6 board and schematic, Gerber files for manufacture, and BOM + CPL files suitable for use with [JLCPCB](https://jlcpcb.com)
