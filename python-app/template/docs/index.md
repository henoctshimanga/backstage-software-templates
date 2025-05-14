# Documentation for ${{values.app_name}}

## Overview
This application provides two primary endpoints:
- `/api/v1/info`: Used for retrieving general metadata and details about the application.
- `/api/v1/healthz`: Used for health checks, ensuring that the application is running properly.

Further context and detailed specifications for each endpoint will be added.

## How to Access the Application
To interact with the application, use the following URL:
```plaintext
${{values.app_name}}-${{values.app_env}}.test.com/api/v1/info
