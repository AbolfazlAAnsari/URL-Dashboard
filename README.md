# URL Dashboard Project

This project aims to create a link-shortening system with a dashboard that displays statistics. It allows users to create shortened links and track their usage. The project is implemented using a SQL Server database and can be developed using any programming language that supports SQL Server communication.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Dashboard Information](#dashboard-information)
- [Steps](#steps)
- [Detail](#detail)

## Introduction

The URL Dashboard project provides a link shortening functionality along with a dashboard to monitor link usage. The main objectives of the project are:

- Generate and store shortened links for long URLs.
- Retrieve the original URL by providing the shortened link.
- Track the number of referrals and the creation dates of the links.
- Implement a dashboard to display charts and information related to link usage.

## Requirements

The project has the following requirements:

- Creation of Shortened Links: The system should generate a new random string of 6 characters to shorten a long URL. If the link has already been shortened, the previous value should be returned.

- Retrieval of Original Links: Given a shortened link, the system should return the corresponding original link. If the link is not registered in the system, an error should be thrown.

- Functionality and Concepts: The project should utilize at least two functions, initiators, processes, and concepts covered during the term.

- Link Expiration: Any link that hasn't been referred to within a week should expire to reduce storage size.

## Dashboard Information

The dashboard provides the following information:

- Charts: Displaying the number of newly registered links and the number of referrals to shortened links per day.

- Top Referrals: Showing the top 3 links that have received the most referrals.

- Mapping Details: Displaying all mappings in the system along with the time remaining until expiration and the number of referrals made.

## Steps

The project implementation includes the following steps:

ERD Diagram Detecting Entities, Relations, and Attributes

Connecting to SQL Server

Database Schema

Database Initialization

Trigger Definition

Link Creation

Link Reference

Link Expiration(links older than 7 days)

Dashboard Visualizations

## Detail

For detailed implementation code and explanations, refer to the main.ipynb file.
All sql command included in .py file using pyodbc library.
