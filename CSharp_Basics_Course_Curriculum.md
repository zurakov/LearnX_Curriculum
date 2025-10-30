# C# Basics Course Curriculum (Level 0 - Complete Beginners)
## LeanX.uz Platform | Full-Stack .NET Engineer: Zafar Urakov

---

## 📋 COURSE OVERVIEW

**Target Audience:** Absolute beginners with no programming experience  
**Course Level:** Basics / Beginner (Level 0)  
**Course Format:** 2 videos per week  
**Total Course Duration:** 8 weeks (16 videos)  
**Each Video:** 15-25 minutes  
**Total Content:** ~280-400 minutes (~5-7 hours)

---

## 🎯 COURSE PHILOSOPHY & PRINCIPLES

### Two Core Principles for Beginners:

**1. KISS Principle (Keep It Simple, Stupid)**
- One concept per video
- Real-world analogies for abstract ideas
- Practical examples over theory
- Avoid overcomplicating syntax

**2. Active Learning Through Doing**
- Every topic has hands-on homework
- Homework builds on previous concepts
- Final project combines everything learned

---

## 📚 DETAILED COURSE BREAKDOWN

### **MODULE 1: FOUNDATIONS (Week 1-2)**

#### **Topic 1: Welcome & Why C# Matters**
**Duration:** 12 minutes  
**Key Concepts:**
- What is programming? (Analogy: Recipe for a computer)
- Why C#? (Used by 50% of professional developers in enterprise)
- What you'll build: Small programs, games, web apps, AI tools
- Career path after this course

**Learning Materials:**
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/whats-new/csharp-version-history
- Article: "Why Learn C#?" - Real-world use cases

**Homework:**
- Download Visual Studio Community (free)
- Create a folder: "CSharpCourse"
- Write 3 things you want to build with C# (save as text file)

**Why This Matters:** Motivation and proper environment setup

---

#### **Topic 2: Your First Program - "Hello World"**
**Duration:** 18 minutes  
**Key Concepts:**
- What is a Console Application?
- Understanding the basic project structure
- Main() method - entry point
- Console.WriteLine() - output to screen
- Running your first program

**Learning Materials:**
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/tutorials/hello-world
- W3Schools: https://www.w3schools.com/cs/cs_intro.php

**Code Example:**
```csharp
using System;

class Program {
    static void Main() {
        Console.WriteLine("Hello World!");
    }
}
```

**Homework:**
- Write a program that prints your name, age, and favorite hobby on separate lines
- Bonus: Make it print in 5 different ways (different print statements)

**Why This Matters:** Understand program structure and basic output

---

### **MODULE 2: BASIC CONCEPTS (Week 2-4)**

