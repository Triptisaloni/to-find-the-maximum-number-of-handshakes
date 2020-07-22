# to-find-the-maximum-number-of-handshakes
Program to find the maximum number of handshakes is discussed here. Given a positive integer n, find out the total number of handshakes possible.



DESCRIPTION



It was Raj's first day at school. His teacher Anu asked the students to meet every other student in the class and to introduce about themselves. The teacher asked them to do handshakes when they meet each other.

If there are n number of students in the class then find the total number of handshakes made by the students.



Input format and output format:



Input consists of 1 integer.
First input corresponds to the total number of students.
Output consists of 1 integer.


Sample Input:

15



Sample output:

105



Algorithm to find the maximum number of handshakes


Input the number of people (n).
Find nC2, calculated as n * (n-1) / 2.
Print the calculated result.


Program to find the maximum number of handshakes is given below

#include
int main()
{
//fill the code
	int num;
	scanf(“%d”,&num);
	int total = num * (num-1) / 2; // Combination nC2
	printf(“%d”,total);
	return 0;
}

Output
15
105
