1. What is Combination?
Definition: Combination is a method of selecting objects from a group where the order of selection does not matter.

Simple Hinglish:

Combination ka matlab hai kisi group mein se kuch objects select karna, jahan unka order important nahi hota.
Example: Students ki team banana
Maan lo tumhare paas 3 students hain:
A

B

C


Question: Inmein se 2 students ki team kitne ways mein bana sakte hain?

Possible teams:
1. AB
2. AC
3. BC
Total = 3 teams.

Dhyan do:
- AB aur BA same team hai.
- AC aur CA same team hai.
- BC aur CB same team hai.
Isliye order matter nahi karta.
2. Combination Formula
Combination ka formula hai:
\[
\boxed{{}^nC_r=\frac{n!}{r!(n-r)!}}
\]

Ismein:
- n = Total available objects
- r = Kitne objects select karne hain
- ! = Factorial
Example: 5 students mein se 2 select karne hain.
Given:
\[
n=5,\quad r=2
\]

Formula mein values put karo:
\[
{}^5C_2=\frac{5!}{2!(5-2)!}
\]

Step 1:
\[
=\frac{5!}{2!\times3!}
\]

Step 2:
\[
=\frac{120}{2\times6}
\]

Step 3:
\[
=\frac{120}{12}
\]

\[
\boxed{10}
\]

Answer = 10 different teams.
3. Permutation vs Combination
Ye dono concepts ek jaise lagte hain, lekin difference bahut important hai.
Permutation – Arrangement










Maan lo 3 students ko first, second aur third rank deni hai.

ABC aur BAC different arrangements hain.

Order matters.

Combination – Selection










Maan lo 3 students mein se 2 ki team banani hai.

AB aur BA same team hai.

Order does not matter.

Permutation	Combination
Arrangement	Selection
Order matters	Order doesn't matter
\({}^nP_r\)	\({}^nC_r\)
\(\frac{n!}{(n-r)!}\)	\(\frac{n!}{r!(n-r)!}\)

4. Combination ko real-life examples se samjho
Example 1: Cricket Team

11 players mein se 5 players select karne hain.
\[
{}^{11}C_5
\]

Example 2: Pizza Toppings

10 toppings mein se 3 toppings select karni hain.
\[
{}^{10}C_3
\]

Example 3: College Committee

8 students mein se 3 students select karne hain.
\[
{}^8C_3
\]

Teeno cases mein selection ho raha hai, arrangement nahi. Isliye Combination use hoga.
5. Combination ki important properties
Ye formulas bhi yaad rakhna:

Property 1:
\[
{}^nC_0=1
\]

Kisi group mein se zero objects select karne ka ek hi way hai.

Property 2:
\[
{}^nC_1=n
\]

5 objects mein se 1 select karne ke 5 ways hain.

Property 3:
\[
{}^nC_r={}^nC_{n-r}
\]

Example:
\[
{}^5C_2={}^5C_3=10
\]

5 students mein se 2 select karna aur 3 students select karna, dono ke ways equal hain.

6. Ab khud solve karo
Combination Mini Test
0/4

Q1. 6 students mein se 2 students ki team banani hai. Kaunsa concept use hoga?

Permutation

Combination




Q2. 5 objects mein se 3 select karne hain. Formula kya hoga?

5! / (5-3)!

5! / (3! × 2!)

5!




Q3. AB aur BA combination mein same hain ya different?

Same

Different




Q4. 5 students mein se 2 select karne ke kitne ways hain?

20

10

5



Submit Answers
7. AI/ML mein Combination ka use
Combination ka use feature selection aur possible subsets samajhne mein hota hai.

Example: Tumhare dataset mein 10 features hain aur tum unmein se 3 features select karna chahti ho.
\[
{}^{10}C_3=\frac{10!}{3!7!}=120
\]

Matlab 120 possible feature groups hain.

Ye Machine Learning mein feature selection aur search problems ko samajhne mein useful hai.

<img width="877" height="372" alt="image" src="https://github.com/user-attachments/assets/f84048d2-7bba-4658-b4dd-bd7e0dc10693" />

<img width="972" height="617" alt="image" src="https://github.com/user-attachments/assets/2e865cbf-f207-41d9-9f89-b45a373584e6" />


