# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare two variable with string datatype
### Step3:
Loop over the entire string and reverse it
### Step4:
Use if condition to check whether the string and the reversed string is equal or not
### Step5:
print palindrome if it's equal else print not a palindrome.
### Step6:
stop

## Program:
```
using System;
namespace divya
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine(" Enter string");
            s = Console.ReadLine();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                revs += s[i].ToString();
            }
            if (revs == s)
            {
                Console.WriteLine("String is Palindrome");
            }
            else
            {
                Console.WriteLine("String is not Palindrome");
            }
        }
    }
}
```

## Output:
![Screenshot 2022-04-18 193633](https://user-images.githubusercontent.com/75235402/163820940-ce830fae-6b95-4ddf-8022-d57a05af72cc.jpg)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
