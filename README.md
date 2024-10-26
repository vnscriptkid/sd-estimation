# sd-estimation

## Conversion
- 1 GB ~ 10^9 bytes
- 1 char ~ 1 byte
- 1 TB (terabytes) = 10^3 GB = 10^6 MB

## WPS / RPS

| **Database**          | **Writes per Second**                                 | **Reads per Second**                                  |
|-----------------------|-------------------------------------------------------|-------------------------------------------------------|
| **PostgreSQL**        | Hundreds to a few thousand writes/sec                 | Thousands to tens of thousands reads/sec              |
| **Redis**             | Hundreds of thousands to over a million writes/sec    | Hundreds of thousands to over a million reads/sec     |
| **MySQL**             | Hundreds to a few thousand writes/sec                 | Thousands to tens of thousands reads/sec              |
| **MongoDB**           | Thousands to tens of thousands writes/sec             | Tens of thousands to hundreds of thousands reads/sec  |
| **Apache Cassandra**  | Thousands to tens of thousands writes/sec per node    | Thousands to tens of thousands reads/sec per node     |
