# World-bank-data-Project

This project aims to use Python generators for streaming data of the Wold bank. It's about writing user-defined functions(plot_pop()), iterators, list comprehensions and generators to wrangle and extract meaningful information from a real-world dataset.


Description of world bank data used:

_Data on world economies for over half a century

_Indicators:
*Population
*Electricity consumption
*CO2 emissions
*Literacy rates
*Unemployment
*Mortality rates

_ Generators for the large data limit:
*Use a generator to load a file line by line
*Works on streaming data
*Read and process the file until all lines are exhausted

feature_names and row_vals contain the header names of the dataset and actual values of a row from the dataset, respectively.

_ Reading files in chunks:
*read_csv() function and chunk_size argument
*Look at specific indicators in specific countries
*Function to generalize tasks

_ plot_pop(): 
takes two arguments: the filename of the file to be processed, and the country code of the rows you want to process in the dataset.
calling the function already does the following:

*Loading of the file chunk by chunk,
*Creating the new column of urban population values, and
*Plotting the urban population data.
