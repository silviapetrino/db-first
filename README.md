
## used_cars

| id | INT - AUTO INCREMENT- PRIMARY KEY NOTNULL UNIQUE |
|-----------|-----------|
| brand | VARCHAR(25) NOTNULL |
| model| VARCHAR(50) NOTNULL |
| license_plate| VARCHAR(10) NOTNULL UNIQUE |
| mileage | MEDIUMINT NOTNULL  |
| year_registration | YEAR NOTNULL   |
| doors | TINYINT NULL   |
| seats | TINYINT NULL  |
| color| VARCHAR(20) NULL  |
| fuel_type | VARCHAR(20) NULL   |
| horsepower |SMALLINT NULL   |
| engine_displacement | SMALLINT NULL   |
| interior_color | VARCHAR(30) NULL  |
| gearbox | VARCHAR(15) NULL   |
| air_conditioning | CHAR(2) NULL   |
| bluethoot | CHAR(2) NULL   |
| radio | CHAR(2) NULL   |

