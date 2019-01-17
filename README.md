# License
Matlab software package for atmospheric tomography processing

Copyright (C) 2018 Gregor Moeller

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.

# References
G. Moeller, Reconstruction of 3D wet refractivity fields in the lower atmosphere along bended GNSS signal paths, Dissertation, Department of Geodesy and Geoinformation, TU Wien, 2017, https://repositum.tuwien.ac.at/obvutwoa/content/titleinfo/2284850

G. Moeller and D. Landskron, Atmospheric bending effects in GNSS tomography, Atmos. Meas. Tech, 12, 23-24, doi: 10.5194/amt-12-23-2019, https://www.atmos-meas-tech.net/12/23/2019/


# About ATom

ATom is a MATLAB GUI based software package, which has been developed within the GNSS-ATom project (840098) - financed by the Austrian Research Promotion Agency (FFG) in the years 2013 to 2015.

‘ATom’ stands for Atmospheric Tomography, the core part of the ATom software package. In addition, ATom allows for conversion of:

- broadcast ephemerides into ECEF satellite positions, elevation or azimuth angles
- zenith total delays into zenith wet delays or slant delays 
- numerical weather model data into refractivity fields
- refractivity fields into zenith delays
- slant delays into total or wet refractivity fields

Therefore, common formats like Napeos, Bernese, IGS SINEX Tropo or the ‘new’ SINEX Tropo format, navigation messages for GPS and GLONASS as well as several formats for post-fit residuals and in-situ measurements are supported.

For more details see the manual ATom_Manual_2018-08-03.pdf
