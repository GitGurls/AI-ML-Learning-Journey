
What is Sample Space?
Definition: Sample Space is the set of all possible outcomes of a random experiment.

Simple Hinglish:

Kisi experiment ko perform karne par jitne bhi possible results aa sakte hain, un sabhi results ke collection ko Sample Space kehte hain.

Sample Space ko capital letter S se represent karte hain.

What is an Event?
Definition: An Event is a subset of the sample space that contains one or more outcomes of a random experiment.

Simple Hinglish:

Jab hum Sample Space mein se apni requirement ke according kuch particular outcomes select karte hain, toh use Event kehte hain.
Example: Rolling a Dice
Maan lo ek dice roll kiya.

Sample Space:
\[
S=\{1,2,3,4,5,6\}
\]

Ab question hai: Dice par even number aane ka event kya hoga?

Even numbers:
\[
\boxed{A=\{2,4,6\}}
\]


<img width="1176" height="647" alt="image" src="https://github.com/user-attachments/assets/ce3fd533-9e81-4a9d-bb1a-d3b0c60b9cab" />


<img width="1252" height="615" alt="image" src="https://github.com/user-attachments/assets/63b6a299-9f2a-4751-a2e3-fb707496491b" />

<img width="1307" height="692" alt="image" src="https://github.com/user-attachments/assets/de5019be-d942-4c93-a311-80fe761c8109" />
<img width="972" height="410" alt="image" src="https://github.com/user-attachments/assets/0fc9726a-fa5c-414d-af0a-1bf82c905f01" />


<img width="841" height="602" alt="image" src="https://github.com/user-attachments/assets/c851387e-fa08-48ba-83ec-aafc311f2a9f" />


<img width="857" height="386" alt="image" src="https://github.com/user-attachments/assets/79207269-0067-4ae4-b086-d02b9c81d9c1" />


ye question Probability + Combination + Sample Space ka hai. Isme ek bahut important concept samjhaya gaya hai: kisi group mein se randomly items select karne par kisi particular item ke select hone ki probability kya hogi.

Chalo step-by-step samajhte hain.
1. Understand the Question
Slide mein likha hai:

Chip Defect Detection
- \(n\) chips manufactured, 1 of which is defective.
- \(k\) chips randomly selected from \(n\) for testing.
- What is the probability that the defective chip is in the \(k\) selected chips?
Simple Hinglish:

Ek factory mein total \(n\) chips banayi gayi hain.

Unmein:
- Total chips = \(n\)
- Defective chips = 1
- Good chips = \(n-1\)
- Testing ke liye randomly select karni hain = \(k\) chips.
Humein calculate karna hai ki selected \(k\) chips mein defective chip hone ki probability kitni hai.
2. Example se samjho
Maan lo factory mein 5 chips hain.
Total 5 chips
✓
C1

Good


✓
C2

Good


✕
C3

Defective


✓
C4

Good


✓
C5

Good



C3 is the only defective chip.

Ab testing ke liye 2 chips select karni hain.
n = 5, k = 2

Question: Selected 2 chips mein C3 (defective chip) aane ka chance kitna hai?
3. Method: Combination
Yahan order matter nahi karta.

For example:
- C1, C3
- C3, C1
Dono same selection hain.

Isliye Combination use karenge.
Step 1: Find Sample Space (S)
Total 5 chips mein se 2 select karni hain.
\[
|S|={5\choose2}
\]

\[
=\frac{5!}{2!\times3!}
\]

\[
=\boxed{10}
\]

Matlab total 10 possible selections hain.
Step 2: Find Favourable Outcomes (E)
Humein defective chip C3 select karni hi hai.

Ab remaining 4 good chips mein se 1 aur chip select karni hai.
\[
|E|={4\choose1}
\]

\[
=\boxed{4}
\]

Matlab 4 favourable selections hain.
Step 3: Calculate Probability
Formula:
\[
P(E)=\frac{|E|}{|S|}
\]

Values put karo:
\[
P(E)=\frac{4}{10}
\]

\[
\boxed{P(E)=0.4=40\%}
\]

Matlab defective chip select hone ka chance 40% hai.

4. Ab general formula samjho (Important)
Slide mein \(n\) aur \(k\) use kiya gaya hai. Humein kisi bhi number of chips ke liye formula banana hai.

Step 1: Total possible selections
\[
|S|={n\choose k}
\]

Step 2: Favourable selections

Ek defective chip already select karni hai.

Remaining good chips = \(n-1\)

Ab \(k-1\) chips select karni hain.
\[
|E|={n-1\choose k-1}
\]

Step 3: Probability
\[
P(E)=\frac{|E|}{|S|}
\]

\[
P(E)=\frac{{n-1\choose k-1}}{{n\choose k}}
\]

Combination formula simplify karne par:
\[
=\frac{(n-1)!}{(k-1)!(n-k)!}
\times
\frac{k!(n-k)!}{n!}
\]

Common terms cancel kar do:
\[
=\frac{k}{n}
\]

Final Formula – Remember This
\[
\boxed{P(\text{Defective chip selected})=\frac{k}{n}}
\]

Where:
- \(n\) = Total number of chips
- \(k\) = Number of selected chips

5. Ek aur example
Suppose:
- Total chips = 20
- Defective chips = 1
- Selected chips = 5
Find probability that defective chip is selected.
\[
n=20,\quad k=5
\]

Direct formula:
\[
P(E)=\frac{k}{n}
\]

\[
=\frac5{20}
\]

\[
\boxed{P(E)=\frac14=25\%}
\]

6. Important: Agar defective chip select NA ho toh?
Kabhi question ulta bhi pooch sakta hai:

What is the probability that the defective chip is NOT selected?

Complement rule use karenge:
\[
P(E')=1-P(E)
\]

\[
=1-\frac{k}{n}
\]

\[
\boxed{P(E')=\frac{n-k}{n}}
\]



<img width="1026" height="486" alt="image" src="https://github.com/user-attachments/assets/d9dfe0e4-5517-4734-b330-62d74ebdde0a" />
