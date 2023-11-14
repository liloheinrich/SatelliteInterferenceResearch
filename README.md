# Satellite Interference Research

## NGSO Interference with Radioastronomy Service (RAS)
https://www.youtube.com/@spectrumxcenter/videos

## SpaceX Direct-to-Cell
Satellite Space Stations filings
- SAT-MOD-20230207-00021 Application for Modification of Authorization https://fcc.report/IBFS/SAT-MOD-20230207-00021
- SAT-LOA-20200526-00055 Application to Launch and Operate https://fcc.report/IBFS/SAT-LOA-20200526-00055

Modification of Authorization for the SpaceX Gen2 NGSO Satellite System to Add a Direct-to-Cellular System  
"SpaceX requests authorization to operate its direct-to-cellular payload to communicate on an unprotected, non-interference basis in the **1910-1915 MHz uplink E-s** and **1990-1995 MHz downlink s-E** bands PCS G Block with off-the-shelf cellular mobile devices otherwise authorized by the Commission to operate in the same frequencies."  

Application for: Space Station -> Amendment to a Pending Application -> Mobile Satellite Service -> 1910-1995 MHz -> Non−Geostationary Space Station ->
  - authorization to add new emission designator and related service
  - authorization to add antenna
  - authorization to add frequency

Technical Narrative
- Scope and Purpose
  - This attachment contains information describing SpaceX’s non-geostationary orbit (“NGSO”) satellite system and use of the 1910-1915 MHz and 1990-1995 MHz bands (the “PCS G Block”) for a direct-to-cellular service in cooperative agreement with T-Mobile’s primary terrestrial mobile operations.
- Overall Descriptions
  - Constellation information is generally available in **Attachment A (“Technical Information to Supplement Schedule S”)** to the previous applications related to SpaceX’s second-generation NGSO Fixed-Satellite Service (“FSS”) system (“Gen2 system”). See: SAT-LOA-20200526-00055; Amendment SAT-AMD-20210818-00105; see also FCC 22-91 (“Gen2 Authorization”).
  - Orbital Parameters
    - Gen2 Authorization initially granted SpaceX authority to launch and operate **7,500 satellites**. Under the modification proposed herein, SpaceX requests adding a **direct-to-cellular Mobile-Satellite Service (“MSS”) payload** operating in the PCS G Block in the United States (the “SpaceX direct-to-cellular system”) on satellites in the Gen2 system, as part of its current authorization. The SpaceX direct-to-cellular system will be deployed on **up to 7,500 satellites** within the orbital shells at **525 km, 530 km, and 535 km altitudes**.
    - At full deployment, this hosted payload will enable SpaceX to provide full and **continuous coverage of the Earth within ±58° latitude by mid-2024**. The Gen2 system will maintain apogee and perigee within an **altitude range of -50 km to +45 km**, and **inclination will be maintained to less than 0.5 degrees** of the respective target values, consistent with the Gen2 Authorization. The right ascension of the ascending nodes (“RAANs”) will precess and **span the full range of 0-360 degrees**. See Schedule S Technical Report and **Direct-to-Cell_MSS_T.mdb database** for more details.
  - Technology and Operations
    - The SpaceX direct-to-cellular system will utilize advanced **phased array beam-forming and digital processing technologies** onboard each satellite payload in order to make **highly efficient use of spectrum resources and share spectrum flexibly** with other space-based and terrestriallicensed users.
    - SpaceX seeks to leverage its existing space resources to provide even more **ubiquitous connectivity options** to Americans, including **outside the reach of traditional terrestrial mobile networks**, with a goal of **global affordable connectivity**. To expand into mobile service, SpaceX **acquired Swarm Technologies, Inc. (“Swarm”)**, a company authorized to deploy and operate **150 small NGSO satellites designed to provide narrowband services in the 137-138 MHz and 148-150.5 very-high frequency (“VHF”) MSS bands**. With this application, SpaceX’s proposed direct-to-cellular system will **enable satellite connectivity for LTE devices, which can include cell phones as well as LTE-capable IoT devices**. The combination of direct-to-cellular and the Swarm IoT connectivity solutions truly encompass all ranges of data rates and power levels for devices around the world.
    - In the PCS G Block, SpaceX’s direct-to-cellular service in the United States would be able to provide **voice, messaging, and basic web browsing at theoretical peak speeds of up to either 3.0 Mbps or 7.2 Mbps peak upload (Earth-to-space) over 1.4 MHz or 5 MHz bandwidth channels per beam, respectively, and up to either 4.4 Mbps or 18.3 Mbps on the downlink (space-to-Earth) over the 1.4 MHz channels or the 5 MHz channel per beam, respectively**. SpaceX plans to implement **3GPP LTE Layer 2 concepts that allow per-user scheduling as low as one resource block centered at any frequency within the 5 MHz spectrum** with appropriate guard bands. SpaceX’s direct-to-cellular system will include multiple beams per satellite, and beam centers will remain stationary on the ground. SpaceX will **compensate and correct for Doppler and time synchronization effects both inside and between beams**. An algorithm will **place beams such that they meet any single or aggregate power-flux density (“PFD”) limit**. The algorithm will also **support user handoff between two beams and point neighboring beams appropriately to minimize interference from beam-to-beam**.
    - In the United States, user terminals will be unmodified, commercial off-the-shelf cellular phones that can communicate in the PCS G Block, which is part of LTE Band 25. These devices typically have **low gain antennas (e.g., -5 dBi)** and will already be certified to operate under Part 24 rules within the United States.
  - Spectrum
    - SpaceX requests authority to provide seamless satellite connectivity in the United States **to T-Mobile USA, Inc.** (with its subsidiaries, collectively referred to as “T-Mobile”) wireless subscribers in the PCS G Block, across which T-Mobile has exclusive, nationwide access.
    - A channelized frequency plan is provided in the associated Schedule S, encompassing **three or four 1.4 MHz downlink channels** or **one 5 MHz downlink channel and 1.4 MHz channels** or **one 5 MHz channels on the uplink with center frequency set appropriately within the 5 MHz PCS G Block uplink or downlink band (???)**. Satellite downlink transmissions will operate over a range of parameters more fully captured in the Schedule S, with no more than a **peak antenna gain of 38 dBi**, **peak Effective Isotropic Radiated Power (“EIRP”) of 58 dBW**, and **peak EIRP density of -2.33 dBW/Hz (per 1.4 MHz channel)**. The direct-to-cellular system satellites will transmit with **circular polarization using L-band antennas**, although the Schedule S lists both right-hand circular polarization (“RHCP”) and left-hand circular polarization (“LHCP”) for completeness. All uplink operations from certified mobile handsets will conform to Part 24 standards and limits, with **vertical polarization**, although the Schedule S lists both vertical and horizontal polarization for completeness.
    - SpaceX certifies that its direct-to-cellular system will operate **without causing harmful interference to or requiring protection from any other service duly licensed in these bands**. The SpaceX direct-to-cellular system will operate in the United States pursuant to a **cooperative agreement with T-Mobile’s primary terrestrial mobile operations** and will **protect adjacent band operations from harmful interference**. Moreover, SpaceX seeks to operate in the PCS G Block on a non-protected, non-interference basis.
