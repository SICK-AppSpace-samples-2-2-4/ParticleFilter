## ParticleFilter
Applying particle filter on scans read from a file
### Description
Scan data from file in resources is retrieved and filtered with the particle
filter. The filtered scan is transformed into a point cloud and sent to the
viewer. Additionally the original scan and the filtered scan are compared and
changes between both scans are printed to illustrate the operation of the
particle filter.
### How to run
Starting this sample is possible either by running the app (F5) or
debugging (F7+F10). Output is printed to the console and the transformed
point cloud can be seen on the viewer in the web page. The playback stops
after the last scan in the file. To replay, the sample must be restarted.
To run this sample, a device with AppEngine >= 2.5.0 is required.
### Implementation
To run with real device data, the file provider has to be exchanged with the
appropriate scan provider.

### Topics
Algorithm, Scan, Filtering, Sample, SICK-AppSpace