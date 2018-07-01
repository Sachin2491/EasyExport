# EasyExport v 0.1.1
Discription : 

Export data from database using passing table name and database connection
You can import jar into your project and just pass database connection and table name in below mentod and getpath of file in return. Simple !

public String getDataForExport(Connection connection, ArrayList<String> tableList)

Enhancements : 01-07-2018

setFilePath(String filePath)
Set file path of you own folder. Example D:\\yourfoldername
Note : Defult folder path will be directry of user who logged in.  Example: I have logged in as Sachin then for me it will be C:\Users\Sachin

setFileName(String fileName)
Set file name : ex: your_file_name
Note :  i ) Defult will be Book.xlsx 
        ii) Do not mention file format name.

setWhereCluse(String whereCluse)
set commmon where claus. In case for all the tables you what apply similar conditions. Example: If there are three table you want extact. Student_Info, Student_address,  Student_percentile this all table have refrance to one primary key which ROlE_NUMBER so you can apply filter like ROLE_NUMBER Between 10 to 30 or ROLE_NUMBER = 20 etc


Note :  code is tested well for oracle and MySQL DB.
Please let me know in case of any issue, through your feedback here or email me on patilsachin2491@gmail.com :  





  

