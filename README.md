# Satellite Interference Research

## NGSO Interference with Radioastronomy Service (RAS)
https://www.youtube.com/@spectrumxcenter/videos

## NGSO-NGSO Interference Regulation Metrics
- Degraded Throughput based on ITU Article 22.5L NGSO-GSO and Resolution 770 Methodology
  - Monte Carlo simulation over a year of C/N with and without interfering constellation, worst case pointing angles and sidelobes, and add rain attenuation cdf
    - From the resulting cdf you can calculate spectral efficiency "throughput" reduction percentage, and with lowest C/N threshold you can calculate unavailability time percentage
    - Do we have to assume worst case pointing angles or is there any algorithmic analysis to be done? Randomized angles may underestimate  
  - How to deal with tolerances uncertainty ranges? How to quantify confidence interval and num samples needed in order to converge to a sufficiently precise answer?
- How to calculate constellation's ground footprint over the course of a year like a heatmap of what area covered what percent of time - utilize constellation and orbital plane symmetry  

## SpaceX Direct-to-Cell
Satellite Space Stations filings
- SAT-MOD-20230207-00021 Application for Modification of Authorization https://fcc.report/IBFS/SAT-MOD-20230207-00021
- SAT-LOA-20200526-00055 Application to Launch and Operate https://fcc.report/IBFS/SAT-LOA-20200526-00055

Modification of Authorization for the SpaceX Gen2 NGSO Satellite System to Add a Direct-to-Cellular System  

"SpaceX requests authorization to operate its direct-to-cellular payload to communicate on an unprotected, non-interference basis in the 1910-1915 MHz uplink E-s and 1990-1995 MHz downlink s-E bands PCS G Block with off-the-shelf cellular mobile devices otherwise authorized by the Commission to operate in the same frequencies."  

Application: Space Station -> Amendment to a Pending Application -> Mobile Satellite Service -> 1910-1995 MHz -> Non−Geostationary Space Station -> authorization to add new emission designator and related service, antenna, and frequency

Technical Narrative
- 1910-1915 MHz uplink E-s and 1990-1995 MHz downlink s-E bands PCS G Block
- up to 7,500 satellites at orbital shells at 525 km, 530 km, and 535 km altitudes. maintain apogee and perigee within an altitude range of -50 km to +45 km. inclination maintained to less than 0.5 degrees of the respective target values. RAANs precess and span the range of 0-360 degrees. See Direct-to-Cell_MSS_T.mdb 
- cover ±58° latitude by mid-2024, entirety of the contiguous United States, Hawaii, Puerto Rico, and the majority of Southeast Alaska, Kodiak, and the Aleutian Islands - where T-Mobile has exclusive access to PCS G Block
- Swarm 150 small NGSO satellites, narrowband services in 137-138 MHz and 148-150.5 very-high frequency (“VHF”) MSS bands, use to enable satellite connectivity for LTE devices (cell phones + LTE-capable IoT devices) to encompass all ranges of data rates and power levels.
- voice, messaging, basic web browsing at theoretical peak speeds of up to either 3.0 Mbps or 7.2 Mbps peak upload (Earth-to-space) over 1.4 MHz or 5 MHz bandwidth channels per beam, respectively, and up to either 4.4 Mbps or 18.3 Mbps on the downlink (space-to-Earth) over the 1.4 MHz channels or the 5 MHz channel per beam, respectively.
- 3GPP LTE Layer 2 concepts allow per-user scheduling as low as one resource block centered at any frequency within the 5 MHz spectrum
- multiple beams per satellite, beam centers remain stationary on the ground. compensate and correct for Doppler and time synchronization effects both inside and between beams. algorithm places beams such that they meet any single or aggregate power-flux density (“PFD”) limit and support user handoff between two beams and point neighboring beams to minimize interference from beam-to-beam
- channelized frequency plan of three or four 1.4 MHz downlink channels or one 5 MHz downlink channel and 1.4 MHz channels or one 5 MHz channels on the uplink with center frequency set appropriately within the 5 MHz PCS G Block uplink or downlink band
- peak antenna gain of 38 dBi, peak EIRP 58 dBW, peak EIRP density of -2.33 dBW/Hz (per 1.4 MHz channel), circular polarization
- cell phone typically low gain antennas -5 dBi, uplink with vertical polarization
- operate in the PCS G Block on a non-protected, non-interference basis, without causing harmful interference to or requiring protection from any other service duly licensed in these bands, cooperative agreement with T-Mobile’s primary terrestrial mobile operations, protect adjacent band operations from harmful interference
- all downlink spot beams independently steerable. coverage area for each user beam is a cell inside the -3 and -5 dB contour (see img) with optionality for either contour size. At a given center frequency, only a single beam typically would cover a user cell on the ground from a given satellite. implement frequency reuse factors to minimize interference and provide a high-performance experience to the user.
- carrier frequency of each space station transmitter shall be maintained within 0.002 percent frequency tolerance
- no established PFD limit for downlink in PCS G Block. Instead, Section 24.236 for PCS operations “predicted or measured median field strength at any location on the border of the PCS service area shall not exceed 47 dBμV/m unless the parties agree to a higher field strength”, converted into equivalent PFD limit. SpaceX and T-Mobile have agreed to an appropriate field strength limit. Section 24.236 applies at borders between US and Mexico, and US and Canada. SpaceX will maintain PFD levels below at national borders and space out downlink beams appropriately from those borders to protect primary terrestrial mobile operations from interference.

- not as relevant:
  - Each active satellite transmission chain (channel amplifiers and associated solid state power amplifier) can be individually turned on and off by ground telecommand, ceasing emissions from the satellite
  - meet requirements for MSS emergency 911 services

- sidenotes:
  - Backhaul use gateway links authorized in Ka-band spectrum, pending future E-band links, high-gain steered beams to simultaneously communicate with multiple SpaceX satellites from a single gateway site, optical inter-satellite links
  - No GSO satellite networks filed for coordination in PCS G Block worldwide. In the future, refrain from imposing EPFD limits on NGSO systems since can co-exist with GSO services without EPFD limits, see ITU Radio Regs. 22.5C, 22.5D, 22.5F
  - German Administration submitted on SpaceX’s behalf to ITU, operations outside of the United States MARS-VLS and MARS-ULS contemplate 1429 MHz to 2690 MHz. protect services allocated under Safety-of-Life, Radio Astronomy, Space Research, Radionavigation Satellite, Aeronautical Radionavigation, and Space Operations
  - orbital debris mitigation discussion from the Gen2 system application and authorization, see Letter from David Goldman to Marlene H. Dortch, IBFS File Nos. SAT-LOA-20200526-00055 and SAT-AMD-20210818-00105, at 1-5 (Aug. 19, 2022)
