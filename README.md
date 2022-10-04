# Dmoney-api-jmx
This is a Jmeter Project where the DmoneyAPI is tested by creating test cases for **Login** , **Creating users** , **Searching users by id** , **Searching users by phone number** , **Searching users by email** and also 
performing **Update** and **Delete** operations. The ramp-up and the number of threads were kept as 1.Here login credentials can also be used from the csv file without explicitly writing it in the body.

Steps to run this project:
- Clone this project or download the .jmx file in the project directory.
- Set **Dmoney-api-userData.csv** in the **CSV Data Set Config** in the **Create Custmoner**
- You can generate your own HTML summary report by running the following code in the terminal:
```
jmeter -n -t Dmoney-api.jmx -l Dmoney-api-result.csv -e -o Reports
```
### Summary Report 
![Report 01](https://user-images.githubusercontent.com/85132422/193811552-2d79384c-fa75-485c-838d-640f466bbd10.png)

![Statistics_report](https://user-images.githubusercontent.com/85132422/193811577-01b9c4c7-f027-4960-a1fe-e9461dacd1b6.png)

### Whole project structure in Jmeter

![file_structure](https://user-images.githubusercontent.com/85132422/193811641-d7d450e9-e2f1-4b5a-b1c3-b7698633ef96.PNG)

- All test cases passed can be viewed from Jmeter result tree:

![Viewing_result_tree](https://user-images.githubusercontent.com/85132422/193811670-16c9c222-4860-4ed5-b2a2-1adffad8106b.PNG)

### Summary report in Jmeter.

![summary_report_jmeter](https://user-images.githubusercontent.com/85132422/193811693-98664931-2d0b-4695-a3fc-2aef70d5b87d.PNG)