- Predicted Space Station Antenna Gain Contours
  - All downlink spot beams on each SpaceX satellite are independently steerable. The **intended coverage area for each user beam is a cell inside the -3 and -5 dB contour**, as illustrated in Figure A.3-1. **(0 deg 33 longitude, 0 deg 25 latitude?).** SpaceX is maintaining **optionality for either contour size** in the design. **At a given center frequency, only a single beam typically would cover a user cell on the ground from a given satellite**. SpaceX plans to implement appropriate **frequency reuse factors to minimize interference and provide a high-performance experience to the user (what is the frequency reuse for???)**. Again, domestic operations in the PCS G Block will protect T-Mobile’s primary terrestrial mobile operations in accordance with an agreement between the companies. In addition, in the United States, SpaceX will comply with the **boundary field strength limit specified in the PCS rules (See later details)**.
- TT&C Characteristics
  - SpaceX will use the existing TT&C subsystem on its Gen2 system for communications with the spacecraft during pre-launch, transfer orbit, and on-station operations, as well as during spacecraft emergencies, consistent with the Gen2 Authorization. A description of the SpaceX TT&C subsystem is provided in the Previous Applications and incorported by reference.
- Backhaul Operations
  - The SpaceX direct-to-cellular system backhaul will use gateway links authorized in Ka-band spectrum for the Gen2 system, as well as **future E-band links, which remain pending**. As discussed in the Previous Applications, the SpaceX Gen2 system **will utilize high-gain steered beams to simultaneously communicate with multiple SpaceX satellites from a single gateway site**. SpaceX has also **deployed optical inter-satellite links** and anticipates that they **will provide seamless network management and continuity of service while minimizing the spectrum footprint of the system overall and facilitating spectrum sharing with other space-based and terrestrial systems**. All backhaul will be consistent with the Gen2 system parameters. A description of the SpaceX TT&C subsystem is provided in the Previous Applications and incorporated by reference.
- Geographic Coverage
  - (In addition to += 58 degrees latitude coverage) For purposes of the service SpaceX proposes in the United States, the system will provide coverage in the entirety of the contiguous United States, Hawaii, Puerto Rico, and the majority of Southeast Alaska, Kodiak, and the Aleutian Islands—all locations where T-Mobile has exclusive access to the PCS G Block. Once operational, the direct-to-cellular
system will instantly serve geographic areas that are unserved or underserved and connect millions of Americans across the country.
- Cessation of Emissions
  - **Each active satellite transmission chain (channel amplifiers and associated solid state power amplifier) can be individually turned on and off by ground telecommand, thereby causing cessation of emissions from the satellite**, as required by Section 25.207 of the Commission’s rules.
