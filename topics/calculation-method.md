# Manual Base Functionality
This manual describes how to set up and use the Base Functionality app.

## Calculation Method
When creating a deferral template, we can indicate what the calculation method is.

### Straight-Line
This means that the amounts are evenly distributed over the periods.
The beginning period (start date) is very important.
If the start is on the 1st of the month, all periods will be the same. 
Do we start eg on 10-11-2022 then the amount will be calculated pro rata.

![Straight Line Calculation Method](../images/calculation-method/straight-line-method.png)

### Equal per Period
If we choose Equal per Period as the method, the amounts will be the same (100) in all periods, regardless of the start date. 

### Days per Period
If we choose Days per period, the 1st period will be calculated based on the start date. If this is still on 10-10-23, 22 days are calculated. The amounts are calculated as follows: Total amount to be distributed (1200) / 365 days (year).

![Days per Period Calculation Method](../images/calculation-method/days-per-period-method.png)

### User-defined
Finally, the User Defined method. If we choose this method, we will have to divide the amounts manually ourselves. The total amount distributed must of course be equal to the amount to be distributed.

![User-defined Calculation Method](../images/calculation-method/user-defined-method.png)


[:arrow_left:](../README.md) [Back](../README.md)