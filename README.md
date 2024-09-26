# Belly Button Biodiversity Dashboard

## Overview

This project creates an interactive dashboard that visualizes the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called OTUs, or Operational Taxonomic Units) were present in more than 70% of people, while the rest were relatively rare.

Using the D3.js and Plotly.js libraries, this dashboard allows users to explore the microbial data for each individual in the study by:
- Selecting a test subject ID from a dropdown menu.
- Viewing demographic information for the selected individual.
- Displaying a bar chart of the top 10 OTUs found in the individual.
- Showing a bubble chart with the distribution of all OTUs found in the sample.

## Live Demo
You can view the deployed app [here](https://manahilr701.github.io/belly-button-challenge).

## Features
- **Dropdown menu**: Allows the user to select a test subject ID to explore.
- **Demographic Info panel**: Displays key details about the individual such as age, gender, ethnicity, and location.
- **Bar Chart**: Shows the top 10 bacteria cultures found in the selected individual.
- **Bubble Chart**: Provides a visual representation of all OTU data, including the OTU ID and sample values.

## Dataset
The dataset used in this project is sourced from [Belly Button Biodiversity Dataset](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json).

### Data Fields:
- **names**: List of test subject IDs.
- **metadata**: Demographic information including ethnicity, gender, age, and location for each test subject.
- **samples**: Microbial data for each subject including OTU IDs, sample values, and OTU labels.

## Tools & Technologies Used
- **HTML5 & CSS3**: For building the structure and layout of the web page.
- **Bootstrap 5**: For responsive design and styling.
- **JavaScript (ES6)**: Core programming for interactive behavior.
- **D3.js**: To fetch data and manipulate the DOM.
- **Plotly.js**: For creating the bar and bubble charts.
- **Git & GitHub Pages**: Version control and deployment.

## Project Structure
```bash
|-- belly-button-challenge/
    |-- index.html               # Main HTML file
    |-- static/
        |-- js/
            |-- app.js           # JavaScript file containing the logic for data fetching and chart building
    |-- README.md                # Project documentation
```

## How to Run Locally
Follow these steps to run the project locally on your computer:

### Clone the repository:
```bash
git clone https://github.com/manahilr701/belly-button-challenge.git
```
### Navigate into the project directory:
```bash
cd belly-button-challenge
```
### Open `index.html` in your browser:
Open the `index.html` file directly in your web browser by either double-clicking the file or using a live server extension in a code editor like Visual Studio Code.

## Deployment
This project is deployed using **GitHub Pages**. You can view the live version [here](https://manahilr701.github.io/belly-button-challenge/).

### Steps to Deploy on GitHub Pages:
1. Commit and push all changes to your GitHub repository.
2. Go to your repository settings.
3. Scroll down to the **GitHub Pages** section.
4. Under **Source**, select the branch to deploy from (typically `main` or `master`).
5. Your site will be published at `https://manahilr701.github.io/belly-button-challenge/`.

## Screenshots
### Dashboard Overview
![Dashboard Overview](<img width="1440" alt="Screenshot 2024-09-26 at 2 50 04 PM" src="https://github.com/user-attachments/assets/f9cffbcc-1dba-48f9-a2eb-42332afedca0">)

### Bar Chart
Displays the top 10 bacteria cultures found for the selected individual.

### Bubble Chart
Shows the relative abundance of OTUs found in the sample.

## Credits
- **Data Source**: [Belly Button Biodiversity Dataset](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json)
- **Plotly.js Documentation**: [https://plotly.com/javascript/](https://plotly.com/javascript/)
- **D3.js Documentation**: [https://d3js.org/](https://d3js.org/)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
