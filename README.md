# Demo app for embedding Superset dashboards

This is a simple demo app for testing superset embedded dashboards.

## Setting up the environment

Create a file named `.env` with the following environment variables:

```
URL_AUTH=http://localhost:8088/api/v1/security/login
URL_GUEST_TOKEN=http://localhost:8088/api/v1/security/guest_token/
USERNAME=<USERNAME>
FIRST_NAMER=<FIRST_NAMER>
LAST_NAME=<LAST_NAME>
DASHBOARD_ID=<DASHBOARD_ID>
SUPERSET_DOMAIN=http://localhost:8088/
```



. Run the application

```bash
 run uvicorn main:app --reload
```
>python -m uvicorn main:app --reload