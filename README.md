# Data Cleaning with SQL Queries

This repository contains SQL scripts for cleaning and transforming data from the NashvilleHousing table in the DataCleaningProject database. 
The scripts utilize SQL queries to address various data quality issues and prepare the data for further analysis.

SQL Steps Overview
1. Change SaleDate

    Converts the SaleDate column to the Date data type for consistency and ease of use.

2. Populate Property Address Data

    Populates missing PropertyAddress values by matching ParcelID with non-null PropertyAddress values.

3. Break out Address into Individual Columns (Address, City, State)

    Splits the PropertyAddress column into separate columns for Address, City, and State to improve data organization.

4. Change Y and N to Yes/No in "Sold as Vacant" Field

    Converts 'Y' and 'N' values in the SoldAsVacant field to 'Yes' and 'No' for clarity and consistency.

5. Remove Duplicates

    Removes duplicate records based on specific columns to ensure data integrity.

6. Delete Unused Columns

    Deletes columns OwnerAddress, TaxDistrict, PropertyAddress, and SaleDate, which are no longer needed for analysis.
