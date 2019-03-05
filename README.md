# sorted-months-weekdays
It sorts list of months or list of weekdays in a chronological order not in alphabetical order

The default python or pandas sort functions sort month names and weekdays in an alphabetical order. I checked a lot to find a function which sorts in chronological order but couldn't find one, so I created this simple package.

# How to install
    pip install sorted-months-weekdays
    
There are two main functions in this package
    Month_Sorted_Month
    Weekday_Sorted_Week
   
# How to import
    from sorted_months_weekdays import Month_Sorted_Month, Weekday_Sorted_Week
    
# Example1
```python
    samplemonthnames1 = ['Apr','Jan','Dec','Mar','Oct']
    samplemonthnames2 = ['December', 'January', 'June', 'March', 'September']
    
    Month_Sorted_Month(samplemonthnames1)
    Result: ['Jan', 'Mar', 'Apr', 'Oct', 'Dec']
    
    Month_Sorted_Month(samplemonthnames2)
    Result: ['January', 'March', 'June', 'September', 'December']
```
# Example2
``` python
    testweeknames1 = ['Tue','Thu','Mon','Sun']
    testweeknames2 = ['Saturday','Tuesday','Friday','Monday']
    
    Weekday_Sorted_Week(testweeknames1)
    Result: ['Mon', 'Tue', 'Thu', 'Sun']
    
    Weekday_Sorted_Week(testweeknames2)
    Result: ['Monday', 'Tuesday', 'Friday', 'Saturday']
```
This function also handles lower and upper case and mixed case months and weekdays lists.
