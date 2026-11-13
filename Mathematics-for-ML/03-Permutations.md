sort n distinct objets aur same obhejcts dono ko smjhaoo
Soni, ye Permutation ka bahut important topic hai. Isme bas ek difference samajhna hai: Objects alag-alag hain ya kuch objects same (identical) hain.

Dono ko examples aur formulas ke saath samajhte hain.

1. Permutation of n Distinct Objects
Meaning: Jab hamare paas n different objects hote hain aur unhe arrange karna hota hai, toh use permutation of n distinct objects kehte hain.

Distinct ka matlab = Sabhi objects alag-alag hain.

Example 1: 3 different letters
Maan lo hamare paas 3 letters hain:

A
B
C
Inko kitne different ways mein arrange kar sakte hain?
Possible arrangements:

ABC

ACB

BAC

BCA

CAB

CBA

Total = 6 arrangements.

Formula:

n
!
=
n
(
n
−
1
)
(
n
−
2
)
⋯
1
n!=n(n−1)(n−2)⋯1
Yahan n = 3.

3
!
=
3
×
2
×
1
3!=3×2×1
6
6
​
 
Example 2: 4 distinct objects
Objects: A, B, C, D

4
!
=
4
×
3
×
2
×
1
4!=4×3×2×1
24
24
​
 
Important formula
n distinct objects
=
n
!
n distinct objects=n!
​
 
Jab saare n objects ko arrange karna ho.

2. Permutation of n Objects When Some Objects Are Identical
Ab second case samjho.

Meaning: Jab kuch objects same (identical) hote hain, toh unhe arrange karne ke unique ways calculate karte hain.

Identical ka matlab = Objects dekhne mein ya value mein same hain.

Example 1: AAB
Maan lo tumhare paas 3 letters hain:

A
A
B
Yahan 3 letters hain, lekin A do baar repeat ho raha hai.
Agar hum simple factorial lagayein:

3
!
=
6
3!=6
Lekin ye 6 unique arrangements nahi hain, kyunki dono A identical hain.

Actual unique arrangements:

AAB

ABA

BAA

Total = 3.

Formula kaise aaya?
Pehle total arrangements:

3
!
=
6
3!=6
A ke 2 identical letters ko aapas mein swap karne par koi naya arrangement nahi banta.

Isliye 2! se divide karenge:

3
!
2
!
2!
3!
​
 
=
6
2
= 
2
6
​
 
3
3
​
 
General Formula
Agar n objects hain aur kuch identical objects repeat ho rahe hain:

n
!
n
1
!
n
2
!
n
3
!
⋯
n 
1
​
 !n 
2
​
 !n 
3
​
 !⋯
n!
​
 
​
 
Where:

n = Total objects

n₁ = First identical group ki quantity

n₂ = Second identical group ki quantity

n₃ = Third identical group ki quantity

3. Ek aur example: BANANA
Word = BANANA

Total letters = 6

Letter

Frequency

B

1

A

3

N

2

Yahan:

A three times repeat ho raha hai.

N two times repeat ho raha hai.

B ek hi baar hai.

Formula:

6
!
3
!
×
2
!
×
1
!
3!×2!×1!
6!
​
 
=
720
6
×
2
= 
6×2
720
​
 
=
720
12
= 
12
720
​
 
60
60
​
 
Matlab BANANA ke 60 unique arrangements possible hain.

4. Dono mein difference
Case 1: Distinct Objects

A
B
C
3
!
=
6
3!=6
Case 2: Identical Objects

A
A
B
3
!
2
!
=
3
2!
3!
​
 =3
Distinct Objects

Identical Objects

Sab objects different

Kuch objects same

No repetition adjustment

Repeated groups se divide

n
!
n!

n
!
n
1
!
n
2
!
⋯
n 
1
​
 !n 
2
​
 !⋯
n!
​
 

ABC = 6 ways

AAB = 3 ways

5. Practice Questions
Ab tum khud try karo.

Permutation mini test

0/4 attempted
Q1. A, B, C, D ko arrange karne ke kitne ways hain?


12

24

6
Q2. AABC ke unique arrangements kitne hain?


12

24

6
Q3. MISS word ke unique arrangements kitne hain?


12

24

6
Q4. LEVEL word ke unique arrangements kitne hain?


30

60

120


How many unique 6-digit passcodes are possible if a passcode uses each of five distinct numbers?

Simple Hinglish: Agar 6-digit ka password banana hai aur usmein 5 different digits use hone hain, toh kitne unique passwords ban sakte hain?
Step 1. Given information
- Total positions = 6
- Distinct digits = 5
- Har digit kam se kam ek baar use hoga.
- Ek digit repeat hoga.
Maan lo digits hain: 1, 2, 3, 4, 5

Inmein se ek digit do baar aayega.
Step 2. Repeated digit choose karo
5 digits mein se koi ek digit repeat ho sakta hai.

Total choices = 5
Step 3. Arrangements calculate karo
Ab 6 digits arrange karne hain, jismein ek digit 2 baar repeat hai.
\[
\frac{6!}{2!}
\]

\[
=\frac{720}{2}=360
\]

Step 4. Total passcodes
\[
5\times360
\]

\[
\boxed{1800}
\]


<img width="1132" height="645" alt="image" src="https://github.com/user-attachments/assets/0d4dd9ad-f36f-48d9-b685-4515d4c5a5c7" />

