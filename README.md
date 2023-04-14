# BCGOV Simple Map Kit (SMK) - Customized Map Application

This repository contains a customized map application built using the [BCGOV Simple Map Kit (SMK)](https://github.com/bcgov/smk) framework. The map displays the following layers:

- Special Protection Areas - All - Colour Filled (from DataBC Layers)
- Forest Development Units (1417) (from WMS layers)

As a bonus, the map also includes an additional layer:

- BC Environmental Monitoring Location Groups

## Requirements

To run this application, you will need:

- An ESRI Developer API key. You can obtain one from the [ArcGIS Developer Dashboard](https://developers.arcgis.com/documentation/mapping-apis-and-services/security/api-keys/).

## How to use

1. Clone this repository to your local machine:
https://github.com/AshimaAdya/BCGov-SMK-App.git

2. Navigate to the project folder:
cd <repository-folder>

3. Replace the placeholder `<your-api-key>` in the `smk-config.json` file with your ESRI Developer API key.

4. To view the customized map locally, you can use a local web server, such as http-server. Install it globally with the following command (you need to have Node.js installed):
npm install -g http-server

5. Start the local web server in the project folder:http-server

6. Open your web browser and navigate to the address provided by the local web server (usually `http://localhost:8080`).

You should now see the customized map with the specified layers.

## Screenshots

Please find the screenshots of the customized map in the `screenshots` folder.
![Screenshot 1](screenshots/screenshot1.png)
![Screenshot 2](screenshots/screenshot2.png)
![Screenshot 3](screenshots/screenshot3.png)



