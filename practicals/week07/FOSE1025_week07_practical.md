# Week 7 SGTA
# PRAC_01

The following are group exercises. For every group, nominate one person who will explain what you have done. The group exercises will be carried out as zoom breakouts and always the same students will be in the same group. Each time, nominate a different person so that all have the opportunity to practice their presentation skills.

## Activity 1 - Understanding dates (5 minutes + 5 minutes discussion)

Dates are stored in Excel as numbers that indicate the number of days since 1 January 1900. Open an Excel spreadsheet and use it to determine what is the date **and the time** that corresponds to the following numbers.

1. 1980.32
2. 34214.16
3. 42332.25

To find the date, you can do the following:

1. Type the number (or copy and paste it) into a cell.
2. Change the cell type to the "Date" format.

## Activity 2 - Finding Time (5 minutes + 5 minutes discussion)

Using the same data from activity 1, can you figure out how to find the time?

## Activity 3 - Operate with dates (10 minutes + 5 minutes discussion)
The following CSV file contains weather data from the US (FYI, the original file is from https://figshare.com/articles/weather_data_csv/5012747).

* [weather_data.csv](weather_data.csv)

Conduct the following activities:

1. Import the CSV file into an Excel spreadsheet.
2. Create the columns `Day`, `Month`, `Year`.
3. Use EXCEL formulas (`DAY`, `MONTH`, `YEAR`) to populate the columns.

## Activity 4 - From Dates to Text (5 minutes + 5 minutes discussion)

Using the same data as in activity 3, use the EXCEL formula (`TEXT`) to generate dates in US format using the `Day`, `Month`, and `Year` columns. In the US format, the month is written before the day. For example, if the date is `23/11/2014`, in US format it will be `11/23/2014`.

You can find documentation about the TEXT function here:
* https://support.office.com/en-us/article/combine-text-with-a-date-or-time-cef6a66c-8176-470c-ba85-4b030405dfbf
* https://support.office.com/en-us/article/text-function-20d5ac4d-7b94-49fd-bb38-93d29371225c

In particular, conduct the following:

1. Create a new worksheet and copy the contents of the worksheet of activity 1 into the new worksheet.
2. Create the column `Date in USA format`.
3. Populate the contents of the column by using the `TEXT` formula.

# PRAC_02
The following are group exercises. For every group, nominate one person who will explain what you have done. The group exercises will be carried out as zoom breakouts and always the same students will be in the same group. Each time, nominate a different person so that all have the opportunity to practice their presentation skills.

## Activity 1 - Parse addresses (10 minutes + 10 minutes discussion)
The following CSV file contains personal information from fictitious people:

* [sample_addresses.csv](sample_addresses.csv)

Conduct the following activities:

1. Create the columns "Street", "City", "Postcode", "State"
2. Use the "text to columns" feature to parse the address column into the different components. For example, the address "171 E 24th St, Leith, 7315 TAS" would fill the following data:

    - **Street**: 171 E 24th St
    - **City**: Leith
    - **Postcode**: 7315
    - **State**: TAS

Hint: In order to fill the columns, you will need to use "text to columns" twice.

## Activity 2 - Flash Fill (15 minutes + 10 minutes discussion)
The following CSV file contains personal information from fictitious people:

* [sample_addresses.csv](sample_addresses.csv)

With this file, use Flash Fill to extract the information from the names and addresses. Flash Fill may or may not work for you. In your group, discuss what you need to do, or what part did not work.

In particular, conduct the following:

1. Import the CSV file into an Excel spreadsheet.
2. Create the columns "First Name", "Surname", "Street", "City", "Postcode", "State".
3. Try to use Flash Fill to fill the data into those columns.
