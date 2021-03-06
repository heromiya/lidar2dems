#lidar2dems

The lidar2dems project is a collection open-source (FreeBSD license) command line utilities for supporting the easy creation of Digital Elevation Models (DEMs) from LiDAR data. lidar2dems uses the PDAL library (and associated dependencies) for doing the actual point processing and gridding of point clouds into raster data.

See the [lidar2dems documentation](http://applied-geosolutions.github.io/lidar2dems/) for complete description, usage, and tutorial

####Funding

lidar2dems was created by Applied GeoSolutions, LLC and the University of New Hampshire as part of a NASA-funded Carbon Monitoring System Project (NASA grant #NNX13AP88G; PI Stephen Hagen). In this project, Applied GeoSolutions and project partners are working with the government of Indonesia ([LAPAN](http://www.lapan.go.id)) to improve forest monitoring in Kalimantan by composing detailed, high resolution maps of forest carbon. If you have questions about this project please email [oss@appliedgeosolutions.com](mailto:oss@appliedgeosolutions.com)

####Authors and Contributors

* [Matthew Hanson](http://github.com/matthewhanson), matt.a.hanson@gmail.com
* Frankie Sullivan, franklin.sullivan@unh.edu
* Steve Hagen, shagen@appliedgeosolutions.com
* Ian Cooke, icooke@appliedgeosolutions.com

####License (FreeBSD)

	Copyright (c) 2015, Applied Geosolutions LLC, oss@appliedgeosolutions.com
	All rights reserved.

	Redistribution and use in source and binary forms, with or without
	modification, are permitted provided that the following conditions are met:

	* Redistributions of source code must retain the above copyright notice, this
	  list of conditions and the following disclaimer.

	* Redistributions in binary form must reproduce the above copyright notice,
	  this list of conditions and the following disclaimer in the documentation
	  and/or other materials provided with the distribution.

	THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
	AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
	IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
	DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
	FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
	DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
	SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
	CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
	OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
	OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

####Prerequisite (added by @heromiya)

* PDAL == 1.5.0 (latest version supporting XML pipelines)

