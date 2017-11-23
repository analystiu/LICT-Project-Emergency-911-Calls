# LICT-Project-Emergency-911-Calls
The data of the file is https://www.kaggle.com/mchirico/montcoalert/data you can get it from kaggle.com

Fire, Traffic, EMS for Montgomery County, PA
This data shows all 9-1-1 police emergency response and officer-initiated calls for service in the City of Montgomery County, PA beginning December 10, 2015. Emergency response calls are the result of people calling 9-1-1 to request police services. Officer-initiated calls include traffic stops, street investigations and other policing activities (such as observing crimes in progress) where police officers initiate the response. The table includes all calls taken and reports intake, dispatch, travel, and total response and call times for those calls serviced by a police agency. The data also includes the responding agency, unit, call type and category and disposition of each call.

Field descriptions:

lat:    Latitude from Google maps, based on the address in the description.
lng:    Longitude same as above, based on the address
desc:    Is the exact description as it was delivered through Montco Active Alert.
zip:    Calculated from Google, when possible.
twp:    The township or boro
timestamp:    is the time
add:    Just the address
e:    This field is always 1…used for counting

(Module required):
1.	Numpy
2.	Pandas
3.	Matplotlib
4.	Pyspark
