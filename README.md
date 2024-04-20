# Cloud Data Warehouse for Bike Share Data Analytics

## Project Introduction

The goal of this project is to develop a data warehouse solution utilizing Azure Synapse Analytics. The focus is on a 
bike-sharing program in Chicago that enables data-driven decision-making and analytical capabilities.

## Project Overview

Divvy is a bike-sharing program in Chicago, where users can pick up and drop off bikes at various stations across the 
city. The data collected from the program includes ride information and associated user accounts. This project aims to 
leverage this data to create a cloud data warehouse that facilitates effective data analysis.

### Data Model

The data model includes the following entities:
- **Rider**: Information about the user of the bike service.
- **Account**: Details about the user's account.
- **Payment**: Records of payments made by the users.
- **Trip**: Trip details including start and end times, and locations.
- **Station**: Location details of bike stations.

### Business Outcomes

The analytical outcomes this project aims to achieve are:
- Insights into daily and monthly usage patterns.
- Understanding of rider behavior in terms of service usage.
- Analysis of payment records to monitor revenue streams.

### Queries

The warehouse supports complex analytical queries to gain insights such as:
- Usage patterns by time of day and day of the week.
- Duration and distance of trips.
- Revenue analysis based on membership and casual rider payments.

## Technologies Used

- **Azure Synapse Analytics**: For building and managing the data warehouse.
- **Azure Data Lake Storage**: To store the raw data.