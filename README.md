# Broadband Coverage API
** by Noel Foy **

For my project the aim is to create an API in which you can put in either the name of your town or county in the 
API and it will then you the percentage of households in the area that have broadband. 
The URL's will be of the format http://broadbandAPI/area/[insert area name] eg http://broadbandAPI/area/Oldcastle 
This type of URL will make it easy for the user as all they will need to enter is the area name.
The people that would use this would be those researching internet access over the country and comparing areas from small villages to big cities.


## Datasets used

Dataset 1: Private households by size. This I will use to find the total amount of households in an area. The dataset shows houses
that have 1 person 2 person etc. it also has a section that shows all houses in an area which is the part of the dataset I will use.
Link to dataset http://data.cso.ie/datasets/households-by-size.html

Dataset 2: Number of households with internet. This I'm going to use to compare the number of households in the area compared
to the number of households with broadband access. I will only use broadband, in the dataset it gives an option for other but I'm 
just going to use broadband as its more of interest to people.
Link to dataset http://data.cso.ie/datasets/households-internet.html

## How to Query the API

The aim for how to query the API is by having a input box where the user is prompted to enter a town or area.
If the area is not in the dataset a message will be returned letting the user know that.

## Example use of the API

How I imagine the API being used is the user will enter in the town or county name.
Returned results will read. Town: Oldcastle, Percentage of households with broadband: 64%, Number of Households: 1000, Households with broadband: 640

## References

Any source I use for researching this project will be contained in here. Will be updated during the project 
