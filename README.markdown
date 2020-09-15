Z-Model of a Train Control System
=================================

This is an unverified formal specification of a train control system design, written using the Z/EVES tool.

This system design aims to capture:
- A model of the rail network
- Signals
- Switches (aka points)
- Crossings/junctions
- Block sections
- Manual route setting
- Interlocking rules
- Automatic Train Operation (ATO) - although the design is quite naїve.
- Registration of stations
- Registration of lines
- Level crossings

The operations supported include:
- Installing level crossings
- Installing inactive block sections
- Installing tracks onto inactive block sections
- Removing tracks from inactive block sections
- Installing switches onto inactive block sections
- Installing crossings onto inactive block sections
- Removing switches/crossings from inactive block sections
- Activating block sections
- Deactivating block sections
- Setting routes for an active block section
- Cancelling routes for an active block section
- Building a new station
- Registering a new line
- Registering a new train
- Inputting train location data from track circuits / axle counters
- Refreshing a naїve ATO system
- Outputting data for use on a mimic panel.

See Train Control System.pdf for a slightly more detailed showcase.

**Disclaimer: This formal specification is only a personal educational exercise. I am certain that there are some mistakes in the model, let alone held to a satisfactory quality.**
