## Postal Code Story at BigCo, Inc.

We keep a validation table of postal codes. This is used by lots of other teams/services.

The data we keep includes the postal code, the city, and the state/province, related to that code.

Typical work includes returning one or more codes based on filters (state/province, city). The service also supports entering a postalcode value (e.g. 12345) and getting a true/false back to indicate whether that code exists in the system.

Periodically, the data file that holds all the postal code information is replaced with an upated version of the data.


