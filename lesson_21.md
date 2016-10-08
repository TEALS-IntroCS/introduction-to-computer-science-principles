<!--- REVISED -->
# Lesson 2.1: Loops

## Learning Objectives

Students will be able to...

-   Define "loop" in a programming context
-   Explain why loops are useful
-   Implement simple repeat and forever loops in SNAP
-   Utilize loops to reduce redundancy in code

## Materials/Preparation

-   Lab 2.1 handout - [Squares and Triangles Redux](lab_21.md) ([Download in MS Word](Unit 2 Word/Lab 2.1 Triangles and Squares Redux.docx)) ([Link to PDF](https://teals-introcs.gitbooks.io/introduction-to-computer-science-principles/content/Unit%202%20PDF/Lab%202.1%20Triangles%20and%20Squares%20Redux.pdf))

## Pacing Guide

| Duration   | Description                                   |
| ---------- | --------------------------------------------- |
| 5 minutes  | Welcome, attendance, bell work, announcements |
| 15 minutes | Lecture and examples                          |
| 25 minutes | Activity - Squares and Triangles              |
| 10 minutes | Debrief and wrap-up                           |

## Instructor's Notes

1. Lecture

    1.  Introduce and discuss concepts of code redundancy and readability
        -   Remind students that a program can be written in many different ways that are functionally equivalent.
        -   Ask students to speculate as to why one version of a program might be better or worse.
            -   Possible answers: more efficient (in time or space), shorter code, more elegant/readable code
        -   Use [this example](http://snap.berkeley.edu/snapsource/snap.html#present:Username=brettwo&ProjectName=Lesson%202.1%20Example) to demonstrate unreadable code
            -   Show students the code, ask what it does, then ask if they can think of ways to improve it
            -   Attempt to get students to realize that the code is _redundant_ and could be simplified if there were a way to execute a block of code more than once
    2.  Introduce loops
        -   Begin with general definition: _A type of block that causes other code to run multiple times in succession_
        -   Introduce SNAP specific loops:
            -   ![](repeat.png) runs the body of the loop the specified number of times
                -   Number of iterations can be a value, variable, or reporter
            -   ![](forever.png) runs the body of the loop nonstop until the script is ended 
                -   Can be stopped either by clicking the stop sign or by any version of ![](stop.png)
            -   ![](<repeat until.png>) runs the body of the loop until the specified condition becomes true
                -   Save detailed discussion of this loop until conditionals are introduced
    3.  Walk through examples of ![](repeat.png) and ![](forever.png)

        -   Emphasize usefulness in reducing redundancy and complexity, especially for repetitive tasks
        -   Simple examples are [here](http://snap.berkeley.edu/snapsource/snap.html#present:Username=brettwo&ProjectName=Lesson%202.1%20Example)
2.  Activity
    -   Direct students to complete ["Squares and Triangles Redux"](lab_21.md) individually.  
        -   If available, students should use their solutions to Lab 1.3 ("Squares and Triangles and Stars, Oh My!") as a starting point.  Ensure students "Save as..." before starting on the new lab to not overwrite their original project (part 1.1).
            -   If student solutions for Lab 1.3 are not available, or are not correct, provide a [correct implementation](http://snap.berkeley.edu/snapsource/snap.html#present:Username=brettwo&ProjectName=Lab%202.1) (download the .xml file and import it into SNAP).
        -   Encourage students to try to use as few blocks and have as little code duplication as possible to draw each shape while still creating understandable scripts.
        -   Once students complete part 2.1, the remaining parts should go much more quickly as they all follow the same basic pattern.
3.  Debrief
    -   Discuss one or two student solutions to part 2.2
        -   Ask students to think about what the code would look like without loops
    -   Discuss one or two students solutions to part 3.1
        -   Point out how unwieldy the code for these two shapes would be without loops

## BJC Lecture Suggestions
####Background Information for Instructors

* BJC Video Suggestion: [BJC Lecture 4](https://www.youtube.com/watch?v=_uKCBmQEf5w): Functions
 * SIRI-EVI 0:00-1:00
 * Functions & Generaliztions (Function Basics) 1:00-3:45
 * More Terminology (from Math) *Boolean etc* 3:47-6:10
 * Types of Input (Sentences, words, characters, digits) 6:12-8:00
 * Functions (Explanations of Use-can be tied in to loops, and inputs) 8:00-9:55
 * MIT Scratch --> BYOB SNAP ( Development of SNAP, DEMO) 10:00-11:30
 * Functions-1 (BYOB-Custom Blocks) & Generalization 11:30-14:50
 * Functions-2 (Join Block) Domain and Range 14:52-17:50
 * Types of Blocks 18:15-19:45
 * Recursion Preview 19:50-27:40
 * Functional Programming Summary 27:40- End
 * Big concepts narrow down to functions




## Accommodation/Differentiation

-   More advanced students can add additional shapes, including a five-pointed star without interior lines.  
    *  Particularly advanced students can be encouraged to build pictures by combining multiple shapes (e.g. a house built of squares of various sizes).

[Lab 2.1 Solution](http://snap.berkeley.edu/snapsource/snap.html#present:Username=brettwo&ProjectName=Lab%202.1)
