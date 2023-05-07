Download Link: https://assignmentchef.com/product/solved-oop-assignment-2
<br>
You are asked to write a program to be used by Massey University Library. There are three types of items that can be borrowed from the library – Books, Journals and Movies. The library keeps records of each item’s type, id, title, year, average rating, number of reviews, and max number of days for borrowing (28 days for books, 14 days for journals, and 7 days for movies). If an item is on loan, its due date should also be recorded. Other information you should record: author and number of pages for books, director for movies, and volume and number for journals.

2. Tasks: Your program shouldA. Read text file library.txt; for each line in the file create a Movie/Book/Journal object and add the object to the library object.B. Output all items in the libraryC. Prompt questions to allow users to do the following (see attached output for more details):a. Search items by id or phrase in title, and list the items foundb. Select an item from the listed items of a search result and display its detailsc. Borrow the selected item if it is available, and display new due date, ord. Return the selected item if it is on loan, ore. Rate the selected item, and display new average rating

Functions workflow (related tasks are marked as A, B, C-a, C-b, C-d, C-d, and C-e):

159.234-2021 Semester 1

3. Design and Implementation GuidelineNote: The following OOP and general software design concepts will be checked while marking the program

1) Class design and implementationb. data fields – internal data not accessed by external classesc. methodsd. constructors

2) Encapsulation design and implementation – proper use of modifiers a. privateb. protectedc. public

3) Inheritance design and implementation a. Reasonable class hierarchiesb. Proper data fields separation in base and derived classesc. Proper methods separation/overloading/overriding in bass and derived classesd. Proper use of base and derived class constructors

4) Polymorphism and implementationa. Write generic code that targets the base class whenever possibleb. Appropriate use of overriding in derived classes to realize polymorphism

5) Information store and implementationa. Use ArrayList or other Java collection class to store information.b. Must make use of getters and/or setters wherever appropriate.

6) Exception handlinga. Throw an exception object when an application error occurs (For example, an invalid piece of data is entered)b. Using “try/catch/finally” or “try/catch” block to handle the exception4. You must follow the next three specifications in each and every assignment for this course1) Place the following comments at the top of your program code and provide the appropriate information:

// Family Name, Given Name, Student ID, Assignment number, 159.234 /* explain what the program is doing . . . */

2) Create the function displayInfo and provide the appropriate information as shown below:

The displayInfo should be the first thing that you display on the screen.

3) DO NOT use any function to clean the screen at any stage of a program, for any assignment in thiscourse.

5. Hand-in: Submit all your .java file as a2.zip electronically on the course stream site.

Marks will be allocated for: correctness, completeness, no code duplication, applying OOP core concepts appropriately, documentation, clear on screen output display…

6. Output of a sample solution

Task A: Add the test data (see library.txt file) into your system. This is the content of the provided library.txt for test purpose.

Task B output: all the items in the library:

Task C: Prompt questions to allow the user to select all the functions: