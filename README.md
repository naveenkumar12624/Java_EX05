# Exp-5 Create a table by the following
## AIM:
To write a program that would print the information (name, year of joining, salary, address) of three employees by creating a class named 'Employee'.

## PROCEDURE:
### STEP 1:
Create class Employee with details name,year of joining, salary, address.
### STEP 2:
Create class Main where we have main function.
### STEP 3:
Within main function create object for class Employee.
### STEP 4:
Through the object add vaues for Employee details and display it through function display in Employee class.
### STEP 5:
End of program.
## PROGRAM:
```java
class Employee
{
    String name,address;
    int yoj,salary;
    public void display()
    {
        System.out.printf("%7s       %4d         %15s        %5d\n",name,yoj,address,salary);
    }
}
public class Main
{
    public static void main(String[] args)
    {
        Employee e1=new Employee1();
        Employee e2=new Employee1();
        Employee e3=new Employee1();
        
        e1.name="Robert";
        e1.yoj=1994;
        e1.address="64C-WallsStreet";
        e1.salary=35000;

        e2.name="Sam";
        e2.yoj=2000;
        e2.address="68D-WallsStreet";
        e2.salary=45000;

        e3.name="John";
        e3.yoj=1999;
        e3.address="26B-WallsStreet";
        e3.salary=55000;

        System.out.println("  Name   Year of joining        Address           Salary");
        e1.display();
        e2.display();
        e3.display();
    }
}
```

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/Java_EX05/assets/93427303/97f1c671-9e2e-4bcb-8929-a0fbf059d75f)

## RESULT:
a program that would print the information (name, year of joining, salary, address) of three employees by creating a class named 'Employee' has been executed successfully.
