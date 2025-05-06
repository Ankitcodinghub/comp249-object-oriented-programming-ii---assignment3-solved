# comp249-object-oriented-programming-ii---assignment3-solved
**TO GET THIS SOLUTION VISIT:** [Comp249 Object-Oriented Programming II – Assignment3 Solved](https://www.ankitcodinghub.com/product/comp249-object-oriented-programming-ii-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;69449&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp249  Object-Oriented Programming II - Assignment3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<strong>Purpose:</strong>&nbsp; The purpose of this assignment is to allow you practice File I/O, ArrayList, and Linked Lists.

<strong><u>Part 1: ArrayList &amp; File I/O</u></strong>

<strong>&nbsp;</strong>Sub-Dictionary Creator

<em>&nbsp;</em>In this part, you are required to write a program that will accept any text file, as input, and creates a sub-dictionary that includes all the words found in that input file based on some rules. The input file may have zero or more words, as well as specific limited set of other characters /punctuation that are used in a specific and predetermined manner. In particular, the text on the input file is only assumed to have the following (besides the words of course!):

<ul>
<li>“<strong>?</strong>”: only appears at the end of a word; for instance: why not<strong>?</strong></li>
<li>“<strong>:</strong>”: only appears at the end of a word; for instance: the rules are<strong>:</strong> ….</li>
<li>“<strong>’</strong>”: which can only appear in front of m or s; for instance: I<strong>’m</strong> … or It<strong>’s</strong> …</li>
<li>“<strong>,</strong>”: only appears at the end of a word; for instance: However<strong>,</strong> ….</li>
<li>“<strong>=</strong>”: which can appear by itself in the middle of an equation; for instance: x <strong>=</strong> y “<strong>;</strong>”: only appears at the end of a word; for instance: violin<strong>; </strong>what else …</li>
<li>“<strong>!</strong>”: only appears at the end of a word; for instance: That is fantastic<strong>!</strong></li>
<li>“<strong>.</strong>”: only appears at the end of a word; for instance: These times were good<strong>. </strong></li>
<li>Digits: 0 to 9, which may appear as a number (i.e. <strong>1927)</strong>; or as a part of a word (i.e. <strong>hi5</strong>) Single characters: <strong>A</strong>, <strong>B</strong>, <strong>T</strong>, etc.</li>
</ul>
&nbsp;

You are required to implement a program that will take any such text file as input, and create a sub-dictionary of the words on that file, based on the following rules:

&nbsp;

<ul>
<li>For each word, only one entry can be recorded in the sub-dictionary. For instance, if the word “Hello” appeared in the text 15 times, it is still recorded once in the sub-dictionary.</li>
<li>All words must be recorded only in UPPERCASE. For instance, Hello must be recorded as HELLO.</li>
<li>Words cannot be recorded with any of the punctuation; for instance, “fantastic!” must be recorded only as “fantastic”.</li>
<li>No numbers or words that have digits anywhere (i.e. 1927, hi5 or b4that) can be recorded in the sub-dictionary.</li>
<li>No single characters (i.e. k, M, t, etc.), with the exception of A and I, can be recorded in the dictionary. (Notice that “a” and “i” are allowed but need to be recorded as A and I respectively).</li>
<li>All words with “’s” or “’m” (or their upper case versions) must be recorded without the ‘s or ‘m. For instance, It’s, will need to be recorded as IT.</li>
<li>All words are recorded in the sub-dictionary in the usual sorted alphabetic order. Additionally, each group must be preceded with an indication of the character that starts this group (similar to real-life dictionaries). For instance, all words starting with “K”, will be preceded with something like:</li>
</ul>
K

= =

<ul>
<li>Finally, the sub-dictionary must have an initial line indicating its size based on the given input file. For instance: The document produced this sub-dictionary, which includes 447 entries.</li>
</ul>
&nbsp;

For instance, given the following file PersonOfTheCentury.txt<sup>[1]</sup> (which is provided with the assignment), your program will create the output file SubDictionary.txt (which is also provided with the assignment). You should notice that this input file is just one example and your program must be able to work with any input file. In fact, the marker will actually test your program with other input files. For immediate illustration, partial images of the input and output files are shown below.

&nbsp;

[1] File is extracted from text obtained from: <u>www.goalcast.com</u>

<strong>Figure 2</strong>: Partial views of the output file Sub-Dictionary.txt

&nbsp;

&nbsp;

&nbsp;

<strong><u>Here are the most important technical rules that you need to follow:</u> </strong>

<ul>
<li>You <strong>MUST</strong> use the <strong>ArrayList</strong> class to implement what is needed. In specific, when you read the input file, all data must be stored in one, or more, ArrayList objects before finally being stored in the output file.</li>
<li>Your program should allow the user to enter the name of the input file at run-time. The name of the output files is always assumed to be txt.</li>
<li>You <strong>MUST NOT</strong> use any other built-in Java classes/packages to do what is needed. For instance, you are <strong>NOT</strong> allowed to use other classes such as List, Map, HashMap, etc. In fact, here are all the needed imports for your program:</li>
</ul>
<strong>import</strong> java.util.ArrayList; <strong>import</strong> java.util.Scanner; <strong>import</strong> java.io.PrintWriter; <strong>import</strong> java.io.FileOutputStream; <strong>import</strong> java.io.FileInputStream;

<strong>import</strong> java.io.FileNotFoundException;

&nbsp;

&nbsp;

ð &nbsp;Finally, as a side note, and in honor/respect of this great scientist, you may notice the word <strong>MC²</strong> in the output file, which was kept in the text and the output in purpose, in spite of the rule stating that words with digits must not be recorded!

&nbsp;

<strong>Figure 3</strong>: In honor of Albert Einstein <strong><u>Part 2: Linked Lists</u></strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<h1>Cell Phones Records</h1>
&nbsp;

In this part, you are required to write a program, using linked lists, that manipulates a set of records of cell phones and performs some operations on these records.

&nbsp;

&nbsp;

<ol>
<li>The <strong>CellPhone</strong> class has the following attributes: a serialNum (long type), a brand (String type), a year (int type, which indicates manufacturing year) and a price (double type). It is assumed that the brand name is always recorded as a single word (i.e. Motorola, SonyEricsson, Panasonic, etc.). It is also assumed that all cellular phones follow one system of assigning serial numbers, regardless of their different brands, so no two cell phones may have the same serial number.</li>
</ol>
You are required to write the implementation of the CellPhone class. Beside the usual mutator and accessor methods (i.e. getPrice(), setYear()) the class must have the following:

<ul>
<li>Parameterized constructor that accepts four values and initializes <em>serialNum</em>, <em>brand</em>, <em>year</em> and <em>price</em> to these passed values;</li>
<li>Copy constructor, which takes two parameters, a CellPhone object and a long value. The newly created object will be assigned all the attributes of the passed object, with the exception of the serial number. <em>serialNum </em>is assigned the value passed as the second parameter to the constructor. It is always assumed that this value will correspond to the unique serial number rule;</li>
<li>clone() This method will prompt the user to enter a new serial number, then creates and returns a clone of the calling object with the exception of the serial number, which is assigned the value entered by the user;</li>
<li>Additionally, the class should have a toString() and an equals() Two cell phones are equal if they have the same attributes, with the exception of the serial number, which could be different.</li>
</ul>
<ol>
<li>The file <strong>txt</strong>, which one of its versions is provided with this assignment, has the information on various cell phone objects. The file may have zero or more records. The information stored in this file is always assumed to be correct and following the unique serial number rule. A snapshot of the contents of the Cell_info.txt file is shown in Figure 1 below.</li>
</ol>
&nbsp;

<ul>
<li>The <strong>CellList</strong> class has the following:</li>
<li>An inner class called CellNode. This class has the following:
<ol>
<li>Two private attributes: an object of CellPhone and a pointer to a CellNode object;</li>
<li>A default constructor, which assigns both attributes to null;</li>
</ol>
</li>
</ul>
<ul>
<li>A parameterized constructor that accepts two parameters, a CellPhone object and a CellNode object, then initializes the attributes accordingly;</li>
</ul>
<ol>
<li>A copy constructor;</li>
<li>A clone() method;</li>
<li>Other mutator and accessor methods.</li>
</ol>
<ul>
<li>A private attribute called head, which should point to the first node in this list object;</li>
<li>A private attribute called size, which always indicates the current size of the list (how many nodes are in the list);</li>
<li>A default constructor, which creates an empty list;</li>
<li>A copy constructor, which accepts a CellList object and creates a copy of it;</li>
<li>A method called addToStart(), which accepts one parameter, an object from CellPhone The method then creates a node with that passed object and inserts this node at the head of the list;</li>
<li>A method called insertAtIndex(), which accepts two parameters, an object from CellPhone class, and an integer representing an index. If the index is not valid (a valid index must have a value between 0 and size-1), the method must throw a NoSuchElementException and terminate the program. If the index is valid, then the method creates a node with the passed CellPhone object and inserts this node at the given index. The method must properly handle all special cases;</li>
<li>A method called deleteFromIndex(), which accepts one integer parameter representing an index. Again, if the index is not valid, the method must throw a NoSuchElementException and terminate the program. Otherwise; the node pointed by that index is deleted from the list. The method must properly handle all special cases;</li>
<li>A method called deleteFromStart(), which deletes the first node in the list (the one pointed by head). All special cases must be properly handled.</li>
<li>A method called replaceAtIndex(), which accepts two parameters, an object from CellPhone class, and an integer representing an index. If the index is not valid, the method simply returns; otherwise, the object in the node at the passed index is to be replaced by the passed object;</li>
<li>A method called find(), which accepts one parameter of type long representing a serial number. The method then searches the list for a node with a cell phone with that serial number. If such an object is found, then the method returns a pointer to that node where the object is found; otherwise, the method returns null. The method must keep track of how many iterations were made before the search finally finds the phone or concludes that it is not in the list;</li>
<li>A method called contains(), which accepts one parameter of type long representing a serial number. The method returns true if an object with that serial number is in the list; otherwise, the method returns false;</li>
<li>A method called showContents(), which displays the contents of the list, in a similar fashion to what is shown in Figure 2 below.</li>
<li>A method called equals(), which accepts one parameter of type CellList. The method returns true if the two lists contain similar objects; otherwise, the method returns false. Recall that two CellPhone objects are equal if they have the same values with the exception of the serial number, which can, and actually is expected to be, different.</li>
</ul>
è Finally, here are some general rules that you must consider when implementing the above methods:

<ul>
<li>Whenever a node is added or deleted, the list size must be adjusted accordingly;</li>
<li>All special cases must be handled, whether or not the method description explicitly states that;</li>
<li>All clone() and copy constructors must perform a deep copy; no shallow copies are allowed;</li>
<li><u>If any of your methods allow a privacy leak, you must clearly place a comment at the beginning of method 1) indicating</u> <u>that this method may result in a privacy leak 2) explaining the reason behind the privacy leak. Please keep in mind</u> <u>that you are not required to implement these proposals;</u></li>
</ul>
&nbsp;

