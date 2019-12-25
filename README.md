# nopCommerce
## nopCommerce & docker-compose

I have starting to use nopCommerce.
Nice webshop, but nopCommerce hasn't normal documentation of how to work with Docker and docker-compose. I created little yml with the general setting, you can use in you works or tests

If you installed docker and docker-compose
you can run as a demon
```bash
docker-compose up -d
```

look at status
```bash
docker ps
```
you must see, something like
```
ae836036d5f6        nopcommerceteam/nopcommerce      "dotnet Nop.Web.dll"     40 minutes ago      Up 38 minutes (healthy)   0.0.0.0:80->80/tcp                               nopcommerce_nopcommerce_1
9ba1078a9d61        mcr.microsoft.com/mssql/server   "/opt/mssql/bin/perm…"   40 minutes ago      Up 40 minutes (healthy)   0.0.0.0:1433->1433/tcp                           nopcommerce_mssql_1
```

for stop
```bash
docker-compose down
```
