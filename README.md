Download Link: https://assignmentchef.com/product/solved-ence360-assignment-multi-thread-downloader-main
<br>
Your task is to write (some parts of) a multi-threaded HTTP multipart downloader program.

There are two parts:

Part 1 – a minimal HTTP client

Part 2 – a concurrent queue using semaphores.

Part 3 – determining chunk sizes and the number of partial downloads required

Part 4 – merging &amp; removing partial content files

A downloader is written in terms of these parts and you will do some analysis and write a short report.

All the programs can be compiled using a Makefile provided simply by going to the base directory where you unpack the assignment and typing ‘<strong>make</strong>‘

<h1>Guidelines</h1>

<ul>

 <li>No more than 3 levels of nesting in any function and less than 40 lines of code</li>

 <li>Use minimum amount of code required</li>

 <li>Do not modify any code outside of <strong>c, queue.c</strong> and <strong>downloader.c </strong>(or the test programs which you may modify to improve – but they will not be marked)<strong>, </strong>otherwise your submission will fail to compile (and you will receive zero marks)</li>

 <li>All memory allocated during the programs execution should be free()’ed and all resources, files, sockets should be closed before the program finishes. <strong>Check your program with valgrind – leakcheck=all to be sure!</strong></li>

 <li>Comment code as necessary, excessive commenting is not required but anything not obvious should be documented</li>

 <li>Marks will be awarded for clean code and documentation</li>

</ul>


