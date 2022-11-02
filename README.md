# high-street-jam
## A simple indicator to warn of potential gridlock along the High Street in Northallerton when a train is abut to cross or has just crossed low gates railway crossing and therefore a high likelihood of traffic backing up along the high street
### "As a driver who needs to travel along the high street during core shopping noirse I would like a quick simple way to check if travelling along the high street in Northallerton is kikely to result in delays due to a train passing low gates level crossing."
This is a small personal project that aims to use api data from realtimetrains.co.uk to check if a train is due at low gates crossing in the next few minutes or has passed in the last few minutes. This can then give a simple indicator of two numbers - how many minutes ago the last train went through as well as how many minutes untik the next train. The initial thought is that these two numbers could be colour coded in a simple traffic kight system - red, amber green, dependinng on how soo or recent a train passed. This kind of project could be extended in many ways including user configuration and potential automationand linkage into other systems  However version one will be focussed on a simple MVP that aims to present the data on a simple web page that is easily readable on a mobile device.
This is a fun learning project and as such is only to be used as an indicator. For example during off peak hours the traffic delays may well be minimised but this will not be taken into account.
#### MVP
A mobile optimised web page showing how many minutes until next train at low gates and how many minutes since the last train passed

A colour coding giving a simole indication of impact - eg very small number of mins (red), small mins (amber), longer mins(green)