#### **Topic 3: Comments - Talking to Your Future Self**
**Duration:** 10 minutes  
**Key Concepts:**
- What are comments? (Code that computers ignore)
- Single-line comments (//)
- Multi-line comments (/* */)
- Good vs. bad comments (WHY, not WHAT)

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_comments.php
- Best Practice: Comments explain "why", not "what"

**Code Example:**
```csharp
// This is a single-line comment
/* This is a 
   multi-line comment */

// Good comment: Calculates total price including 15% tax
decimal total = price * 1.15m;

// Bad comment: Adding 1.15
decimal total = price * 1.15m;
```

**Homework:**
- Write a program with at least 5 comments explaining each line
- Write a comment explaining what you had for breakfast (silly but practical)

**Why This Matters:** Code is read more often than written; future you will thank present you

---

#### **Topic 4: Variables & Data Types (Part 1: Basics)**
**Duration:** 22 minutes  
**Key Concepts:**
- What is a variable? (Analogy: Container holding information)
- Variable naming rules (camelCase)
- Basic data types: int, double, string, bool
- Declaration vs. assignment
- The `var` keyword (inference)

**Learning Materials:**
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types
- W3Schools: https://www.w3schools.com/cs/cs_variables.php

**Code Example:**
```csharp
int age = 25;                    // Integer
double height = 5.9;            // Decimal number
string name = "Zafar";          // Text
bool isStudent = true;          // True or False

// Using var - C# figures out the type
var city = "Tashkent";          // String
```

**Homework:**
- Create variables for: your name, age, height, GPA, is_employed, favorite_color
- Print each variable with a description (e.g., "My name is: John")
- Calculate and print your age in 10 years

**Why This Matters:** Variables are the foundation; every program uses them

---

#### **Topic 5: Input - Listen to Your User**
**Duration:** 15 minutes  
**Key Concepts:**
- Console.ReadLine() - getting user input
- Input is always a string initially
- Converting input to other types (parsing)
- Common conversion methods: int.Parse(), double.Parse()

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_user_input.php
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types

**Code Example:**
```csharp
Console.WriteLine("What is your name?");
string name = Console.ReadLine();

Console.WriteLine("How old are you?");
int age = int.Parse(Console.ReadLine());

Console.WriteLine($"Hello {name}, you are {age} years old");
```

**Homework:**
- Create a "Introduction Program" that asks user: name, age, city, job
- Print back all information in a sentence
- Bonus: Calculate how many months old they are

**Why This Matters:** Programs need to interact with users; input makes programs alive

---

#### **Topic 6: Operators - Doing Math & Logic**
**Duration:** 20 minutes  
**Key Concepts:**
- Arithmetic operators: +, -, *, /, %
- Comparison operators: ==, !=, <, >, <=, >=
- Logical operators: &&, ||, !
- Assignment operators: =, +=, -=, etc.
- Order of operations (PEMDAS)

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_operators.php
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types

**Code Example:**
```csharp
// Arithmetic
int sum = 10 + 5;          // 15
int product = 10 * 5;      // 50
int remainder = 10 % 3;    // 1

// Comparison (returns true/false)
bool isGreater = 10 > 5;   // true
bool isEqual = 10 == 5;    // false

// Logical
bool result = (10 > 5) && (5 > 0);  // true (both conditions true)
bool result2 = (10 > 20) || (5 > 0); // true (at least one true)
```

**Homework:**
- Calculator program: Ask user for 2 numbers, show all operations (+, -, *, /, %)
- Compare 2 ages and tell who is older
- Check if a number is positive, negative, or zero

**Why This Matters:** Math and logic are the core of programming

---

#### **Topic 7: Output Formatting - Making Output Pretty**
**Duration:** 12 minutes  
**Key Concepts:**
- String interpolation ($"...")
- String concatenation (+)
- Escape characters (\n, \t, etc.)
- Basic formatting

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_output.php
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/strings

**Code Example:**
```csharp
string name = "Zafar";
int age = 28;

// String interpolation (recommended)
Console.WriteLine($"My name is {name} and I'm {age} years old");

// Concatenation
Console.WriteLine("My name is " + name + " and I'm " + age + " years old");

// Escape characters
Console.WriteLine("Line 1\nLine 2");      // New line
Console.WriteLine("Column1\tColumn2");    // Tab
```

**Homework:**
- Create a formatted resume (5-6 lines with proper spacing)
- Use \n and \t for formatting
- Display a calculation with clear formatting

**Why This Matters:** User experience matters; good formatting makes programs professional

---

### **MODULE 3: CONTROL FLOW (Week 4-6)**

#### **Topic 8: If Statements - Making Decisions**
**Duration:** 20 minutes  
**Key Concepts:**
- if statement (one path)
- if-else (two paths)
- if-else if-else (multiple paths)
- Nested if statements
- Boolean conditions

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_conditions.php
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/control-flow

**Code Example:**
```csharp
int age = 20;

// Simple if
if (age >= 18) {
    Console.WriteLine("You are an adult");
}

// if-else
if (age >= 18) {
    Console.WriteLine("You are an adult");
} else {
    Console.WriteLine("You are a minor");
}

// if-else if-else
if (age < 13) {
    Console.WriteLine("Child");
} else if (age < 18) {
    Console.WriteLine("Teenager");
} else {
    Console.WriteLine("Adult");
}
```

**Homework:**
- Grade calculator: User enters score (0-100), print grade (A, B, C, D, F)
- Age checker: Determine if person can vote, drive, drink (in your country)
- Number checker: Is it positive, negative, or zero?

**Why This Matters:** Programs need to make decisions based on conditions

---

#### **Topic 9: Switch Statements - The Organized Decision**
**Duration:** 15 minutes  
**Key Concepts:**
- Switch vs. if-else (when to use each)
- Case statement
- Break statement
- Default case
- When switch is cleaner than if-else

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_switch.php
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/control-flow

**Code Example:**
```csharp
int day = 3;

switch (day) {
    case 1:
        Console.WriteLine("Monday");
        break;
    case 2:
        Console.WriteLine("Tuesday");
        break;
    case 3:
        Console.WriteLine("Wednesday");
        break;
    default:
        Console.WriteLine("Unknown day");
        break;
}
```

**Homework:**
- Day of week program: User enters 1-7, print day name
- Menu system: Show options (1=Add, 2=Subtract, 3=Multiply, 4=Exit)
- Month to season converter

**Why This Matters:** Switch statements are cleaner for multiple specific conditions

---

#### **Topic 10: While Loop - Repeat Until Condition is False**
**Duration:** 18 minutes  
**Key Concepts:**
- What is a loop? (Repeat code without rewriting)
- While loop structure
- Infinite loops (and how to avoid them)
- Loop counter
- Break and continue

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_while_loop.php
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/control-flow

**Code Example:**
```csharp
int count = 0;

while (count < 5) {
    Console.WriteLine($"Count: {count}");
    count++;  // IMPORTANT: Must update count or infinite loop!
}

// With break
while (true) {
    Console.WriteLine("Enter number (0 to exit):");
    int input = int.Parse(Console.ReadLine());
    if (input == 0) break;
    Console.WriteLine($"You entered: {input}");
}
```

**Homework:**
- Countdown from 10 to 1
- Ask user for numbers until they enter -1
- Multiplication table: Print 5 times table (5x1=5, 5x2=10, etc.)

**Why This Matters:** Loops save you from writing repetitive code

---

#### **Topic 11: For Loop - Repeat a Known Number of Times**
**Duration:** 18 minutes  
**Key Concepts:**
- For loop structure: initialization, condition, increment
- For vs. while (when to use each)
- Loop variable scope
- Nested loops
- Break and continue in for loops

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_for_loop.php
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/control-flow

**Code Example:**
```csharp
// Simple for loop
for (int i = 0; i < 5; i++) {
    Console.WriteLine($"Number: {i}");
}

// Nested loop (pattern)
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= 3; j++) {
        Console.Write($"{i},{j} ");
    }
    Console.WriteLine();
}
// Output: 1,1 1,2 1,3  2,1 2,2 2,3  3,1 3,2 3,3
```

**Homework:**
- Print numbers 1-20
- Print multiplication table (all tables 1-10)
- Create a pattern (triangle, square using * or #)
- Bonus: Create a pyramid pattern

**Why This Matters:** For loops are essential for counted repetitions; cleaner than while in many cases

---

#### **Topic 12: Break & Continue - Control Loop Flow**
**Duration:** 12 minutes  
**Key Concepts:**
- Break: Exit loop immediately
- Continue: Skip to next iteration
- When to use each
- Avoiding excessive break/continue (code clarity)

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_break_continue.php

**Code Example:**
```csharp
// Break: Exit loop
for (int i = 0; i < 10; i++) {
    if (i == 5) break;  // Stop at 5
    Console.WriteLine(i);
}

// Continue: Skip this iteration
for (int i = 0; i < 10; i++) {
    if (i == 5) continue;  // Skip 5, continue to 6
    Console.WriteLine(i);
}
```

**Homework:**
- Find first number divisible by both 3 and 5 (from 1-100), then stop
- Print 1-20 but skip even numbers
- Bonus: Find sum of numbers 1-100 (but skip multiples of 10)

**Why This Matters:** Advanced loop control for specific requirements

---

### **MODULE 4: DATA STRUCTURES (Week 6-7)**

#### **Topic 13: Arrays - Store Multiple Values**
**Duration:** 20 minutes  
**Key Concepts:**
- What is an array? (Container for multiple items of same type)
- Array declaration and initialization
- Index (position starts at 0)
- Array length
- Looping through arrays
- Common mistakes (IndexOutOfRange)

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_arrays.php
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/arrays

**Code Example:**
```csharp
// Declaration and initialization
int[] numbers = { 10, 20, 30, 40, 50 };

// Access by index (0-based)
Console.WriteLine(numbers[0]);  // 10
Console.WriteLine(numbers[2]);  // 30

// Array length
Console.WriteLine(numbers.Length);  // 5

// Loop through array
for (int i = 0; i < numbers.Length; i++) {
    Console.WriteLine(numbers[i]);
}

// For-each loop (easier)
foreach (int num in numbers) {
    Console.WriteLine(num);
}
```

**Homework:**
- Store 5 numbers in array, find sum and average
- Store 5 names, print them all
- Find the largest number in an array
- Bonus: Find the smallest and largest in same program

**Why This Matters:** Arrays are foundational for handling multiple data items

---

#### **Topic 14: String Methods & Manipulation**
**Duration:** 18 minutes  
**Key Concepts:**
- What are methods? (Functions that strings can use)
- Common string methods: Length, ToUpper(), ToLower(), Substring(), Contains(), Split(), Replace()
- String immutability (strings don't change; new string is created)
- Practical text manipulation

**Learning Materials:**
- W3Schools: https://www.w3schools.com/cs/cs_strings_methods.php
- Official: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/strings

**Code Example:**
```csharp
string text = "Hello World";

// Properties
int length = text.Length;  // 11

// Methods
string upper = text.ToUpper();      // "HELLO WORLD"
string lower = text.ToLower();      // "hello world"
string sub = text.Substring(0, 5); // "Hello"
bool contains = text.Contains("World");  // true
string replaced = text.Replace("World", "C#");  // "Hello C#"
string[] words = text.Split(' ');  // {"Hello", "World"}
```

**Homework:**
- Check if a word is in a sentence
- Convert user input to uppercase and lowercase
- Extract first 3 characters of a word
- Count how many times a letter appears in a sentence (Bonus)

**Why This Matters:** String methods are essential for text processing; used in almost every program

---

### **MODULE 5: SIMPLE PRINCIPLES & PROJECT (Week 7-8)**

#### **Topic 15: KISS Principle & Code Quality for Beginners**
**Duration:** 15 minutes  
**Key Concepts:**
- KISS: Keep It Simple, Stupid
- Why simple code is better than complex code
- Naming variables with clarity
- One job per variable/section
- Readable code is maintainable code
- Real examples: Good vs. Bad code

**Learning Materials:**
- Article: "Clean Code for Beginners" (self-curated)
- Self-reference: Your own code reviews at Aspen Publishing

**Code Example - BAD:**
```csharp
// Don't do this:
int x = int.Parse(Console.ReadLine());
int y = int.Parse(Console.ReadLine());
int z = x + y;
Console.WriteLine(z);
```

**Code Example - GOOD:**
```csharp
// Do this instead:
Console.WriteLine("Enter first number:");
int firstNumber = int.Parse(Console.ReadLine());

Console.WriteLine("Enter second number:");
int secondNumber = int.Parse(Console.ReadLine());

int sum = firstNumber + secondNumber;
Console.WriteLine($"The sum is: {sum}");
```

**Homework:**
- Review one of your previous programs
- Rewrite it using KISS principles (better variable names, clear steps)
- Add helpful comments explaining WHY, not WHAT

**Why This Matters:** Professional developers prioritize readable, simple code

---

#### **Topic 16: CAPSTONE PROJECT - Student Management System**
**Duration:** 25 minutes (Project duration: 4-5 hours of coding)  

**Project Requirements:**
This project combines ALL concepts learned in the course.

**Features to Implement:**
1. Display a menu with options (using switch)
2. Add Student: Input name, age, GPA; store in arrays
3. View All Students: Show all students added
4. Search Student: Find student by name
5. Calculate Average GPA: Find average of all GPAs
6. Remove Student: Delete student from system
7. Exit: Quit the program

**Technical Requirements:**
- Use arrays to store student data
- Use loops (for/while) to manage multiple students
- Use if/else and switch for decisions
- Use string methods for searching
- Apply KISS principle throughout
- Add comments explaining key sections
- Validate user input (check if array is full, etc.)

**Code Structure (Starter Template):**
```csharp
using System;

class StudentManagementSystem {
    static void Main() {
        // Arrays to store student data
        string[] names = new string[10];      // Max 10 students
        int[] ages = new int[10];
        double[] gpas = new double[10];
        int studentCount = 0;  // Track how many students
        
        bool running = true;
        while (running) {
            // Display menu
            Console.WriteLine("\n=== Student Management System ===");
            Console.WriteLine("1. Add Student");
            Console.WriteLine("2. View All Students");
            Console.WriteLine("3. Search Student");
            Console.WriteLine("4. Calculate Average GPA");
            Console.WriteLine("5. Remove Student");
            Console.WriteLine("6. Exit");
            Console.WriteLine("Enter choice (1-6):");
            
            string choice = Console.ReadLine();
            
            switch (choice) {
                case "1":
                    // Add student logic here
                    break;
                case "2":
                    // View all logic here
                    break;
                // ... other cases
                case "6":
                    running = false;
                    break;
            }
        }
    }
}
```

**Learning Outcomes:**
- Practical application of all learned concepts
- Problem-solving skills
- Code organization
- User interaction design

**Evaluation Criteria:**
- ✓ Program runs without errors
- ✓ All menu options work correctly
- ✓ Code is readable (good naming, comments)
- ✓ Proper use of loops, arrays, conditions
- ✓ Input validation (basic checks)

**Homework:**
- Complete the Student Management System (4-5 hours coding)
- Submit complete code with comments
- Write a 1-page reflection: "What I learned and what was hard"

---

## 📊 COURSE TIMELINE & RECORDING SCHEDULE

### **Recording Plan: 2 Videos per Week**

| Week | Days | Topics | Video Count | Minutes |
|------|------|--------|-------------|---------|
| 1 | Mon-Sun | #1-2 | 2 | ~30 |
| 2 | Mon-Sun | #3-4 | 2 | ~32 |
| 3 | Mon-Sun | #5-6 | 2 | ~35 |
| 4 | Mon-Sun | #7-8 | 2 | ~35 |
| 5 | Mon-Sun | #9-10 | 2 | ~33 |
| 6 | Mon-Sun | #11-12 | 2 | ~30 |
| 7 | Mon-Sun | #13-14 | 2 | ~38 |
| 8 | Mon-Sun | #15-16 | 2 | ~40 |

**Total Course Duration:**  
- **Recording Time:** 8 weeks (2 videos/week)
- **Total Video Content:** ~280 minutes (~4.7 hours)
- **With Breaks:** ~5-7 hours total watch time
- **Student Coding Time:** ~25-30 hours (homework + project)
- **Full Course (Watch + Code):** ~30-37 hours

---

## 📝 HOMEWORK STRUCTURE

**Daily Homework:** 30-45 minutes per topic  
**Purpose:** Reinforce learning through practice

**Homework Progression:**
- Topics 1-4: Individual concepts
- Topics 5-7: Combining concepts
- Topics 8-12: Complex logic and loops
- Topics 13-14: Data structures
- Topics 15-16: Professional practices + capstone

---

## 🎓 SUCCESS METRICS FOR STUDENTS

After completing this course, students will be able to:
- ✓ Write basic C# programs
- ✓ Understand variables, data types, and operators
- ✓ Use if/else and switch statements
- ✓ Create loops (for, while, do-while)
- ✓ Work with arrays
- ✓ Manipulate strings
- ✓ Write clean, readable code (KISS principle)
- ✓ Build a complete student management system

---

## 💡 TEACHING TIPS

**For Beginners:**
1. **One Concept Per Video:** Don't overload information
2. **Live Coding:** Type code during recording; show errors and fixes
3. **Real-World Analogies:** Variables = boxes, Loops = repetition in life, Arrays = lists
4. **Pause for Practice:** Pause video and let students code along
5. **Show Common Mistakes:** Include "common error" segments so students learn what NOT to do
6. **Encourage Questions:** Create Discord/Telegram group for homework help

**Video Structure (Suggested for Each Topic):**
1. **Hook (1 min):** Why this matters
2. **Theory (3-5 min):** Explain concept with analogy
3. **Code Example (5-7 min):** Live coding, showing output
4. **Common Mistakes (2-3 min):** What can go wrong
5. **Preview Homework (2 min):** What's coming next

---

## 📚 RECOMMENDED MATERIALS PER TOPIC

**Official Documentation:**
- Microsoft Docs: https://docs.microsoft.com/en-us/dotnet/csharp/
- C# Language Guide: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals

**Free Resources:**
- W3Schools C#: https://www.w3schools.com/cs/
- Microsoft Learn: https://learn.microsoft.com/en-us/training/modules/csharp-variables
- Your reference: Hassan Habib's Standard Architecture principles

**Tools (All Free):**
- Visual Studio Community: https://visualstudio.microsoft.com/community/
- VS Code + C# Extension
- .NET SDK: https://dotnet.microsoft.com/en-us/download

---

## 🚀 NEXT STEPS AFTER BASICS

Once students complete this course:
- **Intermediate Level:** Methods, Classes, Object-Oriented Programming (OOP)
- **Advanced Level:** SOLID Principles, Design Patterns, Event-Driven Architecture (Hassan Habib's Standard)
- **Specialized:** AI Integration, Azure, Entity Framework, Blazor

---

## ✅ SUMMARY FOR YOU

**You'll Record:**
- 16 videos total
- 2 per week for 8 weeks
- 280-400 minutes total content
- Recommended: 20-30 min per video (includes intro/outro/code)

**Your Advantage:**
- Hassan Habib experience = focus on CLEAN CODE
- Enterprise background = real-world examples
- Teaching 10+ developers = explain simply

**Unique Selling Point for LeanX.uz:**
- Beginner-friendly (no prerequisites)
- Professional-grade content (from industry expert)
- Practical capstone project (builds real skills)
- Clear progression to intermediate/advanced

---

**Good luck with your course, Zafar! 🎉**  
*This curriculum balances simplicity with professionalism—perfect for Level 0 students.*
