# Vue-develop

## Setup and run.

1. Clone this repository.
2. Run docker compose.
  ```
  docker-compose up
  ```

### Customize configuration

Copy .env.example to .env file.

1. VUE_UI_PORT=8000  
    The port used by the Vue CLI UI.
2. APP_PORT_RANGE=8081-8089:8081-8089  
    The port used by the application.
3. TZ=UTC  
    Container timezone.