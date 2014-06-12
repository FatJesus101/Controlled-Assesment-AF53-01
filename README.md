#Controlled-Assesment-AF53-01: Plan
===============================
##Task 1-
-------------------------------
###What I Will Need To Be Able To Do:

1) The exchange rates need to be able to be changed by the will of the user.

2) User should be able to enter amount.

3) The user should be able to select the chosen exchanging currency.

4) The printed figure should be to two decimal places.

----------------------------------------------------------------------
###Pseudocode:

```
BEGIN
INPUT currency to be converted, currency converting to (Pound Sterling/Euro/US Dollar/Japanese Yen)
ASSIGN to variables: c_type1, c_type2
INPUT numb1 as c_type1[key]
MATCH c_type1, c_type2 to key in dictionary
IF c_type1 != Pound Sterling and c_type2 != Pound Sterling:
    CONVERT c_type1 into Pound Sterling
    CONVERT Pound Sterling into c_type2
    RETURN int of c_type2
ELSE:
    IDENTIFY Pound Sterling as c_type1 or c_type2
    CHANGE this value to or from Pound Sterling
    RETURN int of c_type2
```
----------------------------------------------------------------------------------------------------
###Variables:

|Variables Used | Type of Variable | Discussion|
|:---|:---:|---:|
|c_type1 | String | Used to store the 'converting from' input text.|
|c_type2 | String | Used to store the 'converting to' input text.|
|numb1 | Integer | Used to store how many of the currency you wish to convert.|
|numb2 | Integer | Used to contain the answer for a short amount of time.|
