# Manual Base Functionality
This manual describes how to set up and use the Base Functionality app.

## Deferral Templates
In standard BC you already have the possibility to create deferral templates. Base Functionality has an extra possibility: **adjusted date formula**.
In this document we will explain the standard procedure and the adjusted date formula.

![Deferral Template](../images/deferral-templates/deferral-template.png)

| **Field Name**  | **Description** |
| ------------- | ------------- |
| Deferral code  | Unique deferral code for the template.  |
| Description  | Description of the deferral template.  |
| Deferral account  | The ledger account for posting the deferred costs.  |
| Deferral %  | The percentage of the deferred amount.  |
| Calculation method  |<ul><li>Straight-line</li><li>Equal amount per period</li><li>Days per period</li><li>User-defined</li><li>In practice we always use straight-line.</li><li>In this document we will give examples of all methods.</li></ul>|
| Start Date  | <ul><li>Posting Date</li><li>Beginning of period</li><li>End of period</li><li>Beginnen of next period</li><li>Beginning of next calendar year</li></ul>  |
| No. of periods  | Specifies how many accounting periods the total amounts will be deferred to.  |
| Period description  | <ul><li>%1 = No of day</li><li>%2 = No of week</li><li>%3 = Month as number</li><li>%4 = Written month</li><li>%5 = Written month</li><li>%6 = Year</li></ul>  |
| Adjusted Date Formula  | -1M <br> As a result, the first booking is not made on the entered start date, but 1 month earlier.  |

How this works in the section [Use Deferral Templates](use-deferral-templates.md).

[:arrow_left:](../README.md) [Back](../README.md)