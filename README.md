class EmployeeDetails { 


is created with all the logic part along with global variables: name as string data type, age as int data type, salary as float datatype and designation as string datatype. 



 String name;


int age;


Float salary;


String designation;


To get user input I have taken Scanner object Scanner in=new Scanner(System.in);



create(){



method is created to take the inputs of the employees it asks to enter the name and it takes the input using next().



then it asks to enter age, as it is int data type we use nextInt() it converts the string to int. 



Then enter salary it is a float data type we use nextFloat() it converts the string to float





display(){



method to display the all the details of the required employee (i.e), employees name,age and salary.




 System.out.println("name : "+name+"age:"+age+"salary:"+salary+"designation:"+designation);





salaryraise(){


to increment the salary, salary raise for the employee is 1500, then it prints the output as salary raised.



class main { 



is created in that object is created for the EmployeeDetails class to fetch the business logic.




while(true){




while loop is taken to repeate the conditions given below, scanner is taken to take the input as choice, 




if(i==4){ 




break;}



it means if the choice is equal to 4 then it exists out



 switch(i){



choice are as below



case 1: e.create();


        break;



 it creates the employee details,



 case 2: e.display();
        
        
        
        break;



 it displays the deatils of the employee, 



case 3: e.salaryraise();
        
        
        break;
        
        
        
 it show the message salary is raised, if the choice is greater than equal to 



case 4: then the program should exit.




output:



In this program it asks to select options:


1.create



2.display



3.salaryraise



4.exit



if we select choice as 1 it takes the employee details



if we select choice as 2 it displays the employee details



if we select choice as 3 it increases the salary of employee with 1500



if we select choice as 4 it exits out of program
