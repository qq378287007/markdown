一、LaTeX中不同形式的英文

(1)mathbb形式的英文：
$
\mathbb{AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz}
$

(2)mathscr形式的英文：
$
\mathscr{AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz}
$

(3)mathcal形式的英文：
$
\mathcal{AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz}
$

(4)mathbf形式的英文：
$
\mathbf{AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz}
$

二、LaTeX中常见希腊字母

α A	
$\alpha A$	   

β B	
$\beta B$	 

γ Γ	
$\gamma \Gamma$	  

δ Δ	
$\delta \Delta$	    

ϵ ε E	
$\epsilon \varepsilon E$	

ζ Z	
$\zeta Z$	        

η H	
$\eta H$	   

θ ϑ Θ	
$\theta \vartheta \Theta$	

ι I	
$\iota I$	        

κ K	
$\kappa K$	     

λ Λ	
$\lambda \Lambda$	      

μ N	
$\mu N$

ξ Ξ	
$\xi \Xi$

o O	
$o O$

π Π	
$\pi \Pi$

ρ ϱ P	
$\rho \varrho P$

σ Σ	
$\sigma \Sigma$

τ T	
$\tau T$

υ Υ	
$\upsilon \Upsilon$

ϕ φ Φ	
$\phi \varphi \Phi$

χ X	
$\chi X$

ψ Ψ	
$\psi \Psi$


三、LaTeX中空格如何显示
(1) # 正常的输入，是没有空格的。
$Embrace the glorious mess that you are.$

(2) # 在两个单词之间使用"\!"，使输入的单词之间内容紧贴，缩进1/6m宽度。
$Embrace\!the\!glorious\!mess\!that\!you\!are.$

(3) # 单词之间使用"\,"，使输出的单词之间有了较小的空格，间隔1/6m宽度。
$Embrace\,the\,glorious\,mess\,that\,you\,are.$

(4) # 单词之间使用"\;"，使输出的单词之间有了中等的空格，间隔2/7m宽度。
$Embrace\;the\;glorious\;mess\;that\;you\;are.$

(5) # 单词之间使用"\ "，使输出的单词之间有了大空格，间隔1/3m宽度。
$Embrace\ the\ glorious\ mess\ that\ you\ are.$

(6) # 单词之间使用"\quad "，使输出的单词之间有了大空格，间隔1m宽度。
$Embrace\quad the\quad glorious\quad mess\quad that\quad you\quad are.$

(7) # 单词之间使用"\qquad "，使输出的单词之间有了大空格，间隔m宽度。
$Embrace\qquad the\qquad glorious\qquad mess\qquad that\qquad you\quad are.$

四、LaTeX中取消默认斜体
(1) # 在LaTeX中输入的英文字母默认为斜体，例如：
	$x_{z}$ 
	$congratulation$

(2)# 使用"\rm "来取消英文中的斜体。
	$\rm x_{z}$
	$\rm congratulation$

五、LaTeX中字母上标

^
 	\hat{a}	a ^ \widehat{a} 
a
 	\widehat{a}
a ¨ \ddot{a} 
a
¨
 	\ddot{a}	a ˙ \dot{a} 
a
˙
 	\dot{a}
a ˉ \bar{a} 
a
ˉ
 	\bar{a}	a ˇ \check{a} 
a
ˇ
 	\check{a}
a ⃗ \vec{a} 
a
 	\vec{a}	a ~ \tilde{a} 
a
~
 	\tilde{a}
a ˋ \grave{a} 
a
ˋ
 	\grave{a}	a ˊ \acute{a} 
a
ˊ
 	\acute{a}
a ˘ \breve{a} 
a
˘
 	\breve{a}	a ~ \widetilde{a} 
a
 	\widetilde{a}
a ‾ \overline{a} 
a
 	\overline{a}	∼ \sim∼	\sim
    

六、LaTeX特殊的数学符号

×	\times	÷ \div÷	\div
⋂ 1 6 \bigcap_1^6⋂ 
1
6
​
 	\bigcap_1^6	⋂ 1 n \bigcap_{1}^{n}⋂ 
