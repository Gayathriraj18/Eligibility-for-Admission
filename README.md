# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:

Step1:
Start by creating a new class.

Step2:
Initiate the integer variables to assign the marks of Maths, Physics and Chemistry and a string variable to assign the name of the student; read the input from the user.

Step3:
Calculate the first total that sums all the 3 subject marks; and the second total that sums maths and physics marks.

Step4:
Based on the condition given, check whether the student is eligible for the engineering admission.

Step5:
Display the output for the input read from the user.

Step6:
Stop the execution.

## Program:
Developed by : Gayathri A
Register Number : 212221230028

using System;

public class ConsoleApp1
{
    public static void Main(string[] args)
    {
        int physi, chemi, maths, total1, total2;
        string name;
        Console.WriteLine("Enter the Physi mark:");
        physi = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the chemis mark:");
        chemi = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the maths mark:");
        maths = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter a Name of the student");
        name = Console.ReadLine();
        total1 = physi + chemi + maths;
        total2 = physi + maths;
        if (physi >= 55 && chemi >= 50 && maths >= 65)
        {
            if (total1 >= 180 || total2 >= 140)
            {
                Console.WriteLine("{0} is eligible for engineering admission", name);
            }
            else
            {
                Console.WriteLine(name + " is not eligible for engineering admission");

            }
        }
        else
        {
            Console.WriteLine("{0} is not eligible for engineering admission", name);
        }

    }
}


## Output:

![Screenshot (4)](https://user-images.githubusercontent.com/94154854/225386638-87ecd4ec-cf13-4896-b85d-9546a135aaf9.png)

![Screenshot (6)](https://user-images.githubusercontent.com/94154854/225387021-181ccdeb-a0f5-47b2-adae-a818cc8af3f8.png)


## Result:

Thus, a C# program to check the eligibility of a student on engineering admission has been executed successfully.
