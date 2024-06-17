# Asthma pathients analysis

**Author**: Aizhan Uteubayeva (NetID: au198)  
**Published**: June 18, 2023

## Project Overview

This project involves creating a web-based interface for data retrieval and analysis using FHIR (Fast Healthcare Interoperability Resources) standards. The focus is on building a flexible and interactive interface to fetch and display various types of patient-related data.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [License](#license)

## Installation

1. Ensure you have internet access to load the necessary libraries and access the FHIR server.
2. Download and open the `Class_10_HW_Aizhan.html` file in a web browser.

## Usage

1. **Enter URL Root**
   - Input the root URL of the FHIR server.
   - Default URL: `https://fhir-open.cerner.com/dstu2/ec2458f2-1e24-41c8-b71b-0e701af7583d/`

2. **Select Patient and Data Type**
   - Choose a patient from the dropdown menu.
   - Select the type of data to retrieve (e.g., Patient, Encounters, Care Plan, Meds, Observations, Allergies, Conditions, Procedures, Appointments).

3. **Retrieve and Display Data**
   - Click the "click" button to fetch the selected data type for the chosen patient.
   - The retrieved data will be displayed in a text area and in a table format if applicable.

## Features

- **Flexible Data Retrieval**: Allows selection of different data types for patients.
- **Interactive Interface**: Uses dropdown menus and buttons for ease of use.
- **Data Display**: Formats and displays data in both text and table formats.
- **Error Handling**: Provides feedback if data retrieval fails.

## Dependencies

- **jQuery**: For making AJAX calls and handling data retrieval.
- **FHIR API**: For accessing patient data.

## License

This project is licensed under the MIT License.
