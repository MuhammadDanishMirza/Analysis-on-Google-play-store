# Google Playstore Apps Analysis

## Author
Muhammad Danish Mirza  
Email: [danimirza55555@gmail.com](mailto:danimirza55555@gmail.com)

## Dataset Description
The dataset is downloaded from the following [link](https://www.kaggle.com/datasets/lava18/google-play-store-apps/).

## Context
While many public datasets (on Kaggle and the like) provide Apple App Store data, there are not many counterpart datasets available for Google Play Store apps anywhere on the web. On digging deeper, the author found out that iTunes App Store page deploys a nicely indexed appendix-like structure to allow for simple and easy web scraping. On the other hand, Google Play Store uses sophisticated modern-day techniques (like dynamic page load) using JQuery making scraping more challenging.

## Content
Each app (row) has values for category, rating, size, and more.

## Acknowledgements
This information is scraped from the Google Play Store. This app information would not be available without it.

## Features
The dataset contains the following features:

| Column Name       | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| App               | The name of the application.                                                |
| Category          | The category to which the app belongs (e.g., ART_AND_DESIGN, AUTO_AND_VEHICLES, BEAUTY). |
| Rating            | The average user rating of the app (on a scale from 1 to 5).               |
| Reviews           | The total number of user reviews for the app.                              |
| Size              | The size of the app (e.g., in megabytes).                                 |
| Installs          | The number of times the app has been installed (e.g., "10,000+", "1,000,000+"). |
| Type              | Indicates whether the app is free or paid.                                 |
| Price             | The price of the app (if it is a paid app).                               |
| Content Rating    | The audience the app is suitable for (e.g., Everyone, Teen).              |
| Genres            | The genre(s) of the app, which may include multiple genres separated by semicolons. |
| Last Updated      | The date when the app was last updated.                                   |
| Current Ver       | The current version of the app.                                           |
| Android Ver       | The minimum Android version required to run the app.                      |

## Libraries Used
The following libraries are used in this Jupyter Notebook:

- **pandas**: For data manipulation and analysis
- **numpy**: For numerical operations
- **matplotlib.pyplot**: For data visualization
- **seaborn**: For advanced data visualization

You can install these libraries using 
```bash
pip install numpy pandas matplotlib seaborn
 
