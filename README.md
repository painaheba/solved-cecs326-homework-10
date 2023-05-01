Download Link: https://assignmentchef.com/product/solved-cecs326-homework-10
<br>
Chapter 8

Purpose: A PROGRAMMING assignment to gain experience with signals and semaphors.

You will build an intersection control system.

Create and initialize a semaphore before you fork. Print the semaphor ID.

After the fork, the child handles traffic in the N/S direction; the parent handles traffic in the E/W direction. Both try to get their cars into the intersection as soon as possible.

Handling of the intersection must proceed as follows:

<ul>

 <li>get a lock on the intersection</li>

 <li>print ”N/S car entering intersection” (or E/W car if you’re the parent).</li>

 <li>Sleep 1 seconds, this time represents how long it takes to cross the intersection.</li>

 <li>print ”N/S car leaving intersection”</li>

 <li>release the lock on the intersection</li>

</ul>

Both the parent and the child should loop until they have gotten 10 cars across the intersection (i.e., loop 10 times).

Demo: Your traffic control program. The instructor will also want to look at the code.


