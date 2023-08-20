# EX-1 Eligibility-for-Admission
## Date:

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithm:
### Step 1:
Create new class

### Step 2:
Initiate the variables for maths, physics and chemistry and get the value from the user.

### Step 3:
Convert the values to integer values.

### Step 4:
Calculate the sum of all three subjects and maths-physics total.

### Step 5:
Check for the given criteria for eligibility using if-else statements.

### Step 6:
Display whether the person is eligible for admission or not based on the given criteria.

### Step 7;
Exit the Program.

## Program:
Name : Anand sasidharan

Reg no : 212221240049

```c#
using System;

namespace exp1
{
    class Eligibility
    {
        static void Main(string[] args)
        {
            string name;
            int math, phy, chem;
            Console.Write("Enter your name:");
            name = Console.ReadLine();
            Console.Write("Enter Maths Marks:");
            math = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter Physics Marks:");
            phy = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter Chemistry Marks:");
            chem = Convert.ToInt32(Console.ReadLine());
            int Sum = math + phy + chem;
            int MPTot = math + phy;
            if (math >= 65 && phy >= 55 && chem >= 50)
            {
                if (Sum >= 180 || MPTot >= 140)
                {
                    Console.WriteLine(name + " is eligible for admission to an engineering course.");
                }
                else
                {
                    Console.WriteLine(name + " is not eligible for admission to an engineering course due to insufficient marks.");
                }
            }
            else
            {
                Console.WriteLine(name + " is not eligible for admission to an engineering course due to insufficient marks.");
            }
            Console.Read();
        }
    }
}
```

## Output:
![1](https://github.com/sasidharan403/Eligibility-for-Admission/assets/94154712/98bc360a-70e0-4caf-bb97-c8ab955c4bb6)
![1](https://github.com/sasidharan403/Eligibility-for-Admission/assets/94154712/98bc360a-70e0-4caf-bb97-c8ab955c4bb6)


## Result:

Thus a C# program to check eligibility for admission is executed successfully.
