# data-reporting-ssis-
Task -build the report as per given format given and automate the process to run on daily basis.


the below source file will be place in source folder on daily at 8.00 am
source file format : StatePaymentNumbers_yyyymmdd.csv
source location:"C:\Users\lenovo\Desktop\ssis projects\source receive data 8 am"

using above source file build a report as per format given below.

report header:
state| total number same as national payment |Total number less than national payment

report file name :StatePaymentsummaryview_yyyymmdd.txt
report delivery method: location: C:\Users\lenovo\Desktop\ssis projects\report or destination create at 9 am

schedule time : daily 9 am
