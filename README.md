# fukuoka-city

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web application that visualizes crowdsourced infectious disease symptom reports across Japan on an interactive map, using open data from the "Warning" app.

## Demo

[Warning Map](https://code4fukui.github.io/fukuoka-city/warnning.html)

## Features

-   **Nationwide Map:** Displays the latest daily symptom report data from the "Warning" crowdsourcing app on an interactive map of Japan.
-   **Severity Indicators:** Uses color-coded markers to indicate the number of reports at each location:
    -   🔴 Red: More than 10 reports
    -   🟡 Yellow: 1 to 10 reports
    -   🔵 Blue: 0 reports
-   **Detailed Popups:** Click on a marker to view a breakdown of reported symptoms (sore throat, cough, fever, runny nose) and the report date for that location.
-   **Automatic Zoom:** The map automatically adjusts its view to fit all locations with available data for the most recent day.

## How to Use

To run this project locally, simply open the `warnning.html` file in a web browser. No web server or build steps are required.

## Data

This project uses a snapshot of data from the "Infectious Disease Outbreak Warning App 'Warning' Crowd Data" dataset, which is included in this repository as `warnning.csv`.

The original open dataset is available at: [https://ckan.open-governmentdata.org/dataset/2c830d40-a4f1-4335-9d05-eeaa18b765f3](https://ckan.open-governmentdata.org/dataset/2c830d40-a4f1-4335-9d05-eeaa18b765f3)

## License

MIT License — see [LICENSE](LICENSE).