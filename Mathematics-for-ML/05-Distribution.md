
1. What does Put Objects in r Buckets mean?
Maan lo tumhare paas 3 balls hain aur 2 buckets hain.
3 objects and 2 buckets
Bucket A

Bucket B


Objects ko in buckets mein distribute karna hai.

Yahan:
- n = Total objects
- r = Total buckets
2. Case 1: Distinct Objects
Meaning: Jab saare objects different hote hain aur har object kisi bhi bucket mein ja sakta hai.

Example:

3 different balls hain:
- A
- B
- C
2 buckets hain:
- Bucket 1
- Bucket 2
Har ball ke paas 2 choices hain.
Step-by-step choices
Ball A
2 choices


Ball B
2 choices


Ball C
2 choices



\[
2\times2\times2=8
\]


Product Rule use karenge, kyunki har ball independently bucket choose kar sakti hai.

General formula:
\[
\boxed{r^n}
\]

Where:
- r = Number of buckets
- n = Number of distinct objects
Example
5 distinct balls ko 3 buckets mein distribute karna hai.
\[
r=3,\quad n=5
\]

\[
3^5=3\times3\times3\times3\times3
\]

\[
\boxed{243}
\]

Total ways = 243.
Distinct Objects = rⁿ
Important assumption: Buckets alag-alag identifiable hain aur empty buckets allowed hain.

3. Case 2: Indistinct Objects
Ab second case samjho.

Meaning: Jab saare objects identical hote hain, yani unmein koi difference nahi hota.

Example:

3 identical balls hain:

● ● ●

Aur 2 different buckets hain:
- Bucket A
- Bucket B
Ab balls ko distribute karna hai.

Possible distributions:
All possible distributions
1.
Bucket A


Bucket B
Empty



2.
Bucket A


Bucket B



3.
Bucket A


Bucket B



4.
Bucket A
Empty


Bucket B




Total = 4 ways.

Dhyan do: Balls identical hain, isliye Bucket A mein pehli ball ya doosri ball bhejne ka koi difference nahi hai.
Formula: Indistinct Objects
Jab n identical objects ko r distinct buckets mein distribute karna ho aur empty buckets allowed hon:
\[
\boxed{{n+r-1\choose r-1}}
\]

Isko Stars and Bars method bhi kehte hain.
Example
3 identical balls ko 2 buckets mein distribute karna hai.
\[
n=3,\quad r=2
\]

Formula:
\[
{3+2-1\choose 2-1}
\]

\[
={4\choose1}
\]

\[
=\frac{4!}{1!\times3!}
\]

\[
\boxed{4}
\]

Answer = 4 ways.
Indistinct Objects = C(n+r−1, r−1)
