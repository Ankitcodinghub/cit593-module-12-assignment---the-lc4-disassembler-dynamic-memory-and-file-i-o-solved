# cit593-module-12-assignment---the-lc4-disassembler-dynamic-memory-and-file-i-o-solved
**TO GET THIS SOLUTION VISIT:** [CIT593 Module 12 Assignment – The LC4 Disassembler: Dynamic Memory and File I/O Solved](https://www.ankitcodinghub.com/product/cit593-module-12-assignment-the-lc4-disassembler-dynamic-memory-and-file-i-o-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;133478&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIT593 Module 12 Assignment - The LC4 Disassembler: Dynamic Memory and File I\/O Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

<h1>Assignment Overview</h1>
In the last assignment, you created a .obj object file from a .asm assembly file.

In this assignment, you will write a program that opens and reads a .obj file created by PennSim, parses it, and loads it into a linked list representing the LC4’s program and data memories (similar to what PennSim’s “loader” does). Additionally, you will be able to convert the binary file contents back to the assembly it came from! This is known as reverse assembling or disassembling.

<h1>Learning Objectives</h1>
This assignment will cover the following topics:

<ul>
<li>Review the LC4 Object File Format</li>
<li>Implement a LinkedList in C</li>
<li>Read and process binary files</li>
<li>Disassemble binary data into a human-readable format</li>
<li>Use debugging tools such as GDB and Valgrind</li>
<li>(Optionally) Collaborate with another programmer on a complex project</li>
</ul>
&nbsp;

<h1>Advice</h1>
<ul>
<li>Read this entire document before starting.</li>
<li>Read this entire document before starting.</li>
<li>Start on this project early.</li>
<li>Find a collaboration partner, even if you decide to do the assignment solo.</li>
<li>Attend recitation, or watch the recordings.</li>
<li>Attend professor office hours, or watch the recordings.</li>
<li>Read the FAQs and search ED Discussion. If you have a question, someone may have already asked it.</li>
</ul>
&nbsp;

<h1></h1>
<h1>Getting Started</h1>
<h2>Codio Setup</h2>
Open the Codio assignment via Canvas.&nbsp; This is necessary to link the two systems.

You will see many files; the directory “obj files for student testing” contains a selection of sample object files you can use for testing your program.&nbsp; Do not assume that we will use these exact files for grading (we won’t).&nbsp; You will need to move these to the root directory in order to test with them.

&nbsp;

<h2>Starter Code</h2>
We have provided a basic framework and several function definitions that you must implement.

<table width="628">
<tbody>
<tr>
<td width="184">lc4.c</td>
<td width="444">– must contain your main function.</td>
</tr>
<tr>
<td width="184">lc4_memory.c</td>
<td width="444">– must contain your linked list helper functions.</td>
</tr>
<tr>
<td width="184">lc4_memory.h</td>
<td width="444">– must contain the declaration of your row_of_memory structure

– must contain the declarations of your linked list helper functions
</td>
</tr>
<tr>
<td width="184">lc4_loader.h</td>
<td width="444">– must contain your loader function declarations</td>
</tr>
<tr>
<td width="184">lc4_loader.c</td>
<td width="444">– must contain your .obj parsing function</td>
</tr>
<tr>
<td width="184">lc4_disassembler.h</td>
<td width="444">– must contain your disassembler function declarations</td>
</tr>
<tr>
<td width="184">lc4_disassembler.c</td>
<td width="444">– must contain your disassembling function</td>
</tr>
<tr>
<td width="184">Makefile</td>
<td width="444">– must contain the targets:

lc4_memory.o

lc4_loader.o

lc4_disassembler.o

lc4

all, clean, and clobber
</td>
</tr>
</tbody>
</table>
&nbsp;

<h2></h2>
<h2>Object File Format Refresher</h2>
The following is the format for the binary .obj files created by PennSim from your .asm files. It represents the contents of memory (both program and data) for your assembled LC-4 Assembly programs. In a .obj file, there are 3 basic sections indicated by 3 header “types” = Code , Data, and Symbol:

<ul>
<li>Code: 3-word header (xCADE, &lt;address&gt;, &lt;n&gt;), n-word body comprising the instructions.
<ul>
<li>This corresponds to the .CODE directive in assembly.</li>
</ul>
</li>
<li>Data: 3-word header (xDADA, &lt;address&gt;, &lt;n&gt;), n-word body comprising the initial data values.
<ul>
<li>This corresponds to the .DATA directive in assembly.</li>
</ul>
</li>
<li>Symbol: 3-word header (xC3B7, &lt;address&gt;, &lt;n&gt;), n-character body comprising the symbol string. These are generated when you create labels (such as “END”) in assembly. Each symbol is its own section.
<ul>
<li>Each character in the file is 1 byte, not 2 bytes.</li>
<li>There is no NULL</li>
</ul>
</li>
</ul>
&nbsp;

<h2>Linked List Structure</h2>
In the file lc4_memory.h, you’ll see the following structure defined:

&nbsp;

The structure is meant to model a single row of the LC4’s memory: a 16-bit address, and its 16-bit contents. An address may also have a label associated with it. Additionally, PennSim always shows the contents of memory in its assembly form. PennSim reverse-assembles the contents and displays the corresponding assembly instruction instead of the binary contents.

Because you will not know the number of instructions in advance, you will create a Linked List of row_of_memory nodes, each node representing a single row of memory.

&nbsp;

<h1></h1>
<h1>Requirements</h1>
<h2>General Requirements</h2>
<ul>
<li>You <strong>MUST NOT</strong> change the filenames of any file provided to you in the starter code.</li>
<li>You <strong>MUST NOT</strong> change the function or struct declarations of any function or struct provided to you in the starter code.</li>
<li>You <strong>MAY</strong> create additional helper functions. If you do, you <strong>MUST</strong> correctly declare the functions in the appropriate header file and provide an implementation in the appropriate source file.
<ul>
<li>You <strong>MUST NOT</strong> to not add any additional .c source or .h header files</li>
</ul>
</li>
<li>Your program <strong>MUST</strong> compile when running the command make.</li>
<li>You <strong>MUST NOT</strong> have any compile-time errors or warnings.</li>
<li>You <strong>MUST</strong> test your code with Valgrind before submission. Valgrind <strong>MUST</strong> report 0 errors and 0 memory leaks.&nbsp; See the details in the <a href="#_heading=h.lv3fp523znre">Valgrind</a> section for required details.</li>
<li>You <strong>MUST</strong> remove or comment out all debugging or error message print statements before submitting.</li>
<li>You <strong>MUST</strong> follow the requirements in the <a href="#_heading=h.tyjcwt">Collaboration</a> section, even if working alone.</li>
<li>You <strong>MUST NOT</strong> use externs or global variables.</li>
<li>You <strong>MAY</strong> use h, stdlib.h, and stdio.h.</li>
<li>Your program <strong>MUST</strong> be able to handle .obj files produced by PennSim.</li>
<li>Your program <strong>MAY</strong> include additional error handling outside the scope of the requirements, but we will not be testing with invalid .obj files.</li>
<li>You <strong>SHOULD</strong> comment your code since this is a programming best practice.</li>
<li>You <strong>MUST</strong> follow the individual requirements for the functions (below).</li>
</ul>
&nbsp;

<h2>Disassembler</h2>
You <strong>MUST</strong> follow the requirements in the source files provided as starter code.

<h3>lc4_memory.c: add_to_list</h3>
This function adds a new row_of_memory node to the LinkedList.

<ul>
<li>If a node with the specified address already exists in the LinkedList, this function <strong>MUST</strong> update the contents field and take no other action</li>
<li>Otherwise, this function <strong>MUST</strong>
<ul>
<li>allocate space for a new node,</li>
<li>set the address and contents fields based on the function arguments,</li>
<li>set the label and assembly fields to NULL,</li>
<li>not allocate memory for the label or assembly fields</li>
</ul>
</li>
<li>If the head pointer is NULL, this function <strong>MUST</strong> set the newly created node as the head of the LinkedList.</li>
<li>Otherwise, this function <strong>MUST</strong> insert the newly created node into the LinkedList based on the address field in ascending order</li>
<li>This function <strong>MUST</strong> return 0 for success, and <strong>SHOULD</strong> -1 if malloc fails</li>
</ul>
&nbsp;

<h3></h3>
<h3>lc4_memory.c: search_opcode</h3>
This function searches the LinkedList until it finds a node where the opcode field matches the opcode argument AND the assembly field is NULL.

<ul>
<li>For this function, the opcode to check for is the four least significant bits of the opcode argument and ranges from 0 to 15</li>
<li>This function <strong>MUST</strong> traverse the LinkedList starting from the head.</li>
<li>If it finds a node where the opcode to check for matches the four most significant bits of the opcode field <strong>AND</strong> the assembly field is NULL, then it <strong>MUST</strong> return a pointer to this node.</li>
<li>This function <strong>MUST</strong> return NULL if no matching node is found in the LinkedList.</li>
<li>This function <strong>MUST</strong> return NULL if the LinkedList is empty.</li>
</ul>
<h3>lc4_memory.c: search_address</h3>
This function searches the LinkedList until it finds a node where the address field matches the address argument.

<ul>
<li>This function <strong>MUST</strong> traverse the LinkedList starting from the head.</li>
<li>If it finds a node where the address to check for matches the address field, then it <strong>MUST</strong> return a pointer to this node.</li>
<li>This function <strong>MUST</strong> return NULL if no matching node is found in the LinkedList.</li>
<li>This function <strong>MUST</strong> return NULL if the LinkedList is empty.</li>
</ul>
<h3>lc4_memory.c: print_list</h3>
This function prints the LinkedList in a specific format.

<ul>
<li>If the head pointer is NULL, this function <strong>MUST</strong> take no action</li>
<li>This function <strong>MUST</strong> print a column title; see the <a href="#_heading=h.y0lz3fq21ca7">Putting It All Together</a> section for an example header.</li>
<li>This function <strong>MUST</strong> print a single line for each node.</li>
<li>If attempting the extra credit, it <strong>MUST NOT</strong> print the assembly field for nodes where the opcode of the contents is not 0001.</li>
<li>It <strong>MUST</strong> print the address and contents fields in hexadecimal with leading zeroes (4 characters wide).</li>
<li>It <strong>MUST</strong> print ONLY the memory list.</li>
<li>The registers in assembly instructions <strong>SHOULD</strong> be separated by a comma
<ul>
<li>g. ADD R1, R2, R3</li>
</ul>
</li>
<li>If the contents of a node are 0, it <strong>MUST</strong> print them as 0 or 0000.</li>
<li>If the assembly of a node is NULL, it <strong>MUST</strong> print the assembly as (null) or leave it blank</li>
<li>It <strong>MUST</strong> print the label when one exists, otherwise it <strong>MUST</strong> leave the section blank.</li>
</ul>
&nbsp;

<h3>lc4_memory.c: delete_list</h3>
This function deletes the LinkedList node by node.

<ul>
<li>This function <strong>MUST</strong> correctly free all allocated memory for each node</li>
<li>This function <strong>MUST</strong> set the head pointer to NULL upon deletion</li>
</ul>
&nbsp;

<h3>lc4.c: main</h3>
The main function <strong>MUST</strong> follow the steps outlined in the starter code.

<ul>
<li>It <strong>MUST</strong> hold the row_of_memory* memory (do not modify this line).</li>
<li>It <strong>MUST NOT</strong> call malloc at any point.</li>
</ul>
&nbsp;

<h3>lc4_loader.c: open_file</h3>
This function opens a file for reading.

<ul>
<li>It <strong>MUST</strong> attempt to open the file file_name.
<ul>
<li>If the file exists, it <strong>MUST</strong> open the file and return a FILE* to the opened file.</li>
<li>Otherwise, it <strong>MUST</strong> return NULL.</li>
</ul>
</li>
<li>You <strong>MUST NOT</strong> attempt to append .obj to the provided file_name</li>
</ul>
&nbsp;

<h3>lc4_loader.c: parse_file</h3>
This function parses a LC4 .obj file.

<ul>
<li>It <strong>MUST</strong> correctly handle endianness. That is, it <strong>MUST</strong> adjust for reading 16-bit words from the file.&nbsp;&nbsp; It <strong>MUST</strong> handle the .obj files that PennSim produces.</li>
<li>For each 3-word header in the file, it <strong>MUST</strong>
<ul>
<li>read the 3-word header,</li>
<li>parse the &lt;directive&gt;, &lt;address&gt;, and &lt;n&gt; words and correctly determine the type of header and memory to allocate,</li>
<li>read the remaining &lt;n&gt; words or bytes,</li>
<li>create a new row_of_memory node,</li>
<li>add the new node to the LinkedList (using the lc4_memory functions)</li>
</ul>
</li>
<li>After reading the file, it <strong>MUST</strong>
<ul>
<li>close the file</li>
<li>return 0</li>
</ul>
</li>
</ul>
&nbsp;

<h3>lc4_disassembler.c: reverse_assemble</h3>
This function disassembles each node to generate a value for the assembly field.

<ul>
<li>It <strong>MUST</strong> search every node in the LinkedList.</li>
<li>If the node’s address is in a CODE region, then it <strong>MUST</strong> do the following:
<ul>
<li>If the opcode is 0001, it <strong>MUST</strong>
<ul>
<li>translate the contents field into the human-readable instruction mnemonic,</li>
<li>allocate space to hold the instruction string, and</li>
<li>store the string into the assembly field</li>
</ul>
</li>
<li>If the node’s address is not in a CODE region, then it <strong>MUST NOT</strong> attempt disassembly</li>
<li>It <strong>MUST</strong> provide an actual label when translating a Branch or Jump instruction into assembly language, not an immediate value. So JMP END, <strong>NOT</strong> JUMP #18.
<ul>
<li>Note that this only applies for extra credit attempts.</li>
</ul>
</li>
<li>After checking all nodes, it <strong>MUST</strong> return 0.</li>
</ul>
</li>
</ul>
&nbsp;

<h2>Extra Credit</h2>
For optional extra credit, build the complete LC4 Disassembler.&nbsp; Your program <strong>MUST</strong> fulfill these additional requirements, while still fulfilling all the requirements for the rest of the assignment:

<ul>
<li>finish the disassembler to translate <strong>all</strong> instructions in the ISA.</li>
<li>create a new output file &lt;user_input&gt;.asm, where &lt;user_input&gt; is the name of the object file without the extension (i.e. create a new file with the .obj extension)</li>
<li>write the equivalent LC4 assembly of the object file to this new output file</li>
<li>PennSim <strong>MUST</strong> be able to assemble this file</li>
<li>PennSim <strong>MUST</strong> be able to load this file into memory</li>
<li>PennSim <strong>MUST</strong> show that the loaded contents your assembled file and the original object file are equivalent</li>
</ul>
&nbsp;

&nbsp;

<h1>Collaboration</h1>
You <strong>are not</strong> required to have a teammate. Points <strong>will not</strong> be deducted if you choose to work alone. If you would like to work as a team, you <strong>MUST</strong> only have <strong>one</strong> teammate.&nbsp; Groups of 3 or more <strong>are not</strong> permitted.

<h2>Collaboration Options</h2>
You have three Options for collaboration:

<ol>
<li><strong>No collaboration</strong>

Complete the assignment independently.&nbsp; You must include a README file that states you worked completely alone.</li>
<li><strong>Collaboration and submit the same code</strong>

After each teammate completes their LinkedList functions, you are free to split up the remainder of the work as you see fit. You can work on everything together or each team member can work on part of the project. Both partners turn in the same code and will receive the same grade. You must include a README file indicating you are submitting the same code, identifying both students, and detailing how you chose to divide up the work (e.g. who contributed what for each function).</li>
<li><strong>Collaboration and submit different code</strong>

If you simply want to be able to discuss your code with a classmate, but prefer to work independently, you may have a teammate but each turn in your own work. You must still include a README indicating you are not submitting the same code along with your teammate’s name and a brief summary of your collaboration process.</li>
</ol>
<h2>Collaboration Requirements</h2>
If you choose to work as a team, each team member <strong>MUST</strong> follow these additional assignment requirements:

<ol>
<li><strong>Each team member must complete all 5 functions supporting the </strong><strong>LinkedList</strong><strong> data structure independently.</strong>

This is a core learning experience of the project and conquering it on your own will serve you well in your future work. The remainder of the work, requirements 2 through 5 below, may be split between you in any way that you and your partner agree upon. The entire lc4_memory.c source file must be written by you alone as an individual project.</li>
<li><strong>After you have completed the LinkedList file on your own, you may work with your partner to finalize a version of </strong><strong>lc4_memory.c</strong><strong> that will be used by your submitted program.

</strong>You will likely find that you need to make changes to your lc4_memory.c source file as a result of tests conducted by you and your partner. Implementing the LinkedList functions on your own is an invaluable learning experience, but once you have completed the functions, you are free to discuss them with your partner and refine the final version for submission.</li>
<li><strong>Each function MUST include a comment at the top with the name of the person who authored it.

</strong>If there is anything more you think we should know about your submission, it should be included in your README file.</li>
<li><strong>Each team must submit a brief </strong><strong>README</strong><strong> file that describes which Collaboration Option you chose and your division of labor.

</strong>If you are doing Option 1, you <strong>MUST</strong> indicate that you worked alone.

If you are doing Option 2, you <strong>MUST</strong> include both your and your teammate’s names and specify who wrote each function.

If you are doing Option 3, you <strong>MUST</strong> to include both your and your teammate’s name and a brief (a few sentences max) description of how you worked together.The README should not be more than one page in length.</li>
</ol>
We strongly recommend that you and your teammate work together to test, debug, and fix memory leaks in your code.

<h2>Collaboration Tips</h2>
Here are some suggestions to discuss with your partner before starting. These are ideas that other students have found helpful but they are not required.

<ul>
<li><strong>Discuss your preferred communication platforms.</strong>

Do you like to use Slack? Email? Text messages? Regular video calls on Slack or Zoom? Pick something you will be able to check daily to help your collaborator with debugging challenges as they arise.</li>
<li><strong>Most people appreciate updates about when you plan to work on the assignment.</strong>

Letting your teammate know that you plan to do most of your work over the weekend, for example, demonstrates a commitment to the work and helps set expectations for people with different working schedules. If you prefer to leave work until the last minute, your teammate deserves to know this (we recommend starting as early as possible).</li>
<li><strong>Assign roles as soon as possible.</strong>

It should be clear who is responsible for writing which sections of the code before you start the project. Consider writing the README first and updating it if necessary.</li>
<li><strong>Review the assignment instructions (again).</strong>

Consider which parts you think will be the most challenging and which parts you feel the most confident in. Try to split up the work so that each person has at least one challenging section and one section they feel confident in. This allows each person to contribute their individual skills while also having opportunities to learn new things.</li>
<li><strong>Plan to check in multiple times.</strong>

This is a large project and it won’t be done in a few hours and probably not in a few days.</li>
<li><strong>Plan at least one day to debug and fix memory leaks before turning in the assignment.

</strong>While you will be primarily graded on functionality, it is important that you learn to use malloc and free correctly and that you learn to use Valgrind to find and eliminate any memory leaks. Code that contains memory leaks will not receive full credit.</li>
<li><strong>Whenever possible, try to explain your work to your teammate in your own words.

</strong>Explaining your code to someone else is a great learning tool for both people!</li>
<li><strong>Back up your work to Codio frequently.</strong></li>
<li><strong>Check in with your teammate before making changes to code your teammate has written.</strong>

Discuss the change. You both may learn something by discussing their implementation.</li>
</ul>
&nbsp;

<ul>
<li><strong>Communicate when asking for an extension.</strong>

If you need an extension for some reason, be sure to mention that you are working with a partner for this assignment and they also need the same extension. Your partner should fill out an extension request with the same information.&nbsp; This will ensure that you and your partner have the same due date.</li>
</ul>
<h1></h1>
<h1>Suggested Approach</h1>
This is a <em>suggested</em> approach.&nbsp; You are not required to follow this approach as long as you follow all of the other requirements.

<h2>High Level Overview</h2>
Follow these high-level steps and debug thoroughly before moving on to the next.

<ol>
<li>Create a pointer-based framework in C to hold a LinkedList by writing the following functions:
<ol>
<li>A function to create a new node in the LinkedList. If this is the first node in the list, this function will create a new list. If there is already an identical node in the list, this function will update the contents of that pre-existing node.</li>
<li>A function to search the LinkedList for a node with a specific memory address value.</li>
<li>A function to search the LinkedList for a node with a specific opcode that has not yet been assigned an assembly instruction.</li>
<li>A function to print the elements of the list in the specified format.</li>
<li>A function to delete the entire list and free the memory it was using.</li>
</ol>
</li>
<li>Write the open_file function to open a .OBJ file specified by the user via the command line.</li>
<li>Write the parse_file function to extract information from the open file, place the information into your LinkedList, and close the file.</li>
<li>Write the reverse_assemble function to update each node in your LinkedList with the assembly language equivalent of the binary strings extracted by parse_file.</li>
<li>Print your LinkedList.</li>
<li>Debug and resolve any lingering memory leaks and other memory management errors.</li>
</ol>
<h2></h2>
<h2>Great High Level Overview, but I really need a Slightly More Detailed Overview</h2>
Okay, I guess we can give some more details.

<h3>Implement the LinkedList</h3>
The first thing to do is to get the LinkedList working, that is, create the list, place new nodes into the correct position, etc.

The first files to view in the helper file are lc4_memory.h and lc4_memory.c. In these files you will notice the structure that represents a row_of_memory as referenced in the <a href="#_heading=h.f0lbvapby1i3">LinkedList</a> section. You will also see several helper functions that will serve to manage a LinkedList of rows_of_memory nodes.

Your job is to implement these LinkedList helper functions using your knowledge from the last assignment. You must implement everything described by the comments in the starter code

If you wish to implement additional helper functions, feel free to add them to any .c source file but remember to add the function prototypes to the appropriate .h header file.

&nbsp;

<h3>Setup the main Function</h3>
Accept arguments and pass them to the functions.&nbsp; Set up the general flow of high-level functions.

Switch to modifying the file called lc4.c<strong>.&nbsp; </strong>This serves as the main function for the entire program.

The head of the linked list must be stored in main.&nbsp; Notice that a pointer named memory will do just that.

main then extracts the name of the .obj file the user has passed in when they ran your program (this is in the argv[] parameter).

Next, it calls lc4_loader.c’s open_file function and holds a pointer to the open file.

Then, it calls lc4_loader.c’s parse_file function to read and interpret the .obj file.

Lastly, it disassembles the file, prints the LinkedList to the terminal, deletes the LinkedList, and finally terminates the program.

All of these functions are described in greater detail in later subsections.

&nbsp;

&nbsp;

We have provided the order of the function calls and their purpose as shown in comments in the lc4.c.&nbsp; Once you have properly implemented lc4.c and have it accept input from the

command line, a user should be able to run your program as follows:

./lc4 &lt;my_file&gt;.obj

where &lt;my_file&gt; can be replaced with any file name the user desires as long as it is a valid .obj file that was created by PennSim. If no file is passed in, your program should generate an error telling the user what went wrong, like this:

error1: usage: ./lc4 &lt;object_file&gt;.obj

&nbsp;

<h3>Implement the LC4 Loader</h3>
The loader is responsible for reading a file, parsing each line, and creating/modifying nodes.&nbsp; Most of the work of your program will take place in the file: called lc4_loader.c.

In this file, start by implementing the function open_file to take in the name of the file the user of your program has specified on the command line (see lc4_loader.h for the definition of open_file). If the file exists, the function should return a handle to that open file, otherwise a NULL should be returned.

Also in lc4_loader.c, implement a second function, parse_file<strong>, </strong>that will read in and parse the contents of the open .obj file as well as populate the LinkedList as it reads the .obj file. The format of the .obj input file has been described in lecture, but its layout has been reprinted above in the <a href="#_heading=h.6bisvzex9z5c">Object File Format Refresher</a> section.

As shown in the <a href="#_heading=h.ghnqbgxbejm9">Flowchart</a>, have the function read in the 3-word header from the file. You’ll notice that all of the LC4 .obj file headers consist of 3 fields: &lt;type&gt;, &lt;address&gt;, and &lt;n&gt;. As you read in the first header in the file, store the address and the &lt;n&gt; field into local variables. Then determine the type of header you have read in: CODE, DATA, or SYMBOL.

<h4>The CODE header</h4>
The body of the CODE section is &lt;n&gt;-words long.&nbsp; This is a sample CODE section:

<table width="547">
<tbody>
<tr>
<td width="547">CA DE 00 00 00 0C 90 00 D1 40 92 00 94 0A 25 00 0C 0C 66 00 48 01 72 00 10 21 14 BF 0F F8</td>
</tr>
</tbody>
</table>
Notice the field for &lt;n&gt; is 0x000C, or decimal 12. Because each instruction in LC4 is 1 word long, this indicates that the next 12 words in the .obj file are 12 LC4 instructions.

The first LC4 instruction in the 12-word body is: 0x9000 which is a CONST assembly instruction if you convert to binary.

Allocate memory for a new node in your linked list to correspond to the first instruction. As it is the first instruction in the body, and the address has been listed as 0x0000, you would populate the row_of_memory structure as follows:

<table width="188">
<tbody>
<tr>
<td width="101">address</td>
<td width="87">0000</td>
</tr>
<tr>
<td width="101">label</td>
<td width="87">NULL</td>
</tr>
<tr>
<td width="101">contents</td>
<td width="87">9000</td>
</tr>
<tr>
<td width="101">assembly</td>
<td width="87">NULL</td>
</tr>
<tr>
<td width="101">next</td>
<td width="87">NULL</td>
</tr>
</tbody>
</table>
In a loop, read in the remaining instructions from the .obj file; allocate memory for a corresponding row_of_memory node for each instruction. As you create each row_of_memory, add these nodes to your linked list, ordering the list by address (you should use the functions you’ve created in lc4_memory.c to help you with this).

For the first 3 instructions listed in the sample above, your linked list would look like this:

&nbsp;

<h4>The DATA Header</h4>
The procedure for reading in the DATA sections is identical to reading in the CODE sections. These would become part of the same linked list since PROGRAM and DATA are all in one memory on the LC4; they are partitioned by address.

<h4>The SYMBOL Header</h4>
For the following SYMBOL header/body:

<table width="283">
<tbody>
<tr>
<td width="283">C3 B7 00 00 00 04 49 4E 49 54</td>
</tr>
</tbody>
</table>
The address field is: 0x0000. The symbol field itself is 0x0004 bytes long. The next 4 bytes 0x49 0x4E 0x49 0x54 are ASCII for INIT. This means that the label for address: 0000 is INIT. Your program must search the LinkedList nodes, find the appropriate address that this label is referring to, and populate the label field for the node. Note: &lt;n&gt; tells us exactly how much memory to malloc to hold the string, however, you must add a byte to hold the NULL terminator. For INIT, this means you need to allocate 5 bytes.

For the example above, the node 0000 in your LinkedList, would be updated as follows:

<table width="197">
<tbody>
<tr>
<td width="103">address</td>
<td width="94">0000</td>
</tr>
<tr>
<td width="103">label</td>
<td width="94">INIT\0</td>
</tr>
<tr>
<td width="103">contents</td>
<td width="94">9000</td>
</tr>
<tr>
<td width="103">assembly</td>
<td width="94">NULL</td>
</tr>
<tr>
<td width="103">next</td>
<td width="94"></td>
</tr>
</tbody>
</table>
It may be that you come across a label for an address that has not yet been created in your linked list. In this case, create a new node, add the label and set the contents field to 0. The other node fields must be left blank for the time being. They will be eventually updated.

It is possible that an address has two labels in the .obj file. In this case, use the last one that appears in the .obj file.

Once you have read the entire file, created and added the corresponding nodes to your LinkedList by address order, close the file and return to main. If you encounter an error in closing the file, print an error, free all the memory associated with the LinkedList, and then exit the program.

&nbsp;

<h3>Implement the Disassembler</h3>
Go through the row of memory nodes and update the assembly field based on the contents.

In lc4_disassembler.c, write a third function reverse_assemble that will take as input memory the head of the LinkedList populated in the previous section. reverse_assemble must translate the hexadecimal representation of selected instructions into their assembly equivalent. Refer to the <strong>LC4 ISA Instruction</strong> document for details.

To simplify this problem a little, <strong>do not</strong> translate every single instruction into its assembly equivalent.&nbsp; Only translate instructions with the opcode of 0001, that is, ADD REG, MUL, SUB, DIV, and ADD IMM.

The immediate value MUST be prefixed with #, x, or X, (as appropriate), for example

ADD R1, R1, #10 == ADD R1, R1, xF == ADD R1, R1, XF

Do not translate data stored at an address in the DATA section.

As shown in the flowchart, this function will call your linked list’s search_opcode helper function. Your search_opcode function should take as input a 4-bit value representing the opcode to search for and return the first node in the LinkedList that matches the opcode and also has a NULL assembly field.

For example, here’s the definition of an ADD instruction from the ISA:

<strong>0001</strong> ddds ss00 0ttt

When searching for an opcode instruction with opcode == 0001, the opcode parameter passed to search_opcode must be:

0000 0000 0000 <strong>0001</strong>

So you will need to use the <a href="#_heading=h.zj5njymjq2c">C-bitwise operators</a> to line these two values up before comparing them.

search_opcode finds the first instruction in the LinkedList where these two 4-bit fields match with that additional constraint that rows_of_memory that already have the assembly instruction filled in doesn’t count as a match.

When/if a node in your linked list is returned, you’ll need to examine the contents field of the node and translate the instruction into its assembly equivalent. Once you have done that, allocate memory for the ASCII string and store this string in the assembly field of the node. Repeat this process until all the nodes in the LinkedList with an opcode == 0001 have their assembly fields properly translated.

As an example, the figure below shows a node on your list that has been “found” and returned when the search_opcode function was called.

From the contents field, we can see that the hexadecimal value 0x128B which is <strong>0001</strong> 001 010 001 011 in binary. From the ISA, we realize the sub-opcode reveals that this is actually a MUL instruction. We can then generate the string “MUL R1, R2, R3” and store it back in the node in the assembly field. For this work, we strongly encourage you to investigate the switch statement in C (any good book on C will help you understand how this works and why it is more practical than multiple if/else/else/else statements).

&nbsp;

<h3>Putting It All Together</h3>
One last thing to do in main is to call a function to print the contents of your LinkedList to the screen. So call the print_list function in lc4_memory.c. You will need to implement the printing helper function to display the contents of your lc4’s memory list like this:

<table width="494">
<tbody>
<tr>
<td width="116">&lt;label&gt;</td>
<td width="101">&lt;address&gt;</td>
<td width="124">&lt;contents&gt;</td>
<td width="153">&lt;assembly&gt;</td>
</tr>
<tr>
<td width="116">INIT</td>
<td width="101">0000</td>
<td width="124">9000</td>
<td width="153"></td>
</tr>
<tr>
<td width="116"></td>
<td width="101">0001</td>
<td width="124">D140</td>
<td width="153"></td>
</tr>
<tr>
<td width="116"></td>
<td width="101">0002</td>
<td width="124">9200</td>
<td width="153"></td>
</tr>
<tr>
<td width="116"></td>
<td width="101">…</td>
<td width="124"></td>
<td width="153"></td>
</tr>
<tr>
<td width="116"></td>
<td width="101">0009</td>
<td width="124">128B</td>
<td width="153">MUL R1, R2, R3</td>
</tr>
<tr>
<td width="116">END</td>
<td width="101">000A</td>
<td width="124">0</td>
<td width="153"></td>
</tr>
<tr>
<td width="116">(and so on…)</td>
<td width="101"></td>
<td width="124"></td>
<td width="153"></td>
</tr>
</tbody>
</table>
&nbsp;

<ol>
<li>There may be very long labels so that the other entries in that row are pushed to the right. That is fine.</li>
<li>You may find the formatting strings “%-20.04x” and “%-20s” useful in keeping your output aligned. This isn’t critical but it is definitely easier to read.</li>
</ol>
<h1>Testing</h1>
<h2>Files for Testing</h2>
In the last assignment, you created a .obj file. Try loading that file into the Codio workspace for this assignment and use your lc4 program on it. You know exactly how that program should disassemble.

To test further, bring up PennSim, write a simple program in it, output a .obj from PennSim, then read into your program and see if you can disassemble it. You can create a bunch of test cases very easily with PennSim.

You should test your lc4 program on a variety of .obj files, not just simple examples. We have provided a selection of .obj files in the “<u>obj files for student testing</u>” folder in the Codio workspace.&nbsp; Additionally, this directory contains .sol solution file which are the expected output.&nbsp; You can compare the expected output to your output to see if you are getting the expected results.

You may find it easier to copy PennSim.jar and the test files into the submit directory, so everything is in one place.

From the default home workspace directory (when the terminal prompts ends with ~, you will need to use cd submit to change the directory to the submit directory.

&nbsp;

<h2>Unit Testing</h2>
When writing such a large program, it is a good strategy to “unit test.” This means, as you create a small bit of working code, compile it, and create a simple test for it.

As an example, once you create your very first function: add_to_list, write a simple main and test it out. Call it, print out your “test” list, and see if this function even works. Run valgrind on the code, see if it leaks memory or accesses uninitialized memory locations. Once you are certain it works, and doesn’t leak memory, go on to the next function search_address, implement that, and test it out.

<strong>DO NOT</strong> write the entire program, compile it, and then start testing it. You will never resolve all of your errors this way. You need to unit test your program as you go along or it will be impossible to debug.

&nbsp;

<h2>GDB for Debugging</h2>
Using gdb to debug your program is also highly recommended and is actually required before asking for help on ED or during office hours.&nbsp; The first thing the TAs will ask is if you have done this; if not, they will ask you to do it.&nbsp; This is a required part of the learning experience and you’ll want this skill to succeed in 595.

While it may seem easy to use print statements, they quickly clutter your program and require commenting out/deleting when you no longer need them (and inevitably uncommenting/undeleting when you need to debug again).

gdb allows you to inspect the actual contents of memory which is an advantage over print statements because print statements only print ASCII characters.&nbsp; Further, you can see the actual contents of memory of any variable at any time, while print statements only print when you call the print statement during the execution of your program.

Plus, you’ll have to use it for 595 so you may as well get some practice in now.

<h3>Segmentation Faults Demystified</h3>
Segmentation faults are VERY common failures in C programs. They can be hard to pin down.&nbsp; First we should understand why they happen:

Segmentation faults are a common class of error in programs written in languages like C that provide low-level memory access. They arise primarily due to errors in the use of pointers for memory addressing, particularly illegal access. There are two common cases:

<ol>
<li>Case 1: trying to dereference a NULL pointer. This often happens when calling a function that returns a pointer or NULL in case of error. If you don’t check the return value from the function and then proceed to dereference the pointer, you will get a segmentation fault.</li>
<li>Case 2: an incorrect assumption that memory on the stack (and heap) is initialized to zero. This is NOT the case. If you want the memory to be initialized to zero, you need to do this explicitly, possibly using the memset function. You might have code that checks to see if the memory is 0 or NULL and then take some action based on this. If the memory is not initialized to zero, it will have random, unpredictable contents. This is often referred to as (X) or “don’t care” in the lectures.</li>
</ol>
So, how do you figure out where the segmentation fault is occurring? The simplest way to find out is using GDB. After compiling using the -g option and running the program, run the program with arguments (the gdb commands start and run allow you to specify the command line arguments), and you should go right to the segmentation fault. You can then use the gdb where command which will tell you the line number in your program where the failure occurs.

&nbsp;

For example:

<table width="232">
<tbody>
<tr>
<td width="232">gdb -q -tui –args ./lc4 test1.obj</td>
</tr>
<tr>
<td width="232">(gdb) run</td>
</tr>
</tbody>
</table>
runs gdb on your lc4 program with argv[1] set to test1.obj

&nbsp;

<h2></h2>
<h2>Valgrind for Memory Leaks and Memory Management Errors</h2>
Prior to exiting your program, you MUST properly free any memory that you allocated. We will be using a memory-checking program known as valgrind to ensure your code properly releases all memory allocated on the heap.&nbsp; Simply run your program, lc4, as follows:

valgrind –leak-check=full –track-origins=yes ./lc4 test1.obj

where valgrind is the name of the program to run,

–leak-check=full is a Valgrind option to perform the full memory leak analysis,

–track-origins=yes is a Valgrind option to show you where some errors originate from,

./lc4 is the name of the program that Valgrind will analyze,

and test1.obj is the argument to your lc4 program, i.e. the name of the .obj file you want to disassemble.

<ul>
<li>You <strong>MUST</strong> watch the video “TA Demo: Debugging in C (Valgrind)”, and learn how to use Valgrind.</li>
</ul>
&nbsp;

<ul>
<li>Valgrind will find errors related to accessing uninitialized memory locations (invalid read/write errors). This typically results from assuming that malloc zeroes out the memory it returns. malloc <strong>DOES NOT</strong> do this.</li>
<li>Valgrind will find errors when you access memory locations outside a range allocated for an array or string (a second kind of read/write error). While your program may appear run correctly on your test cases when you have these errors, the results are unpredictable and may cause the test cases run by the autograder to fail.</li>
</ul>
&nbsp;

<h1></h1>
<h1>Submission</h1>
<h2>README file</h2>
Whether you worked alone or with a teammate you <strong>MUST</strong> submit your code with a README file before submitting it (see the <a href="#_heading=h.3shvlnqondjz">Collaboration</a> section).&nbsp; The autograder will be checking for the presence of this file and the TAs will read them.&nbsp; You may be contacted in the discussion board’s Chat feature if something needs clarification.

<h2>Submission Check</h2>
There is a single “submission check” test that runs once you upload your code to Gradescope.&nbsp; This test checks that you have submitted all required files and also that your program compiles and any autograder code compiles successfully.&nbsp; It does not run your program or provide any feedback on whether it works or not.&nbsp; This check just ensures that all the required components exist.&nbsp; This test is performed after uploading to Gradescope.

Ensure that you are passing this check before closing Gradescope.&nbsp; If you are not passing this check, please reach out to TAs for troubleshooting assistance.

&nbsp;

<h2>Consistency Checks</h2>
The autograder also will run three of the actual tests and provide feedback.&nbsp; These are add_to_list.2, search_opcode.3, and reverse_assemble.2.&nbsp; This is for a basic consistency check that your program runs.&nbsp; The remaining tests are hidden until manually published after the deadline.&nbsp; Be sure these submission-visible tests are passing before closing Gradescope.

&nbsp;

<h2>The Actual Submission</h2>
You will submit this assignment to Gradescope in the assignment entitled <strong>Assignment 12: The LC4 Disassembler</strong>.

Download the required .c source and .h header files (as well as any additional helper files required) as well as your Makefile and README from Codio to your computer, then upload all of these files to the Gradescope assignment.

Do not not submit intermediate files (anything .o).

You have unlimited submissions until the deadline, after which late penalties apply as noted in the syllabus.

We will only grade the last submission uploaded.

If you are working with a partner, you <strong>MUST</strong> also click the “View or edit group” link in the upper right of the submission page to add your partner.&nbsp; We will adjust these based on the README content, but give your partner peace of mind by including them at submission time.

Do not mark your Codio workspace complete.&nbsp; Only the submission in Gradescope will be used for grading purposes.

There is no page matching and no academic integrity submission for autograder assignments.

<h1></h1>
<h1>Grading</h1>
We will only grade the last submission, regardless of the results of any previous submission.

We will not be providing partial credit for autograder tests.

You may ask for feedback by submitting a regrade request using the Miscellaneous Adjustments rubric item.

<h2>Disassembler</h2>
We will only use valid, disassemblable .obj files.&nbsp; We will not test your program with deliberately faulty .obj files.

<h3>Makefile</h3>
05 points

As part of the submission check, the autograder will ensure that you have submitted all the required files and that makefile correctly creates the final executable.

<h3>Unit Tests</h3>
50 points

The autograder will test your open_file, add_to_list, delete_list, search_address, search_opcode, and reverse_assemble functions by providing inputs directly to these functions.&nbsp; The autograder will deduct points if they do not produce the correct output.

Do note that the autograder provides feedback for one test of add_to_list, one test of search_opcode, and one test of reverse_assemble as a baseline consistency check.&nbsp; The remaining tests are hidden until manually published after the deadline.

<h3>Integration Tests</h3>
45 points

The autograder will test against our (hidden) .obj files.&nbsp; The autograder is checking for correct output from the print_list function.&nbsp; The autograder will deduct points if it does not produce the correct output.&nbsp; All of these tests are hidden until manually published after the deadline.

<h3>Valgrind deductions</h3>
Each Valgrind error deducts 1.0 points from the score.&nbsp; This caps at 10.0 points for Unit Tests and 10.0 points for Integration Tests.&nbsp; Overall, the maximum deduction for Valgrind errors is 20.0 points.&nbsp; This deduction is hidden until manually published after the deadline.

<h3></h3>
<h3>Extra Credit</h3>
The Extra Credit is worth 15 percentage points so the highest grade on the assignment is 115%.

Your extra credit <strong>MUST NOT</strong> break functionality for the non-extra credit requirements.&nbsp; Make a backup of your finalized program before attempting the extra credit.&nbsp; If your program fails to meet the basic requirements, you will end up losing more points than the extra credit would gain.

There is no partial credit.&nbsp; It must work completely for any credit.

We will not give guidance on how to do this since it is designed to be capstone challenge problem.

&nbsp;

<h2>An Important Note of Plagiarism</h2>
<ul>
<li>We will scan your assignment files for plagiarism using an automatic plagiarism detection tool.</li>
<li>If you are unaware of the plagiarism policy, make certain to check the syllabus to see the possible repercussions of submitting plagiarized work (or letting someone submit yours).</li>
</ul>
<h1></h1>
<h1>Flowchart</h1>
As a tool to assist, we are providing a <em>suggested</em> flowchart as an overview of the program operation.&nbsp; You may choose your own implementation, as long as it works.

<h1>FAQ</h1>
<h2>Quick Hints</h2>
These are some hints provided by TAs and Ira.

<ul>
<li>You are able to distinguish code vs. data simply based on the address of the entry (see the LC4 Memory Map from lecture).</li>
<li>You can assume that the maximum length of an assembly instruction is 100, the maximum length of a label is 70 and the maximum length of a file_name is 100.</li>
<li>Make sure all of your loops that traverse the memory list look at the first and last element of the memory list. This is a VERY common mistake.</li>
<li>You do not have to check that the addresses in the .obj file are valid. That is, addresses for CODE memory will always be after a .CODE directive, and addresses for DATA memory will always be after a .DATA directive.&nbsp; Essentially, all test files will be valid LC4 object files.</li>
</ul>
<h2>Useful Commands</h2>
<ul>
<li>The hexdump -C command displays an .obj file one byte at a time rather than one word at a time. The first column displayed by hexdump is the byte offset.</li>
</ul>
<h2>Programming Tips</h2>
<ul>
<li>Do not ignore warning messages displayed in Codio. Understand them and address the issues by modifying your code. Ask the TAs if you don’t know what a warning means.</li>
<li>There are many possible errors and we will not check them. But you should as part of debugging and ensuring your program does have the correct output.&nbsp; Some example errors:
<ul>
<li>the input file isn’t validly formatted</li>
<li>malloc can’t find sufficient memory</li>
<li>etc

It is a best practice to print an error message and exit if any of those things happen but the autograder will not be testing those sort of edge cases.</li>
</ul>
</li>
<li>While we want your program to have no memory leaks, it is more important that your program actually runs. Get the program working, then go back and fix memory leaks.</li>
<li>You must allocate memory for strings before calling strcpy.</li>
<li>add_to_list must keep the memory list in sorted order by address. CODE DATA isn’t relevant.</li>
<li>The feof function may not work the way you think it should. The eof indicator only returns TRUE <em>after</em> you have attempted to read past the end of the file. If the file position is right at the end of the file but you haven’t tried to read past the end of the file yet, feof will be FALSE. This means that you need to check all of your calls to fread or fgetc to make sure they didn’t hit the end of the file.</li>
</ul>
<h2>Endianness</h2>
<ul>
<li>The x86 (the processor used by Codio) has a different endianness than the LC4. When doing fread’s of 2 byte words, swapping occurs to adjust for this. That same swapping doesn’t occur with the fgetc or fread’s with size 1.</li>
<li>If you read the .obj file into memory one word at a time using fread, you will need to swap for endianness. In contrast, if you choose to read the .obj file into memory one byte at a time with fgetc, the endianness doesn’t need to be adjusted. However, you will have to combine two bytes into a word using bitwise operators.</li>
</ul>
&nbsp;

<h1>Resources</h1>
<ul>
<li>Valgrind documentation

<a href="https://www.valgrind.org/docs/manual/quick-start.html#quick-start.interpret">https://www.valgrind.org/docs/manual/quick-start.html#quick-start.interpret</a></li>
<li>C bitwise operators may greatly simplify your implementation

<a href="https://www.tutorialspoint.com/cprogramming/c_bitwise_operators.htm">https://www.tutorialspoint.com/cprogramming/c_bitwise_operators.htm</a></li>
<li>Checking end of file <a href="https://faq.cprogramming.com/cgi-bin/smartfaq.cgi?id=1043284351&amp;answer=1046476070">https://faq.cprogramming.com/cgi-bin/smartfaq.cgi?id=1043284351&amp;answer=1046476070</a></li>
<li>C Bitwise Operators in Canvas

[no link since this changes every semester]</li>
</ul>
&nbsp;

&nbsp;
