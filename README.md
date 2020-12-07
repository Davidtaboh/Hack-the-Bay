# Hack-the-Bay

### Background

This project was done for a Hackthathon sponsored by Booz Allen Hamilton and several environmental organizations. It centered around pollution in the Chesapeake Bay, and was divided into four challenges, with each team only able to choose one. Our goal was to visualize pollution in the bay and show how it has changed over time. We were provided with a massive dataset with numerous different pollution datapoints, which were divided by the regions of the Chesapeake Bay watershed. This data comes primarily from the CMC (Chesapeake Monitoring Cooperative), and the CBP (Chesapeake Bay Program), and includes pollution measurement indicators such as water temperature, PH levels, and conductivity.

### Cleaning the data

While the data was clean, relatively speaking, there was still work to be done in order for it to be usable in Tableau. We first had to merge the data into one file, as the data came from two different sources. 

Next, we wanted to have three different CSV files for water temperature, conductivity, and PH levels. The first part of our code, the exploratory file, was us making and exporting three different CSVs with the the data properly formatted. This mostly consisted of us using Python to select only the neccesary columns for our dataframes, and filtering some of the data as neccesary. 

### Enhancing the data

After the intial export of our data to CSV's, we updated our files by adding the fields "q" and "quarter" to make our data more filterable and comparable across different series of time. After this process, we imported the data into Tableau for further analysis.

### License

This project is licensed under the MIT License
