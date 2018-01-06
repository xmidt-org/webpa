# webpa

Webpa is a combination of a server and client that provide a simple interface to access the TR-181 objects on an RDK device.  Webpa leverages xmidt for the connection to the RDK device.

# tl;dr summary

Webpa is a very simple micro service and client that provides a REST interface to access the TR-181 data model on an RDK device.

# the webpa server

### [tr1d1um](https://github.com/Comcast/tr1d1um)

Tr1d1um provides the RESTful object model representation translation layer.

[![Build Status](https://travis-ci.org/Comcast/tr1d1um.svg?branch=master)](https://travis-ci.org/Comcast/tr1d1um) 
[![codecov.io](http://codecov.io/github/Comcast/tr1d1um/coverage.svg?branch=master)](http://codecov.io/github/Comcast/tr1d1um?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/Comcast/tr1d1um)](https://goreportcard.com/report/github.com/Comcast/tr1d1um)
[![Apache V2 License](http://img.shields.io/badge/license-Apache%20V2-blue.svg)](https://github.com/Comcast/tr1d1um/blob/master/LICENSE)

# the webpa client

### [parodus2ccsp](https://github.com/Comcast/parodus2ccsp)

parodus2ccsp provides the WRP handling and request mapping to the CCSP bus.

[![Build Status](https://travis-ci.org/Comcast/parodus2ccsp.svg?branch=master)](https://travis-ci.org/Comcast/parodus2ccsp)
[![codecov.io](http://codecov.io/github/Comcast/parodus2ccsp/coverage.svg?branch=master)](http://codecov.io/github/Comcast/parodus2ccsp?branch=master)
[![Coverity](https://img.shields.io/coverity/scan/xxx.svg)](https://scan.coverity.com/projects/comcast-parodusxxx)
[![Apache V2 License](http://img.shields.io/badge/license-Apache%20V2-blue.svg)](https://github.com/Comcast/parodus2ccsp/blob/master/LICENSE)
