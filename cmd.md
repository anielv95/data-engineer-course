```docker run -it -e POSTGRES_USER="write the right user" -e POSTGRES_PASSWORD="write the right password" -e POSTGRES_DB="ny-taxi" -v ${pwd}:/var/lib/postgresql/data -p 5432:5432 postgres:17.0```

```pip install pgcli```

```pgcli --help```

```pgcli -h <particular host> -p <particular port> -u <particular user> -d <database name>```

```https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2021-01.parquet```

minute 11:45