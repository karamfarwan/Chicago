# Traffic Crashes - Crashes Column Description

| Column Name           | Description                                                                                                                                  |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| CRASH_RECORD_ID        | Unique identifier for the entire crash report                                                                                                |
| CRASH_DATE             | Date and time of the crash                                                                                                                   |
| CRASH_DATE_EST_I             | Crash date estimated by desk officer or reporting party (only used in cases where crash is reported at police station days after the crash)  |
| POSTED_SPEED_LIMIT     | Posted speed limit at the crash location                                                                                                     |
| TRAFFIC_CONTROL_DEVICE | Type of traffic control device at the crash location (e.g., traffic signal, stop sign)                                                       |
| DEVICE_CONDITION       | Condition of the traffic control device (e.g., functional, damaged)                                                                          |
| WEATHER_CONDITION      | Weather conditions at the time of the crash (e.g., clear, rainy, snowy)                                                                      |
| LIGHTING_CONDITION     | Lighting conditions at the time of the crash (e.g., daylight, dark)                                                                          |
| FIRST_CRASH_TYPE       | Type of the first collision in the crash (e.g., rear-end, angle)                                                                             |
| TRAFFICWAY_TYPE        | Type of trafficway where the crash occurred (e.g., local street, expressway)                                                                 |
| LANE_CNT               | Number of lanes at the crash location                                                                                                        |
| ALIGNMENT              | Street alignment at the crash location (e.g., straight, curve)                                                                               |
| ROADWAY_SURFACE_COND   | Roadway surface condition at the crash location (e.g., dry, wet)                                                                             |
| ROAD_DEFECT            | Defects or issues with the road (e.g., pothole, rut)                                                                                         |
| REPORT_TYPE            | Type of crash report (e.g., on-scene, supplemental)                                                                                          |
| CRASH_TYPE             | Type of crash (e.g., injury, property damage)                                                                                                |
| INTERSECTION_RELATED_I | Indicator if the crash occurred at an intersection (Y/N)                                                                                     |
| NOT_RIGHT_OF_WAY_I     | Indicator if the unit did not have the right of way (Y/N)                                                                                    |
| HIT_AND_RUN_I          | Indicator if the crash was a hit-and-run (Y/N)                                                                                               |
| DAMAGE                 | Extent of damage (e.g., functional, major damage)                                                                                            |
| DATE_POLICE_NOTIFIED   | Date and time when police were notified of the crash                                                                                         |
| PRIM_CONTRIBUTORY_CAUSE| Primary contributing cause of the crash (e.g., speeding, failure to yield)                                                                   |
| SEC_CONTRIBUTORY_CAUSE | Secondary contributing cause of the crash (if applicable)                                                                                    |
| STREET_NO              | Street number where the crash occurred                                                                                                       |
| STREET_DIRECTION       | Direction of the street where the crash occurred (e.g., north, south)                                                                        |
| STREET_NAME            | Street name where the crash occurred                                                                                                         |
| BEAT_OF_OCCURRENCE     | Police beat where the crash occurred                                                                                                         |
| PHOTOS_TAKEN_I         | Indicator if photos were taken at the scene (Y/N)                                                                                            |
| STATEMENTS_TAKEN_I     | Indicator if statements were taken at the scene (Y/N)                                                                                        |
| DOORING_I              | Indicator if the crash involved a dooring incident (Y/N)                                                                                     |
| WORK_ZONE_I            | Indicator if the crash occurred in a work zone (Y/N)                                                                                         |
| WORK_ZONE_TYPE         | Type of work zone (if applicable)                                                                                                            |
| WORKERS_PRESENT_I      | Indicator if workers were present at the scene (Y/N)                                                                                         |
| NUM_UNITS              | Number of units (vehicles) involved in the crash                                                                                             |
| MOST_SEVERE_INJURY     | Most severe injury sustained by any person involved in the crash (e.g., fatal, non-incapacitating)                                           |
| INJURIES_TOTAL         | Total number of injuries in the crash                                                                                                        |
| INJURIES_FATAL         | Number of fatal injuries in the crash                                                                                                        |
| INJURIES_INCAPACITATING| Number of incapacitating injuries in the crash                                                                                               |
| INJURIES_NON_INCAPACITATING| Number of non-incapacitating injuries in the crash                                                                                           |
| INJURIES_REPORTED_NOT_EVIDENT| Number of injuries reported but not evident at the scene (e.g., internal injuries)                                                           |
| INJURIES_NO_INDICATION  | Number of injuries with no indication of severity (e.g., minor injuries)                                                                     |
| INJURIES_UNKNOWN       | Number of injuries with unknown severity                                                                                                     |
| CRASH_HOUR             | Hour of the crash occurrence                                                                                                                | 
| CRASH_MONTH             | Month of the crash occurrence                                                                                                                | 
| LATITUDE             | The crash location latitude                                                                                                                 |
| LONGITUDE             | The crash location longitude                                                                                                                |
| LOCATION             | The crash location as Point Data Structure                                                                                                                 |

# Traffic Crashes - Vehicles Column Description

