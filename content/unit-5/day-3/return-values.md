---
title: "Return Values"
metaTitle: "Return Values"
order: 0
---

## Summary

### Materials  

* [Day 3 PowerPoint deck]()
* [Full Name sample code]()
* [Series Sum Solution]() (for teacher)
* [Pizza Allowance code sample]()
* [Writing Functions with Return Values]() Handout
* [Writing Functions with Return Values]() Handout in Word
* [Activity: Return Values]()
* [Problem Set: Returns]()

### Instructional Activities and Classroom Assessments 

1. Parameters Review (5 minutes)
2. Introduce Return Values (20 minutes)
3. Activity: Writing Functions with Return Values (25 minutes)
4. Reflection
5. Homework

### Learning Objectives 

* [AAP-3.A]() For procedure calls:
    * a. Write statements to call procedures. [3.B]()
    * b. Determine the result or effect of a procedure call. [4.B]() 
* [AAP-3.B]() Explain how the use of procedural abstraction manages complexity in a program. [3.C]()
* [AAP-3.C]() Develop procedural abstractions to manage complexity in a program by writing procedures. [3.B]()

### Essential Knowledge

* [AAP-3.A.1]() A procedure is a named group of programming instructions that may have parameters and return values.
* [AAP-3.A.2]() Procedures are referred to by different names, such as method or function, depending on the programming language.
* [AAP-3.A.3]() Parameters are input variables of a procedure. Arguments specify the values of the parameters when a procedure is called.
* [AAP-3.A.4]() A procedure call interrupts the sequential execution of statements, causing the program to execute the statements within the procedure before continuing. Once the last statement in the procedure (or a return statement) has executed, flow of control is returned to the point immediately following where the procedure was called.
* [AAP-3.B.1]() One common type of abstraction is procedural abstraction, which provides a name for a process and allows a procedure to be used only knowing what it does, not how it does it.
* [AAP-3.B.2]() Procedural abstraction allows a solution to a large problem to be based on the solutions of smaller subproblems. This is accomplished by creating procedures to solve each of the subproblems.
* [AAP-3.B.4]() A procedural abstraction may extract shared features to generalize functionality instead of duplicating code. This allows or program code reuse, which helps manage complexity.
* [AAP-3.B.5]() Using parameters allows procedures to be generalized, enabling the procedures to be reused with a range of input values or arguments.  
* [AAP-3.C.2]() The exam reference sheet provides
```
Text:

PROCEDURE procName(parameter1, parameter2, ...)
{    
    <block of statements>    
    RETURN(expression)
}
Block:  

which is used to define a procedure that takes zero or more arguments. The procedure contains block of statements and returns the value of expression. The RETURN statement may appear at any point inside the procedure and causes an immediate return from the procedure back to the calling statement.
```

## Details 

### 1. Parameters review (5 minutes)

* Review with students:
    * Parameters
    * Data types
    * How to use parameters in a function

### 2. Introduce return values (20 minutes)

* Define return values.
* Student will use examples provided in the PowerPoint to learn how return values work.

### 3. Activity: Writing Functions with Parameters (25 minutes)

* Direct students to go their Writing Functions with Return Values page.
* Task students with completing all of the tasks on the page:
    * Tasks 1 - 2 using the guide on the Activity: Return Values webpage.
    * Task 3.
    * If students have time, encourage them to code in JavaScript.

### 4. Reflection

If you run out of time, you may also assign this as individual homework. Students should complete their reflection. 

1. What needs to be added to a function so that it will return a value?
2. If a function returns a value in one case, does it need to return a value in all cases?
3. What happens if you call a function with a return value without storing or using the returned value?
4. Where might return values be used in your previous projects?

### 5. Homework

* Task students with completing the activities on the Problem Set: Returns webpage for homework.
* _Practice sets are written as JavaScript exercises and can be accomplished using block based code. Students can choose whichever code editor they feel most comfortable with to complete the problems. If needed, students can copy the JavaScript snippet from the problem set, paste it into the JavaScript workspace in MakeCode, then switch back to Block. It has been demonstrated that exposing students to both block and text based code simultaneously makes the transition from block to text more successful._