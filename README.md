# 911-calls

Emergency (911) Calls: Fire, Traffic, EMS for Montgomery County, PA
You can get a quick introduction to this Dataset with this kernel: Dataset Walk-through
Acknowledgements: Data provided by montcoalert.org

# Dataset
The data- contains the following fields:-- -

* lat : String variable, Latitude
* lng: String variable, Longitude
* desc: String variable, Description of the Emergency Call
* zip: String variable, Zipcode
* title: String variable, Title
* timeStamp: String variable, YYYY-MM-DD HH:MM:SS
* twp: String variable, Township
* addr: String variable, Address
* e: String variable, Dummy variable (always 1)

# Data Cleaning 
* Removing the null values
* droping non usefull columns or dummy cols:
* However we see the last column 'e' has no significance as its a dummy column and all the entries are equal to 1, so its better to discard that column.

# How many different types of calls
Resons for calling the 911 there are mainly 3 resons to call 911 
* Traffic
* EMS
* Fire 