1
n
​
 	\bigcap_{1}^{n}
⋃ 1 n \bigcup_1^n⋃ 
1
n
​
 	\bigcup_1^n	⋃ 1 n \bigcup_{1}^{n}⋃ 
1
n
​
 	\bigcup_{1}^{n}
( 5 3 ) \binom53( 
3
5
​
 )	\binom53	( 5 3 ) \binom{5}{3}( 
3
5
​
 )	\binom{5}{3}
∀ \forall∀	\forall	∃ \exists∃	\exists
∂ \partial∂	\partial	∝ \propto∝	\propto
{ } \left\{ \right\}{}	\left\{  \right\}	⟨ ⟩ \left \langle \right \rangle⟨⟩	\left \langle    \right \rangle
100 \sqrt{100} 
100
​
 	\sqrt{100}	1000 3 \sqrt[3]{1000} 
3
  
1000
​
 	\sqrt[3]{1000}
lim ⁡ n → ∞ f ( x ) \mathop{\lim}_{n \to \infty }f(x)lim 
n→∞
​
 f(x)	\mathop{\lim}_{n \to \infty }f(x)	3 7 \frac{3}{7} 
7
3
​
 	\frac{3}{7}
∑ n = 0 ∞ \sum_{n=0}^{\infty}∑ 
n=0
∞
​
 	\sum_{n=0}^{\infty}	∫ a b f ( x ) d x \int_a^bf(x)dx∫ 
a
b
​
 f(x)dx	\int_a^bf(x)dx
∫ \int∫	\int	∮ \oint∮	\oint
∯ \oiint 
∬
​
 	\oint	∰ \oiiint 
∭
​
 	\oiiint
    



七、LaTeX中简单数学公式
(1) # 方程
$y=x^2$

(2) # 恒等的欧拉公式
$e^{i\pi} + 1 = 0$

(3) # e^x的泰勒展开式
$e^x=\sum_{n=0}^\infty \frac{1}{n!}x^i$

(4) # 排列组合数公式,其中两对"$",表示公式独占一行。
独占一行，e^x的泰勒展开式  $$e^x=\sum_{n=0}^\infty \frac{1}{n!}x^i$$

(5) # 排列组合数公式,其中两对"$",表示公式独占一行。
独占一行  $$\frac{n!}{k!(n-k)!} = {n \choose k}$$



八、LaTeX中矩阵的显示
# 矩阵的输入，其中"\cdots"为省略号，"\\"为为换行，"&"为对其符号，使矩阵更整齐。
$A_{m,n} = 
\begin{pmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\     
a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\     
\vdots & \vdots & \vdots & \vdots    \\
a_{m,1} & a_{m,2} & \cdots & a_{m,n} 
\end{pmatrix}$



九、LaTeX中方程组的显示

(1) # 圆的参数方程
$$ \left\{
         \begin{aligned}
         x & =  r\cos \theta \\
         y & = r\sin \theta \\
         \end{aligned}
\right.$$

(2) # 均匀分布函数
$$ F(x)=
\left\{
       \begin{array}{rcl}
		0,       & {x<a}\\
		\frac{x-a}{b-a},     & {a<x<b}\\
	    1,    & {x>b}\\
       \end{array} 
\right. $$

(3) 麦克斯韦方程组
$$
\begin{cases}{}
\oint_l{Hdl}=\int_s{jds}+\int_s{\frac{\partial D}{\partial t}ds} \\ 
\oint_l{Edl}=-\int_s{\frac{\partial B}{\partial t}}\\
\oint_s{ds}=0\\
\oint_s{Dds}=\int_v{\rho dv}
\end{cases}
$$


十、练习

$$
f(x) = \frac{1}{\sqrt{2\pi} \sigma} e ^ {- \frac{(x - \mu)^2}{2 \sigma^2}}
$$

#加粗：$$f(x)=\frac{1}{\sqrt{2\pi}\sigma}exp\left\{-\frac{(x-\mu)^2}{2\sigma^2}\right\}$$



https://blog.csdn.net/Sakura_Logic/article/details/103980420