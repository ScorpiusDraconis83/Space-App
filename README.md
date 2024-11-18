# 🚀 Space-App: Real-Time Space Exploration Dashboard

An interactive dashboard to explore global space exploration data in real time, featuring **automated updates every 6 hours**. It offers a comprehensive view of space activities, from historical milestones to upcoming launches.

You can access the live version of the application [here](https://spacexploration-2t723npiha-uc.a.run.app/).

For a quick demonstration of the app's features, check out the video below:

[![Space App Video](https://img.youtube.com/vi/2rO7on8kaW4/0.jpg)](https://www.youtube.com/watch?v=2rO7on8kaW4)

## ✨ Features
- **Earth Globe**: A rotating 3D Earth globe visualizing the number of space launches by country since the inception of space exploration.
- **Historical Timeline**: A constellation-shaped graph representing significant historical events in space exploration. Clicking on a node reveals a description and image related to the event.
- **Launch Statistics**: Displays trends with dynamic charts.
- **Automated Updates**: Data refreshed every 6 hours through a cloud-based pipeline (Google Cloud Platform).

## 🛠️ Technical Stack
- **Languages:** Python
- **Frameworks:** Dash, Flask
- **Libraries:** Plotly, Pandas
- **Cloud Services:** Google Cloud Run, Google Cloud Scheduler, Google Cloud Storage

## 🌍 Web Scraping
Data is scraped from various sources using Python libraries like `requests` and `BeautifulSoup`. The scraping scripts are hosted in separate repositories:
  - [Wikipedia Space Scraper](https://github.com/Tanguy9862/Wikipedia_Space_Scraper)
  - [Next Launch Scraper](https://github.com/Tanguy9862/Next-Launch-Scraper)
  - [NextSpaceFlight Scraper](https://github.com/Tanguy9862/NextSpaceFlight-Scrapper)

## License

This project is licensed under the Apache-2.0 License. You are free to use, modify, and distribute the code, provided that you attribute the work to the original author.

## Copyright

© 2024 Tanguy Surowiec. All rights reserved.
