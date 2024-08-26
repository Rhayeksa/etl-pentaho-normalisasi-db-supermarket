# ETL Pentaho Normalisasi Database Supermarket

ETL Pentaho Normalisasi Database Supermarket merupakan project yang berkegiatan untuk melakukan normalisasi database menggunakan software tools ETL Pentaho

## Overview

### Prototipe Design Table Database

![image](./images/prototipe%20design%20table%20database.png)

### Step Transformation ETL Pentaho

![image](./images/step%20transformation%20ETL%20pentaho.png)

### Design Table Database

![image](./images/design%20table%20database.png)

## Goals

- Melakukan normalisasi database pada database supermarket
- Melakukan transformasi database dari file CSV ke Postgresql

## Requirement

- Software ETL Pentaho (recommanded version 9.4.0.0-343)
- Server Database Postgresql (recommanded version 16.3)
- Software DBeaver (recommanded version 24.1.5)

## Penggunaan

1. Clonning atau download repo ini

   url : <https://github.com/Rhayeksa/etl-pentaho-normalisasi-db-supermarket>

2. Buka aplikasi DBeaver

   - buat koneksi baru sesuai dengan database postgresql yang terinstall
     ![image](./images/buat%20koneksi%20baru.png)

   - buat database baru dengan nama db_supermarket dan schema baru dengan nama sch_supermarket

     - database
       ![image](./images/buat%20database%20baru.png)

     - schema
       ![image](./images/buat%20schema%20baru.png)

3. Buka aplikasi ETL Pentaho

   - buka file transformation db_supermarket dan db_supermarket_relational_table
     ![image](./images/buka%20file%20transform%20menggunakan%20etl%20pentaho.png)

   - lakukan penyesuaian koneksi pada database postresql yang terinstall
     ![image](./images/penyesuaian%20koneksi%20db%20postgresql.png)

   - jalankan tranformation db_supermarket
     ![image](./images/run%20transformation%20db_supermarket.png)

   - jalankan tranformation db_supermarket_relational_table
     ![image](./images/run%20transformation%20db_supermarket_relational_table.png)

4. Buka kembali aplikasi DBeaver

   - cek kesesuaian table dan data

     - table dan relasinya
       ![image](./images/cek%20table%20dan%20relasinya.png)

     - data
       ![image](./images/cek%20data%20sebagai%20sample.png)