<ol>
<li><strong>IV)</strong> Now, you are required to write a public class called <strong>CellListUtilization</strong>. In the main() method, you must do the following:</li>
</ol>
<ul>
<li>Create at least two empty lists from the CellList class;</li>
<li>Open the txt file, and read its contents line by line. Use these records to initialize one of the CellList objects you created above. You can simply use the addToStart() method to insert the read objects into the list. However, the list should not have any duplicate records, so if the input file has duplicate entries, which</li>
</ul>
is the case in the file provided with the assignment, for instance, your code must handle this case so that each record is inserted in the list only once;

<ul>
<li>Show the contents of the list you just initialized;</li>
<li>Prompt the user to enter a few serial numbers and search the list that you created from the input file for these values. Make sure to display the number of iterations performed;</li>
<li>Following that, you must create enough objects to test each of the constructors/methods of your classes. The details of this part are left as open to you. You can do whatever you wish as long as your methods are being tested including some of the special cases.</li>
</ul>
&nbsp;

<strong><u>General Guidelines When Writing Programs:</u></strong><strong>&nbsp; </strong>

<ul>
<li>Include the following comments at the top of your source codes</li>
</ul>
// —————————————————–

// Assignment (include number)

// Question: (include question/part number, if applicable)

// Written by: (include your name and student id)

