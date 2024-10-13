# Question 1

![[Pasted image 20241012123030.png]]
$$
\begin{align}

|f(jw)|\ =\sqrt{(Re[F(jw)])^2+(Im[F(jw)]^2}\\ \\
f(t) =te^{-at} \leftrightarrow F(jw) =(\frac{1}{a+jw})^2      \\\\
w =2\pi f \\\\
w= 2(\pi)(1.69) =10.6185 \\\\

f(t) = 100te^{-043t}.\\ \\
F(jw)= 100(\frac{1}{0.43+jw})^2\\\\
F(jw)= 100(\frac{1}{0.43+10.6185j})^2\\\\
let\ z = 0.43 +10.6185j \\\\\
|z| = \sqrt{(0.43)^2+(10.6185)^2}\\\\
|z| = 10.6272\\\\
|F(jw)|= 100(\frac{1}{10.6272})^2\\\\
|F(jw)|=0.885 \\\\

\end{align}
$$
# Question 2 

![[Pasted image 20241012121147.png]]

$$
\begin{align}
B_{wf} = \frac{1}{T}= \frac{1}{16.3us}=61.3KHZ
\end{align}
$$


# Question 5
![image](https://github.com/user-attachments/assets/d3306052-1ae8-4e24-b67f-e740b4d6fe45)

$$
\begin{align}
a\ =\ 0.75\\ \\

na^n\ = \frac{az}{(z-a)^2}\\ \\

y[n]\ = x[n]\ + ay[n-1] \\ \\

Y(z)\ = \frac{0.8z}{(z-0.8)^2}\ +0.75 \frac{Y(z)}{z}    \\ \\

Y(z)\ - 0.75 \frac{Y(z)}{z} = \frac{0.8z}{(z-0.8)^2} \\ \\

Y(z)(1\ - \frac{0.75}{z}) \ =  \frac{0.8z}{(z-0.8)^2} \\ \\

  \frac{1}{z}Y(z)(1\ - \frac{0.75}{z}) \ =  \frac{0.8z}{(z-0.8)^2} \times \frac{1}{z}\\ \\

\frac{1}{z}Y(z)(\frac{z- 0.75}{z})\ =\ \frac{0.8}{(z-o.8)^2} \\ \\

\frac{1}{z}Y(z)\  =\ \frac{0.8}{(z-0.8)^2} \times \frac{z}{z-0.75} \\ \\

\frac{1}{z}Y(z)\ = \frac{0.8z}{(z-0.8)^2(z-0.75)} \\ \\
fractional\ decomposition \\ \\ 

\frac{0.8z}{(z-0.8)^2(z-0.75)}\ = \frac{A}{z-0.8}\ + \frac{B}{(z-0.8)^2} + \frac{C}
{z-0.75}\\ \\

pole\ method \\ \\

0.8z\ =\ A(z-0.8)(z-0.75)\ +\ B(z-0.75)\ +\ C(z-0.8)^2 \\ \\ 

let\ z\ =\ 0.8 \\\\

0.8(0.8)\ =\ B(0.8-0.75) \\ \\ 

\frac{0.64}{0.05}\ =\ B \\\\

12.8\ =\ B \\\\

let\ z\ =\ 0.75 \\\\

0.8(0.75)\ =\ C(0.75-0.8)^2\\\\
0.6\ =\ C(\frac{1}{400}) \\ \\

0.6 \times \frac{400}{1} =\ C\\\\

240\ =\ C \\\\

solve\ for\ A\ let\ z\ =\ 1 \\ \\

0.8z\ =\ A(z-0.8)(z-0.75)\ +\ B(z-0.75)\ +\ C(z-0.8)^2 \\\\

0.8\ =\ A(0.2)(0.25)\ +\ B(0.25)\ +\ C(0.2)^2 \\\\

0.8\ =\ A(0.05)\ +\ 12.8(0.25)\ +\ 240(0.2)^2 \\\\

0.8\ = A(0.05)\ +\ 12.8 \\\\

0.8\ -\ 12.8\ =\ A(0.05)\\\\
-\frac{12}{0.05}\ =\ A\\\\

-240\ =\ A \\\\

\frac{1}{z}Y(z)\ = \frac{A}{z-0.8}\ + \frac{B}{(z-0.8)^2} + \frac{C}
{z-0.75}\\ \\

\frac{1}{z}Y(z)= -\frac{240}{z-0.8}\ + \frac{12.8}{(z-0.8)^2} + \frac{240}{z-0.75}\\ \\

Y(z)\ =\ -\frac{240z}{z-0.8}\ + \frac{12.8z}{(z-0.8)^2} + \frac{240z}{z-0.75}\\ \\

Y(z)\ =\ -\frac{240z}{z-0.8}\ +16 \frac{0.8z}{(z-0.8)^2} + \frac{240z}{z-0.75}\\ \\

y(n)\ =\ - (240)(0.8)^n\ +\ 16 n(0.8)^n + (240)(0.75)^n \\\\

y(n)\ =\ - (240)(0.8)^{11}\ +\ 16 (11)(0.8)^{11} + (240)(0.75)^{11}\\\\

y(n)\ =\ 4.6388\\\\



\end {align}
$$


# Question 6

![[Pasted image 20241012210452.png]]
$$
\begin{align}

w=2\pi f\\\\
w=2\pi (6.7k)\\\\
w=13400\pi\\\\
X_c = \frac{1}{wc}\\\\
X_c = \frac{1}{13400\pi (7uf)}\\\\
X_c = 3.3934\\\\
V_C =V_{in} \times \frac{X_c}{\sqrt{R^2+X_C^2}}\\\\
V_C =37 \times \frac{3.3934}{\sqrt{3^2+(3.3934)^2}}\\\\
V_C =27.720\\\\
\end{align}
$$
# Question 7

![[Pasted image 20241012222832.png]]$$
\begin{align}
V_{in} =tu(t)\\\\
V_{R} =IR\\\\
V_{C} =\frac{1}{c}\int^{t}_{0}i(t) \\\\
V_{in}= IR+\frac{1}{c}\int^{t}_{0}i(t)\\\\
L(tu(t))=L(i(t))+L(\frac{1}{c}\int^{t}_{0}i(t))\\\\
\frac{1}{s^2}=I(s)R+\frac{1}{c}\times \frac{I(s)}{s}\\\\
pull\ out I(s)\\\\
\frac{1}{s^2}=I(s)(R+ \frac{1}{cs})\\\\
I(s) = \frac{1}{s^2}\times \frac{cs}{csR+1}\\\\
I(s) =  \frac{c}{s^2(cR+1)}\\\\
V_{out}=\frac{1}{c}I(s)\\\\
V_{out}=\frac{1}{c}\times \frac{c}{s^2(cR+1)}\\\\
V_{out}=\frac{1}{s^2(cR+1)}\\\\
\end{align}
$$