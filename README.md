
# Intelligent Analytics
Predictive Maintenance


### **Data Source:** 
* A C++ simulator
### **Data Set Information:** 
* The data is a simulation of 60 ingot saw blades being used to cut a certain type of metal ingots. The data set has 6,094,516 records that come from 60 blades (0 - 59) with various total cuts per blade. 
* A CSV file. 
### **Attribute Information:**
* bladenum: represents a blade identification number, with the zero-based numbering.
* cutnum: represents how many times a blade has been used to cut ingots, with the zero-based numbering. 
* time: represents a point in time of a blade, starting with 1. A cut, that is a set of records with the same cutnum value, has the time values from 1 to x, where x is the end of that cut. 
* carriage_position: represents a blade location in a cut. The distance of a blade movement between the times x and x-1 can be calculated by the carriage position at time x minus the carriage position at time x-1. A blade can get duller over time. This can be shown by how much slower a blade moves from one carriage location to the next. 
* failure: represents a failure when the value is 1. 
### **Predicted Attribute:**
* failure