- E911 Compliance
  - The direct-to-cellular system **will meet requirements for MSS emergency 911 services** under Section 9.18 of the Commission’s rules.
- Frequency Tolerance
  - The **carrier frequency of each space station transmitter shall be maintained within 0.002 percent of the reference frequency**, as required by Section 25.202(e) of the Commission’s rules.
- Interference Analyses
  - The Commission has recognized that a proposed modification to an **NGSO authorization should be granted where it “does not present any significant interference problems and is otherwise
consistent with Commission policies.”**
  - Compliance With Out-of-Band Field Strength Limits
    - The Commission’s Part 25 rules and the ITU Radio Regulations **do not directly establish a power-flux density (“PFD”) limit for downlink (space-to-Earth) communications in the PCS G Block**. Instead, under **Section 24.236 for PCS operations**, “[t]he **predicted or measured median field strength at any location on the border of the PCS service area shall not exceed __47 dBμV/m__ unless the parties agree to a higher field strength.”** In-band, **SpaceX and T-Mobile have agreed to an appropriate field strength limit**. Recognizing that **Section 24.236 applies at borders between (a) the United States and Mexico and (b) the United States and Canada**, the field strength limits specified in Section 24.236 can be converted into an **__equivalent PFD limit__ that will provide the same protections to in-band operations** as the field strength limit itself. SpaceX **will maintain PFD levels below the equivalent PFD value at national borders and space downlink beams appropriately from those borders to protect primary terrestrial mobile operations from interference**. SpaceX will only exceed these limits at the national border in the event that it has been authorized to do so by the regulatory authority of the appropriate border country and after it has provided documentation of such authorization to the Commission.
  - Interference Protection for Geostationary Satellite Networks
    - No geostationary orbit (“GSO”) satellite networks have been filed for coordination in the PCS G Block worldwide. Should GSO operators seek access to these frequencies in the future, the Commission should **refrain from imposing equivalent power flux-density (“EPFD”) limits on NGSO systems**. Notwithstanding the fact that NGSO providers would have filing priority, current operations within multiple frequencies affirm that **NGSO systems can capably co-exist with GSO services without unnecessary EPFD limits. See ITU Radio Regs. 22.5C, 22.5D, and 22.5F.**
  - Interference with Respect to Other Non-Geostationary Satellite Systems
    - The ITU has procedures for coordination among NGSO systems. SpaceX has engineered its system with the technical flexibility that will facilitate the necessary coordination with other NGSO satellite systems and is committed to achieving mutually satisfactory agreements. There are no NGSO systems filed through the United States operating in the PCS G Block and none filed by any other administration that has been granted U.S. market access. Thus, no further coordination or protection is required as part of this application for service in the United States.
  - Interference with Respect to Terrestrial Networks
    - **T-Mobile is the exclusive licensee of the PCS G Block in the United States**. T-Mobile has stated in a separate spectrum manager lease notification that it has an agreement with SpaceX regarding operation of the direct-to-cellular system in a way that is compatible with T-Mobile’s primary terrestrial mobile operations. Thus, no further coordination or protection is required.
- Coordination With U.S. Government Networks
   - To the extent necessary, SpaceX will coordinate with the National Telecommunications and Information Administration (“NTIA”) to protect any operations in this or adjacent bands from harmful interference and to ensure that they are compatible with federal uses. SpaceX notes that the **U.S. Table of Frequency Allocations lists no federal allocations from 1850-2205 MHz**.
- ITU Filings for SpaceX
  - The **German Administration has submitted system information on SpaceX’s behalf for ITU publication under the names MARS-VLS and MARS-ULS**. With respect to operations in the United States, the filings request operation in the PCS G Block on a non-interference, nonprotection basis to support the direct-to-cellular system through an Advance Publication Information (“API”) based on Radio Regulation 4.4. **For operations outside of the United States, the MARS-VLS and MARS-ULS ITU filings contemplate use of frequencies from 1429 MHz to 2690 MHz**. SpaceX intends to provide similar direct-to-cellular operations in international markets, subject to cooperation with terrestrial mobile partners authorized to provide service on specified frequencies, and consistent with spectrum reuse authorizations within each country. These cooperative arrangements will **provide protections for services allocated under Safety-of-Life, Radio Astronomy, Space Research, Radionavigation Satellite, Aeronautical Radionavigation, and Space Operations**. SpaceX’s operations will be consistent with the parameters specified in its ITU filings and compliant with any conditions of the authorizing Administration.
- Orbital Debris Mitigation
  - SpaceX hereby incorporates by reference the **orbital debris mitigation discussion from the Gen2 system application and authorization**, and the SpaceX direct-to-cellular system will comply with any conditions on the Gen2 system relating to orbital debris mitigation. See generally Previous Applications; see also **Letter from David Goldman to Marlene H. Dortch, IBFS File Nos. SAT-LOA-20200526-00055 and SAT-AMD-20210818-00105, at 1-5 (Aug. 19, 2022).**

Schedule S Technical Report

Other Attachments to Filing
