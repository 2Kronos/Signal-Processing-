# Question 1
![image](https://github.com/user-attachments/assets/f7438664-e168-43d9-bebe-cb9106af5342)

**Answer = 20.589 $\pm$ 0.002 
Marks: 14

Transfer function 

$$H(s)=\frac{Y(s)}{X(s)}$$

$$H(s)=\frac{V_{out}(s)}{V_{in}(s)}$$
$$H(S)= \frac{4}{s+0.25}$$
$$V_{in}(t) = te^{-0.2t}$$
$$L(V_{in}) = L(te^{-0.2t})$$
$$V_{in}(s)= \frac{1}{(s+0.2)^2}$$
$$V_{out}(s) = V_{in}(s) \times H(s)$$$$V_{out}(s)= \frac{1}{(s+0.2)^{2}} \times \frac{4}{(s+0.25)}  $$ $$V_{out}(s)= \frac{4}{(s+0.2)^{2}(s+0.25)}$$
$$V_{out}(s) =\frac{A}{(s+0.2)} + \frac{B}{(s+0.2)^{2}} + \frac{C}{(s+0.25)}$$
$$4 = A(s+0.2)(s+0.25)+B(s+0.25) +C(s+0.2)^{2}$$
Let s = -0.2

$$4= B(-0.2+0.25)$$
$$80=B$$
Let s=-0.25
$$4= C(-0.25+0.2)^{2}$$
$$\frac{4}{(\frac{1}{400})} = C$$
$$1600 =C$$
Let s =0
$$4=A(0+0.2)(0+0.25)+B(0+0.25)+C(0+0.2)^{2}$$
$$4= A(0.05)+B(0.25)+C(0.2)^{2}$$
$$4= A(0.05)+80(0.25)+1600(0.2)^{2}$$
$$4 = A(0.05)+84$$
$$4-84=A(0.05)$$
$$\frac{-80}{0.05}=A$$
$$-1600=A$$
$$V_{out}(s) =-\frac{1600}{(s+0.2)} + \frac{80}{(s+0.2)^{2}} + \frac{1600}{(s+0.25)}$$
$$V_{out}(s) =-1600\frac{1}{(s+0.2)} + 80\frac{1}{(s+0.2)^{2}} + 1600\frac{1}{(s+0.25)}$$
$$V_{out}(s) =-1600e^{-0.2t} + 80te^{-0.2t} + 1600e^{-0.25t}$$
$$V_{out}(s) =-1600e^{-0.2(6.43)} + 80(6.43)e^{-0.2(6.43)} + 1600e^{-0.25(6.43)}$$
$$V_{out}=20.589$$
# Question 2
![[Screenshot 2024-10-18 230330.png]]
**Marks:10**
**Answer:-0.784$\pm$ 0.002**




# Question 3

![[Screenshot 2024-10-18 230817.png]]
**Marks:14**
**Answer:14.798$\pm$ 0.002




# Question 4

![[Screenshot 2024-10-18 231140.png]]
**Marks:10**
**Answer:42.693$\pm$ 0.002

# Question 5
![[Screenshot 2024-10-18 231216.png]]
**Marks:12**
**Answer:1.321$\pm$ 0.002