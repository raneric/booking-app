# Actions badges
###   **API CI action badge**  
   [![booking-api-app-build](https://github.com/raneric/booking-app/actions/workflows/api-ci.yml/badge.svg)](https://github.com/raneric/booking-app/actions/workflows/api-ci.yml)
###   **Front CI action badge**   
   [![booking-react-app-build](https://github.com/raneric/booking-app/actions/workflows/front-ci.yml/badge.svg)](https://github.com/raneric/booking-app/actions/workflows/front-ci.yml)
###   **Auto-dependency check badge**   
   [![auto-deps-check](https://github.com/raneric/booking-app/actions/workflows/auto-deps-check.yml/badge.svg)](https://github.com/raneric/booking-app/actions/workflows/auto-deps-check.yml)
# Setup Instructions

Follow these steps to set up and run the project:

1. **Install dependencies**  
   Run the following commands in both the `client` and `server` directories to install the necessary dependencies:

   ```bash
   cd ingedata-dev-test/client
   npm install
   ```

   ```bash
   cd ../server
   npm install
   ```

2. **Run the frontend and the backend**  
   The `docker-compose.yml` file, start two services `client` and `server` which run the react app and the node.js API:

   ```bash
   cd ..
   docker compose build
   docker compose up
   ```
