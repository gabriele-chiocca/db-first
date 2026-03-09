| Nome colonna             | Tipo di dato | Attributi                       | Indice      |
| ------------------------ | ------------ | ------------------------------- | ----------- |
| id                       | BIGINT       | UNIQUE, NOT NULL, AUTOINCREMENT | PRIMARY KEY |
| car_name                 | VARCHAR(40)  | NOT NULL                        | INDEX       |
| car_type                 | VARCHAR(40)  | NULL                            | --          |
| car_price                | DECIMAL(7,4) | NOT NULL                        | --          |
| car_released_year        | YEAR         | NULL                            | --          |
| car_image                | VARCHAR(255) | NULL                            | --          |
| place_of_production      | VARCHAR(40)  | NULL                            | --          |
| car_summary              | VARCHAR(200) | NULL                            | --          |
| car_complete_description | TEXT         | NULL                            | --          |
