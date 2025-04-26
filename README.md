# cs2200-homework-4-random-message-generator-solved
**TO GET THIS SOLUTION VISIT:** [CS2200 Homework 4-Random Message Generator Solved](https://www.ankitcodinghub.com/product/cs2200-1-28/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126876&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2200 Homework 4-Random Message Generator Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In this homework, you will be implementing an arraylist and debugging code for a “Random Message Generator.”

The files we provided include:

• main.c: main functions that generate the random message

• main.h: header file of the main function

• arraylist.c: functions that are used to manipulate the ArrayList (used by main.c)

• arraylist.h: header file of ArrayList data structure

• arraylisttest.h: header file for the tests for the arraylist data structure.

• arraylist test.c: functions for testing the the arraylist data structure

• Makefile: A script that can be used for compiling the code (optional).

You will be modifying arraylist.c, main.c, and main.h for this homework. Before completing the various parts of this homework, read all the relevant files, and fill in your name and GTID at the top.

2 Part 1: Implement taking in parameters from command lines

First, let’s knock out taking in arguments from the command line. There will be two command line arguments for this program. This code should be written in the main method in the main.c file. Look for inline comments that will describe where you should implement your code. The arguments are:

• t triggers the program to run the unit tests on the arraylist rather than generating a random message.

• l sets the length of the message that the program will generate.

We highly recommend using the getopt() function. The method head looks like this:

getopt(int argc, char *const argv[], const char *optstring)

where argc is the argument count, argv is argument array, and optstring is the specified list of characters, each representing a single character option. If the character in opstring is followed by ’:’, the corresponding option will take in an argument, and that argument will be pointed by optarg.

This function will return the next option character (if one is found) from argv that matches a character in optstring. If no character in argv is in optstring or there is a missing argument, it will return ’?.’ If we set the first character of optstring to be ’:’ and we encounter a missing argument situation, it will return ’:’ instead. Otherwise, it will return -1 which indicates that all option characters have been parsed.

2.1 Deliverable 2: GDB Snapshots

Your screenshot should include the following:

1. Setting the breakpoint at the appropriate line to print the values stored in variables length and tests

2. Running the program in gdb with appropriate arguments

3. Printing the values of length and tests

4. Delete the breakpoint you set above.

2.2 Compiling and Running

In the future, we will provide you with a Makefile for compiling your programs. However, for this assignment, we want you to be aware of how C programs are actually compiled. To compile a program you’ll use the gcc compiler. To use the gcc compiler use the following format:

• gcc PATH/TO/C/FILE PATH/TO/C/FILE … -o PROGRAM NAME

Or if you’re compiling to debug with gdb:

• gcc -g PATH/TO/C/FILE PATH/TO/C/FILE … -o PROGRAM NAME

To run the program you will simply need to type the path to your program. One thing to note is that you will have to put “./” before the filename if you are in the same directory as your program. For example, if you use the name Word Generator:

• From same directory: ./Word Generator -l 10

• From different directory: ./PATH/…/Word Generator -t

3 Part 2: Implement the ArrayList methods

Next, implement the functions for the ArrayList data structure in arraylist.c:

• create arraylist: Taking the capacity of the arraylist as an input, create an ArrayList using the backing array with type ** char. Remember to use malloc() to allocate space for the storage of the ArrayList. The function should return a pointer to the ArrayList you created.

• add at index: Add a word to ArrayList at a specific index. If the length of the ArrayList is going to exceed the capacity, resize the ArrayList to twice its original capacity. You can call resize(), which is also a function you will implement, to do this.

• append: Add a word to the end of the ArrayList. Remember to resize as required in add at index.

• remove from index: Remove a word from the ArrayList at a certain index and return the word removed. Make sure to maintain the ArrayList contiguous.

• resize: Resize the backing array to hold twice its original capacity. It should now support arraylist-&gt;capacity∗ 2 elements.

• destroy: Destroy the ArrayList by freeing the ArrayList itself and its backing array.

Please refer to the comments in arraylist.h for further guidelines. Also note that arraylist.c is almost blank. In short, you need to implement the functions defined in arraylist.h. Think of arraylist.h as the interface that your code is expected to comply with. If your code passes the arraylist tests sanity tests and your word generator gives the expected output, then your code should be good. We reserve the right to review the code to ensure that your implementation is not hard coded or incorrect (i.e. implemented a link list instead of an array list).

4 Part 3: Debug the main file

For the last part of the project, you will need to debug the provided code in main.c and main.h. This code is used to create a “random word generator” that, in short, draws several random words from an array called “Dictionary”. There are 3 problematic lines of code that are causing problems located somewhere throughout the provided code. If you get stuck look for the comments for hints! This section is to prepare you for debugging C code on your projects that are much larger and more complex than this code.

The intended output from the program is:

• -l 5: Message: this tea Half is nothing

• -l 10: Message: this tea is nothing more Half than hot leaf juice

• -l 15: Message: this tea is nothing more than hot Half leaf juice cs2200 rocks momo secret tunnel

The output shown above should be the only output onto stdout (or stderr) that your program makes when the l argument is used. When the t argument is used only the outputs of the arraylist tests should be shown on stdout (or stderr). We will not run your program with both the t and l arguments used simultaneously.

If this part seems tedious, often small bugs that are easily overlooked lead to headaches on the projects. Hopefully, this practice will allow you to locate them easier in the future.

4.1 GDB Debugging Tips

If your program is crashing or misbehaving, you can use GDB to locate the bug. GDB is a command line interface that will allow you to set breakpoints, step through your code, see variable values, and identify segfaults. There are tons of online guides, click here (http://condor.depaul.edu/glancast/373class/docs/gdb.html) for one.

First (after compiling with the -g flag) load your binary file into GDB using:

$ gdb &lt;file name&gt; or in our case $ gdb Word Generator

Within GDB, you can run your program with the run command:

$ (gdb) r &lt;command line arguments&gt; Which in our case is either one of these:

$ (gdb) r -t

$ (gdb) r -l &lt;# of words&gt;

$ (gdb) break main.c:53 ! set breakpoint at call to system init

$ (gdb) r -l &lt;# of words&gt;

! (wait for breakpoint)

$ (gdb) s ! step into the function call

or by using the actual function name being called from the main loop:

$ (gdb) break sim cmd ! set breakpoint at call to sim c

$ (gdb) r -l &lt;# of words&gt;

! (wait for breakpoint)

$ (gdb) s ! step into the function call

$ (gdb) x/24xb frame table

0x1004000aa: 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00

0x1004000b2: 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00

0x1004000ba: 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00

The format of this command is x/nfu [memory location], where n is the number of items to print, f is a formatting identifier, and u is the specifier for the units you would like to print. b specifies 1 byte, h specifies 2 bytes, w specifies 4 bytes, and g specifies 8 bytes.

If you use the corruption checker, you can set a breakpoint on panic() and use a backtrace to discover the context in which the panic occurred:

$ (gdb) break panic

$ (gdb) r -i &lt;# of words&gt;

! (wait for GDB to stop at the breakpoint)

$ (gdb) backtrace

$ (gdb) frame N ! where N is the frame number you want to examine

Lastly, you can use gdb to see the value of a variable without print statements using:

$ (gdb) print &lt;variable name&gt;

5 Submission

Files you will submit on Gradescope:

• Your GDB snapshots

• arraylist.c

• main.c

• main.h
