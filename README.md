#Project 1 for WAD(543) class

##Submitted by Khaing Thin Zar Sein (6530381)

# Car Market Analytics

Welcome to the Car Market Analytics website! This application is a comprehensive tool for analyzing and visualizing data related to the car market. It allows users to view, highlight, and compare different cars using an intuitive dashboard and charts.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Live Demo](#live-demo)
- [Pages Overview](#pages-overview)
  - [Index Page](#index-page)
  - [Dashboard Page](#dashboard-page)
  - [All Cars Page](#all-cars-page)
  - [Highlighted Cars Page](#highlighted-cars-page)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)


## Introduction

The Car Market Analytics application provides insights into the car market by presenting data in a visually appealing and user-friendly manner. The application offers a dashboard with sample cars, charts, and tables, as well as an "All Cars" page where users can browse all available cars. Users can highlight cars of interest, which are then displayed on a dedicated "Highlighted Cars" page.

## Features

- **Interactive Dashboard:** View sample cars, explore data through tables, and visualize trends with charts.
- **All Cars Page:** Browse and filter through all available cars presented as card components.
- **Highlighting Functionality:** Highlight cars from the dashboard or all cars page, and view them on the highlighted cars page.
- **Data Visualization:** Leverage `Chart.js` to create insightful charts for better data understanding.
- **Responsive Design:** The website is designed to be fully responsive, ensuring a seamless experience across devices.

## Live Demo

Explore the live demo of the Car Market Analytics website:

- [Home Page](https://jue-iroiro.github.io/car-market-analytics/)

## Pages Overview

### Index Page

The index page serves as the landing page of the website, providing navigation to the key features of the application: the Dashboard and the Highlighted Cars pages.

### Dashboard Page

The dashboard page provides a summary of the car market data. It includes:
- **Sample Cars:** Displays the first four cars as examples.
- **Charts:** Various charts generated using `Chart.js` to analyze car data.
- **Table:** A table that presents detailed car information.

### All Cars Page

Accessible via the dashboard, this page presents all the cars in the dataset as Bootstrap card components. Users can browse, filter, and highlight cars from this page.

### Highlighted Cars Page

This page displays all the cars that have been highlighted by the user. It provides a quick reference to the cars of interest and uses useLocalStorage to store persitance data.

## Technology Stack

- **Frontend:**
  - [React](https://reactjs.org/)
  - [Vite](https://vitejs.dev/)
  - [Bootstrap](https://getbootstrap.com/)
  - [Chart.js](https://www.chartjs.org/)
  - [React-Bootstrap](https://react-bootstrap.github.io/)
  - [React-Router-Dom](https://reactrouter.com/)
- **State Management:** `useLocalStorage` from `react-use` for persisting highlighted cars.
- **Deployment:** Hosted on GitHub Pages.

## Installation

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/jue-iroiro/car-market-analytics.git
   ```
2. Navigate to the project directory:
   ```bash
   cd car-market-analytics
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Usage

- **Dashboard:** Start by exploring the dashboard to view sample cars, analyze data through charts, and browse the table.
- **All Cars:** Head to the "All Cars" page to view all available cars. You can highlight and unhighlight cars from this page.
- **Highlighted Cars:** Visit the "Highlighted Cars" page to see all the cars you've highlighted.



![1](https://github.com/user-attachments/assets/8fa6e3c2-34a8-4835-b887-cbf6adeebe00)
![2](https://github.com/user-attachments/assets/0b849369-60c2-47da-9f25-e070bcad77c0)
![3](https://github.com/user-attachments/assets/730d95c9-704b-4aba-97bc-8e708549ef80)
![4](https://github.com/user-attachments/assets/dde961ac-58a7-4ad4-97c4-59cc162ccb9c)
![5](https://github.com/user-attachments/assets/4814a0a1-b246-45e3-ac7b-81e9253b6730)
![6](https://github.com/user-attachments/assets/d380ab37-0470-4baa-baf3-06c995b24702)
![7](https://github.com/user-attachments/assets/5e2ad94f-71e4-4ca7-9b19-327b01d9d75c)
![8](https://github.com/user-attachments/assets/209cbb25-e903-4c7d-aaf1-e30a0c3932c2)
![9](https://github.com/user-attachments/assets/72eb3fbf-6dba-499c-94f4-edeec519b803)
![10](https://github.com/user-attachments/assets/414d67ff-7194-405f-8a5c-98087c1fde95)
