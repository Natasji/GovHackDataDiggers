# Dataset resources

Challenge: https://hackerspace.govhack.org/challenges/ai_applications_using_open_road_crash_data

## Datasets

### Victoria Road Crash Data

**Accident**

    accident no, node id, date, time, collision with, day of week, severity, type of road ROAD_GEOMETRY(e.g. intersection & highway), speed zone, no of persons inj...

**Accident event**

    accident no, event type (collision, rollover...)

**Accident location**

   accident no, node id, road type (street/road/highway...), road type int (?)

**ATMOSPHERIC CONDITION**

    accident no, atmosph cond (clear, wind, rain, dust etc.)

**Node**

   accident no, node id, LATITUDE, LONGITUDE, POSTCODE

**Person**

    accident no, age (*can be linked to areas eg schools... ?*), inj level, road user type (drivers/passengers...), taken hospital (*severity*)

**Road surface cond**

    accident no, surface cond (dry, wet, muddy)

**SUB_DCA**

    accident no, road type (road curved, iintersection...)

### Speed sign

    id, LATITUDE, LONGITUDE, sign size, side of road (left, right), speed, road type (street/drive...), sign type (standard/school zone...), time effected

### Traffic count location

    road type (intersection...), ??

### Traffic lights

    site no, site type (INT, POS, FLASH...??), LATITUDE, LONGITUDE

### Traffic volume

    line coordinates can't convert to csv now

### Turning movement summaries

    a survey form not useful??

### Speed zones August 2024

    area coordinates can't convert to csv now



## Produced datasets

### location link

    node id, site no, LATITUDE, LONGITUDE, POSTCODE, num of incidents (at this location)

### merged dataset

    join everything by accident no or location
