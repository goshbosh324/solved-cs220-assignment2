Download Link: https://assignmentchef.com/product/solved-cs220-assignment2
<br>
In this your second project you write a function int sort(int A[], int n)

that takes one array of length n and sorts it. However, n is of the order of ten millions, so you need to use radixsort to get the sorting done fast. Fast here means in the range of seconds.

The numbers are all less than 2<sup>32</sup>; you need to do two rounds of radixsort for the lower and upper 16 bit of the number. For an integer b you can find the lower 16 bit by b &amp; 0xFFFF and the upper 16 bit by (b&gt;&gt;16) &amp; 0xFFFF. Read up about bit operations and hexadecimal number in C and C++.