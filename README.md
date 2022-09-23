# Simplyfi assignment
Question 1
Write a python code for converting integer values to Indian currency notations, without 
using the currency libraries
Example:
input: 504678
output: 5,04,67


![Screenshot (5)](https://user-images.githubusercontent.com/114252395/192049502-73a8e694-0ead-4dd1-bc96-074ebba43860.png)


Question 2 :


You won’t get caught if you hide behind someone.”
Sang-Woo advises Gi-Hun to hide behind someone to avoid getting shot.
Gi-Hun follows Sang-Woo's advice and hides behind Ali, who saved his life earlier. Gi-Hun and Ali 
both have the same height, K

. Many players saw this trick and also started hiding behind Ali. 
Now, there are N
players standing between Gi-Hun and Ali in a straight line, with the ith player having height Hi

. Gi-Hun wants to know the minimum number of players who need to get shot so that Ali is visible 
in his line of sight.

Note:
• Line of sight is a straight line drawn between the topmost point of two objects. Ali is visible 
to Gi-Hun if nobody between them crosses this line. 

• Even if there are some players who have the same height as that of Gi-Hun and Ali, Ali will 
be visible in Gi-Hun's line of sight. 

• Gi-Hun and Ali have the same height. 

Input Format

• The first line of input contains a single integer T
, denoting the number of test cases. The description of T

• test cases follows. 

• The first line of each test case contains two space-separated integers N and K

• , denoting the total number of players between Gi-Hun and Ali and the height of both of 
them respectively. 

• The second line of each test case contains N

• space-separated integers, denoting the heights of the players between Gi-Hun and Ali. 
Output Format
For each test case, output in a single line the minimum number of players who need to get shot so 
that Ali is visible in Gi-Hun's line of sight.
Constraints

• 1≤T≤105

• 1≤N≤105

• 1≤K≤106

• 1≤Hi≤106 for every 1≤i≤N

• .

• The sum of N across all test cases does not exceed 5⋅105

• . 
Sample Input 1 

3

4 10

2 13 4 16

5 8

9 3 8 8 4

4 6

1 2 3 4

Sample Output 1 

2

1

0

![Screenshot (6)](https://user-images.githubusercontent.com/114252395/192049949-02ff3da8-0fcd-41f1-9706-8ba0a05f1014.png)


Explanation

Test Case 1: Gi-Hun and Ali have height 10
. For Ali to be visible to Gi-Hun, the second person (with height 13) and the fourth person (with 
height 16) need to get shot. Hence, the minimum number of players who need to get shot is 2
.


Test Case 2: Gi-Hun and Ali have height 8
.

For Ali to be visible to Gi-Hun, the first person (with height 9) needs to get shot. Hence, the 
minimum number of players who need to get shot is 1
.


Test Case 3: Nobody needs to get shot because everyone is shorter than Gi-Hun and Ali