| Column Name           | Description                                                                                     |
|-----------------------|-------------------------------------------------------------------------------------------------|
| CRASH_UNIT_ID         | Unique identifier for each unit (vehicle, pedestrian, cyclist) involved in the crash            |
| CRASH_RECORD_ID       | Unique identifier for the entire crash report                                                    |
| CRASH_DATE            | Date and time of the crash                                                                       |
| UNIT_NO               | Sequential number assigned to each unit within a crash                                           |
| UNIT_TYPE             | Type of unit (e.g., motor vehicle, bicycle, pedestrian)                                           |
| NUM_PASSENGERS        | Number of passengers in the unit (if applicable)                                                  |
| VEHICLE_ID            | Unique identifier for the vehicle                                                                |
| CMRC_VEH_I            | Commercial vehicle indicator (Y/N)                                                               |
| MAKE                  | Make of the vehicle                                                                              |
| MODEL                 | Model of the vehicle                                                                             |
| LIC_PLATE_STATE       | State where the license plate is registered                                                       |
| VEHICLE_YEAR          | Year of the vehicle                                                                               |
| VEHICLE_DEFECT        | Defects or issues with the vehicle (e.g., brakes, lights)                                         |
| VEHICLE_TYPE          | Type of vehicle (e.g., passenger car, motorcycle, truck)                                          |
| VEHICLE_USE           | Use of the vehicle (e.g., personal, commercial)                                                   |
| TRAVEL_DIRECTION      | Direction of travel (e.g., northbound, southbound)                                                 |
| MANEUVER              | Maneuver performed by the unit (e.g., turning left, going straight)                                |
| TOWED_I               | Indicator if the vehicle was towed (Y/N)                                                          |
| TOWED_TO              | Location to which the unit was towed, if relevant                                                          |
| TOWED_BY              | Entity that towed the unit, if relevant                                                          |
| FIRE_I                | Indicator if the vehicle caught fire (Y/N)                                                         |
| OCCUPANT_CNT          | Number of occupants in the vehicle (if applicable)                                                |
| EXCEED_SPEED_LIMIT_I  | Indicator if the unit exceeded the speed limit (Y/N)                                               |
| FIRST_CONTACT_POINT   | Point of initial contact between units (e.g., front, rear)                                         |



# Traffic Crashes - People Column Description

| Column Name           | Description                                                                                     |
|-----------------------|-------------------------------------------------------------------------------------------------|
| PERSON_ID              | Unique identifier for a person involved in the crash (if applicable)                              |
| PERSON_TYPE            | Type of person (e.g., driver, passenger, pedestrian, cyclist)                                      |
| CRASH_RECORD_ID        | Unique identifier for the entire crash report                                                      |
| VEHICLE_ID             | Unique identifier for the vehicle involved in the crash (if applicable)                             |
| CRASH_DATE             | Date and time of the crash                                                                       |
| SEAT_NO                | Seat number (if applicable)                                                                       |
| CITY                   | City where the crash occurred                                                                     |
| STATE                  | State where the crash occurred                                                                    |
| ZIPCODE                | Zip code where the crash occurred                                                                 |
| SEX                    | Gender of the person involved (if applicable)                                                       |
| AGE                    | Age of the person involved (if applicable)                                                           |
| DRIVERS_LICENSE_STATE  | State where the driver's license is registered (if applicable)                                      |
| DRIVERS_LICENSE_CLASS  | Class of the driver's license (if applicable)                                                        |
| SAFETY_EQUIPMENT       | Safety equipment used by the person (e.g., seatbelt, helmet)                                         |
| AIRBAG_DEPLOYED        | Indicator if the airbag deployed (Y/N)                                                               |
| EJECTION               | Indicator if the person was ejected from the vehicle (Y/N)                                           |
| INJURY_CLASSIFICATION  | Classification of injury (e.g., fatal, non-incapacitating)                                            |
| HOSPITAL               | Hospital where the person was taken (if applicable)                                                  |
| EMS_AGENCY             | Emergency Medical Services agency that responded (if applicable)                                      |
| EMS_RUN_NO             | Run number assigned by EMS (if applicable)                                                            |
| DRIVER_ACTION          | Action taken by the driver (e.g., failed to yield, stopped)                                           |
| DRIVER_VISION          | Driver's vision condition (e.g., obstructed, not obstructed)                                          |
| PHYSICAL_CONDITION     | Physical condition of the driver (e.g., normal, impaired)                                             |
| PEDPEDAL_ACTION        | Action taken by pedestrian or cyclist (if applicable)                                                 |
| PEDPEDAL_VISIBILITY    | Visibility condition for pedestrian or cyclist (e.g., daylight, dark)                                 |
| PEDPEDAL_LOCATION      | Location of pedestrian or cyclist at the time of the crash                                            |

> Note that all location data are in EPSG:4326 (WGS 84 -- WGS84 - World Geodetic System 1984, used in GPS)

> Note that other columns may exist in the datasets, however, we were unable to find relevant information. Consider each column independently and try to grasp the purpose from the stored data.
