—--commands to run on a fresh vm—-
sudo apt-get upgrade -y
sudo apt-get install python3 -y
sudo apt-get install python3-pip -y
pip3 install requests
pip3 install Flask
—----------SCRIPT OPTIONS—---------- 
--field
Select a field 
--value
Select a value 
--verbose
Show the results as they are calculated 
--test-nvd --verbose
Test if the nvd api call works 
--NVD
Enable the nvd api call, will take a longer run time
--output
Output the full results 
--api-key
Add your api key
--add-mapping {custom-server custom_vendor custom_product}
Add a new cpe maping
--list-mappings
Displays all the current cpe mappings 
