# Project Details

## Coffee Taste Preferences Analysis

### Summary:
The "Coffee Taste Preferences Analysis" Python code project explores coffee drinkers' preferences using data from the 'Great American Coffee Taste Test.' The code covers various aspects, including demographic information, brewing methods, and taste preferences. Visualizations offer insights into popular coffees, preferences by gender, age, and expertise level. The project combines web scraping and data analysis techniques to provide actionable insights for businesses in the coffee industry.

### Use case:
By understanding customer preferences and behaviors, businesses can optimize their strategies, improve product-market fit, and enhance customer satisfaction through personalized experiences and campaigns. This analysis has practical applications for businesses, enabling them to predict customer behavior, create targeted marketing campaigns, and enhance product offerings based on segmented experiences.

### Reference:
[The Great American Coffee Taste](https://cometeer.com/pages/the-great-american-coffee-taste-test)

## Amazon Web Scraping w/ Python

### Summary:
The "Amazon Web Scraping w/ Python" project utilizes libraries like BeautifulSoup, requests, and Selenium to scrape dynamic content from Amazon's website. The script extracts information such as product title, price, and reviews for a specified product, utilizing Selenium for pages that rely on JavaScript for content loading. The extracted data is then stored in a CSV file for further analysis.

### Use case:
In a real-world scenario, this project could be employed for price monitoring and trend analysis. For instance, it could be used by e-commerce businesses to track competitors' pricing, helping them make informed decisions and adjustments to stay competitive. Additionally, this automated web scraping tool can be scheduled to run periodically, providing updated data for ongoing analysis and decision-making processes.

## Data Cleaning with SQL

### Summary:
This project focuses on cleaning and organizing data from the "NashvilleHousing" table in our database. Here's a summary of the key steps:

##### Populating Property Address Data:
* Identifying records with missing property addresses.
* Matching records with the same ParcelID but different UniqueID to update missing property addresses.
##### Breaking out Address into Individual Columns:
* Splitting the Property Address into separate columns for Address and City.
* Creating new columns (PropertySplitAddress and PropertySplitCity) to store the split data.
##### Breaking out Owner Address into Individual Columns:
* Replacing commas with periods and using PARSENAME to split Owner Address into Address, City, and State.
* Creating new columns (OwnerSplitAddress, OwnerSplitCity, and OwnerSplitState) to store the split data.
##### Changing 'Y' to 'Yes' and 'N' to 'No' in "Sold as Vacant" Field:
* Updating the "SoldAsVacant" field to standardize values as 'Yes' or 'No'.
##### Removing Duplicates:
* Using a Common Table Expression (CTE) to identify and delete duplicate records based on specific columns.
##### Deleting Unused Columns:
* Removing unnecessary columns (OwnerAddress, TaxDistrict, PropertyAddress, SaleDate).
* The project aims to enhance data quality and structure, making it more suitable for analysis and reporting. These data cleaning steps ensure consistency, standardization, and elimination of redundant information in the Nashville housing dataset.

### Use case:
In a real-world scenario, this cleaned and organized dataset could be used by real estate professionals, analysts, or researchers for various purposes such as market analysis, trend prediction, and decision-making. It could also serve as a foundation for building machine learning models or integrating with other datasets for comprehensive analysis. The project essentially contributes to data quality, reliability, and usability, which are crucial aspects in any data-driven application or business context.

## COVID-19 Deaths Analysis in SQL

### Summary:
This Python project involves comprehensive data analysis on COVID-19 deaths in the USA. The initial steps include data cleaning, where 'N/A' and 'Data not available' fields are replaced with NULL for accurate calculations. The project then delves into various aspects, such as identifying states with the highest positive tests and hospital admissions, investigating changes in admissions, and assessing death rates over different periods. Notably, the analysis uncovers insights into regional variations, with regions 4 and 5 facing significant challenges.

### Use case:
In a real-world scenario, this project aids healthcare professionals, policymakers, and researchers by providing valuable information for resource allocation, identifying critical regions, and understanding the dynamics of COVID-19 impact. The ability to explore and visualize data trends supports informed decision-making and helps implement targeted strategies to combat the pandemic effectively.

## BMI Calculator

### Summary:
This Python project is a user-friendly tool that calculates Body Mass Index (BMI) based on user-provided information: weight and height. The BMI is then categorized into different weight classes, providing the user with insights into their health status.

### Use case:
This project serves a practical purpose in the real world, as it can be integrated into websites for health-related platforms or fitness applications. By incorporating web scraping, one could collect additional data on health trends, allowing for a broader analysis of BMI distributions across different demographics. Moreover, the tool emphasizes the importance of maintaining a healthy weight, providing links to authoritative sources like the CDC for users to access more information and adopt a balanced lifestyle.

## Automatic File Sorter in File Explorer

### Summary:
This Python project leverages the operating system's capabilities to conduct high-level operations on files, providing an efficient solution for organizing files based on their types. The script automatically categorizes files into folders such as 'csv files,' 'image files,' and 'text files' within a specified directory.

### Use case:
In a real-world scenario, this project is particularly useful for individuals or organizations dealing with diverse data sources and file types. For example, in web scraping and data analysis workflows, where multiple data files, images, and text documents are generated, this script can be employed to streamline the file management process. By automating the sorting of files, it enhances data organization, reduces manual effort, and contributes to a more structured and manageable workspace, ultimately facilitating smoother data analysis and decision-making processes.

