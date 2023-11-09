# Structure table db

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

|                     |     used_cars      |                                       |
| :------------------ | :----------------: | ------------------------------------: |
| id                  |        INT         | AUTO INCREMENT,NOT NULL - PRIMARY KEY |
| brand               |    VARCHAR(20)     |                              NOT-NULL |
| model               |    VARCHAR(20)     |                              NOT-NULL |
| mileage             |     MEDIUMINT      |                              NOT-NULL |
| year_of_manufacture |        YEAR        |                                  NULL |
| vin                 |    VARCHAR(17)     |                      NOT-NULL, UNIQUE |
| license_plate       |    VARCHAR(30)     |                      NOT-NULL, UNIQUE |
| color               |    VARCHAR(30)     |                                  NULL |
| price               |     FLOAT(6,2)     |                              NOT-NULL |
| doors               |      TINYINT       |                                  NULL |
| trasmission         |    VARCHAR(20)     |                              NOT-NULL |
| motor_fuel          |    VARCHAR(20)     |                              NOT-NULL |
| ownership_history   |     VARCHAR()      |                                  NULL |
| title_status        |     VARCHAR()      |                                  NULL |
| maintenance_records |     VARCHAR()      |                                  NULL |
| safety_features     |     VARCHAR()      |                              NOT-NULL |
| condition           |     VARCHAR()      |                                  NULL |
| optional            |     VARCHAR()      |                                  NULL |
| air_conditioning    | TINYINT DEFAULT(0) |                                  NULL |
| width               |  TINYINT UNSIGNED  |                                  NULL |
| length              |  TINYINT UNSIGNED  |                                  NULL |
