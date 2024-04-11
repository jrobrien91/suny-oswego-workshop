PROJECT: SOURCE-2024
FACILITY: FARM
DATA: DOW6 mobile radar

The radar data in this directory was collected by the FARM DOW6 mobile radar and only includes 
data from the low frequency (9.398 GHz) dual-polarization radar channel. Data have been
re-translated from the raw I/Q time series using LROSE software (version: 20230814 Jade). More
information on LROSE software can be found online:

https://github.com/NCAR/lrose-core

No corrections have been applied to the radar data except rotating the azimuth angles so that 0 deg
azimuth is aligned with true north.

Vehicle headings were estimated in the field using solar scans, except for SOURCE IOP03, which was
a nocturnal deployment. For IOP03 a tall tower clutter target was used to estimate the vehicle
heading. Radar deployment locations (latitude & longitude) have also been corrected in the radar
data.

The deployment locations and vehicle headings for SOURCE-2024 used to correct radar data are listed
below and have been verified by the data manager (Josh Aikins; jaikins@illinois.edu):

20240402_IOP01
lat: 43.344110
lon: -76.697725
heading: 56.0

20240403_IOP02
lat: 43.463067
lon: -76.518163
heading: 159.4

20240404_IOP03
lat: 43.799822
lon: -75.730695
heading: 181.8

Please see the deployment logs for more information on deployments.

Below is a description of the radar data fields.

DBMHC		Received power, horizontal channel, co-polar (dBm)
DBMVC		Received power, vertical channel, co-polar (dBm)
DBZHC		Equivalent reflectivity factor, horizontal channel, co-polar (dBZ)
DBZVC		Equivalent reflectivity factor, vertical channel, co-polar (dBZ)
KDP			Specific differential phase (deg/km)
NCP			Normalized coherent power (unitless)
PHIDP		Differential phase shift (deg)
RHOHV		Correlation coefficient (unitless)
SNRHC		Signal-to-noise ratio, horizontal channel, co-polar (dB)
SNRVC		Signal-to-noise ratio, vertical channel, co-polar (dB)
TRIP_FLA	Second trip detection (values > 3 indicate second trip)
VEL			Doppler velocity (m/s)
VL			Doppler velocity, long pulse (m/s)
VS			Doppler velocity, short pulse (m/s)
WIDTH		Spectrum width (m/s)
ZDRM		Measured differential reflectivity with no correction (dB)
*Clutter Filtered Fields (“_F” appendage as needed)

Radar data have been provided in both DORADE and cfradial netcdf formats. All files are individual
sweeps, which consists of a full surveillance scan (SUR) or a range-height-indicator (RHI) scan.
Sweeps have not been aggregated into complete volumes.

---------------------------------------------------------------------------------------------------
