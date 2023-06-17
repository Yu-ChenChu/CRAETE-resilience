# CRAETE-resilience
------------------
The data is part of the CREATE-resilience project, which aims to plan the solar EV charging station in Los Angeles County.
"" is used to describe a folder and '' is used to describe a file.
1. 'Sunshine_extract.ipynb' contains the code to scrape sunshine data.Source: Sunrise Sunset(https://sunrise-sunset.org/us/los-angeles-ca/2022/1)
2. 'Daylength.ipynb' contains the code to aggregate sunshine data
3. 'Out_LA.ipynb' contains the code to replace column 'start_link' or 'end_link' in dataset'Basecase.csv' with '0' if they are outside of LA.
4. "Data" contains the two folders "LA_Sunrise_Sunset_Data" and "Travel_Trajectory_Data":     
	&emsp;1."LA_Sunrise_Sunset_Data" contains the raw and organized data of sunshine calculation.<br />
		&emsp;&emsp;1. '2018_2023_sunrise_sunset.csv' contains daily sunrise, sunset, and daylength data from 2018 to 2023<br />
  		&emsp;&emsp;2. 'sunrise_sunset_month.csv' contains five-year average monthly data of sunrise, sunset, and daylength from December 2018 to Febuary 2023 <br />
   		&emsp;&emsp;3. 'sunrise_sunset_season.csv' contains five-year average seasonal data of sunrise, sunset, and daylength from December 2018 to Febuary 2023<br />
        &emsp;2. "Travel_Trajectory_Data" contains the raw and organized data for the replacement. However, the other two dataset 'Basecase.csv' and 'Basecase2.csv' are too big to be uploaded:<br />
		&emsp;&emsp;1.'trips_out_of_LA.csv' lists the trips that have the origin or destination locating outside LA county.<br />
		&emsp;&emsp;2.'Basecase.csv' is a travel trajectory dataset that contains all travel information of each trip.<br />
		&emsp;&emsp;3.'Basecase2.csv' is the new travel trajectory dataset which 'start_link' or 'end_link' has been replaced. <br />
