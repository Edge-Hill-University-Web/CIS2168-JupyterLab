# CIS2168-JupyterLab
Docker Based Jupyter Lab Environment configured for CIS2168 Data Driven Design 

## How to deploy the container

Ensure you have docker installed on your machine. 

Open up terminal or command prompt and navigate to the directory containing the `docker-compose.yml` and enter the following command. 
 
_Note: This will build the contianer in "detached" mode._

```
docker compose up -d
```

    

Open up a web browser such as Chrome or Firefox and input the following URL

```
127.0.0.1:2168
```

This will take point you to the exposed `2168` port from the contianer you have just deployed. 

Upon first use of the container you will be required to input a `password/token` this is *2168*