// —————————————————–

<ul>
<li>In a comment, give a general explanation of what your program does. As the programming questions get more complex, the explanations will get lengthier.</li>
<li>Include comments in your program describing the main steps in your program.</li>
<li>Display a welcome message which includes your name(s).</li>
<li>Display clear prompts for users when you are expecting the user to enter data from the keyboard.</li>
<li>All output should be displayed with clear messages and in an easy to read format.</li>
<li>End your program with a closing message so that the user knows that the program has terminated.</li>
</ul>
<strong>&nbsp;</strong>

<strong><u>JavaDoc Documentation:</u> </strong>

Documentation for your program must be written in <strong>JavaDoc</strong>.

In addition, the following information must appear at the top of each file:

Name(s) and ID(s) &nbsp;&nbsp; (include full names and IDs)

COMP249

Assignment # &nbsp;&nbsp;&nbsp;&nbsp; (include the assignment number) Due Date &nbsp;&nbsp; (include the due date for this assignment)

<h1>Submitting Assignment 3</h1>
&nbsp;

<ul>
<li>For this assignment, you are allowed to work individually, or in a group of a maximum of 2 students (i.e.</li>
</ul>
you and one other student). You and your teammate must however be in the same section of the course. Groups of more than 2 students = zero mark for all members!

<ul>
<li>Only electronic submissions will be accepted. Zip together with the source codes.</li>
<li>Students will have to submit their assignments (one copy per group) using the Moodle system (please check for your section submission). Assignments must be submitted in the right DropBox/folder of the assignments. <strong>Assignments uploaded to an incorrect DropBox/folder will not be marked and result in a zero mark. No resubmissions will be allowed. </strong></li>
</ul>
– &nbsp;&nbsp;&nbsp; <strong>&nbsp;</strong>

<ul>
<li><u>Naming convention for zip file</u>: Create one zip file, containing all source files and produced documentation for your assignment using the following naming convention:</li>
</ul>
The zip file should be called<em> a#_StudentName_StudentID</em>, where # is the number of the assignment and <em>StudentName/StudentID</em> is your name and ID number respectively. Use your “official” name only – no abbreviations or nicknames; capitalize the usual “last” name. Inappropriate submissions will be heavily penalized. For example, for the first assignment, student 12345678 would submit a zip file named like:<em> a1_Mike-Simon_123456.zip. </em>if working in a group, the name should look like: <em>&nbsp;a1_Mike-Simon_12345678-AND-Linda-</em>

<em>Jackson_98765432.zip. </em>

<em>&nbsp;</em>

<ul>
<li>If working in a team, only one of the members can upload the assignment. <u>Do <strong>NOT</strong> upload the file for</u> <u>each of the members!</u></li>
</ul>
&nbsp;

ð Important: Following your submission, a demo is required (please refer to the course outline for full details). The marker will inform you about the demo times. Please notice that failing to demo your assignment will result in zero mark regardless of your submission.

&nbsp;
