# VGM API

The container weight is an important piece of information for many parties in the container export chain. Instead of being forwarded point to point, it can now be made available in a central API.

| This documentation applies to v1 of this API | 
| -------- |


## Purpose of this API

Since July 1st 2016, the weight of every container loaded on board of a SOLAS ship needs to be verified. Verification can be done either through **actual weighing** (placing the container on an officially calibrated scale), or through **calculation** (container tarra weight + weight of the goods -- this requires a special permission).

The **shipper** provides this information to the **ship's agent**. The agent then passes it on to the **carrier**, because the carrier needs to balance the vessel, and to the **terminal**, because the terminal is not allowed to load the container otherwise. Several other parties could also benefit from having the weight in their digital files, e.g. CMR documents.

The first version of this API provides the VGM of a container that has been weighed. In the next phase, the API will also provide container tarra weights so as to support the calculation method. 

Currently, the NxtPort platform processes only new VERMAS submissions (not cancellations and updates).

## Contents of this repository
  
```
/
  /doc            technical documentation about the use of this API
  /src            sample source code to call this API 
  /data           sample data (requests, responses ...)
```

## More information

More information about this API is available on
* [the NxtPort website](https://www.nxtport.eu)
* [the NxtPort market](https://market.nxtport.eu)