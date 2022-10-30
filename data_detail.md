## Data detail
```
idves – ship ID
datetimes – timestamp UTC
idinf – coordinate source ID
latitude – latitude in decimal format
longitude – longitude in decimal format
region – catching subzone
course – course (degrees)
velocity – velocity (knots)
trawl - fishing gear
total_ton – daily walleye pollock catch by the respective ship in the respective region (tonnes)
science - (0/1) scientific/commercial trawling.
```

## Task setting

We need to develop an algorithm that predicts walleye pollock catch in tonnes as for a certain date for each ship log record. If a ship was in the navigation phase (did not fish), the catch for such records should amount to 0. Moreover, trawling may be scientific and commercial. Scientific trawling is conducted uniformly, along a certain trajectory, with a view to detect fish locations. Scientific trawling on the map is shown in below figure.

![](https://n-ws-f21jf.s3pd02.sbercloud.ru/b-ws-f21jf-ny6/AI4Sea/jpg/science.jpg)

Commercial trawling is conducted where acoustic surveys show the highest amounts of fish. Commercial trawling is shown in below figure.
![](https://n-ws-f21jf.s3pd02.sbercloud.ru/b-ws-f21jf-ny6/AI4Sea/jpg/fisihing.jpg)


