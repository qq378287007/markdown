一、LaTeX中英文

(1) mathbb英文
$$
\mathbb{AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz}
$$

(2) mathscr英文
$$
\mathscr{AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz}
$$

(3) mathcal英文
$$
\mathcal{AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz}
$$

(4) mathbf英文
$$
\mathbf{AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz}
$$

二、LaTeX中希腊字母

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


三、LaTeX中空格

(1) 正常输入无空格
$$Embrace the glorious mess that you are.$$

(2) "\!"缩进1/6m宽度
$$Embrace\!the\!glorious\!mess\!that\!you\!are.$$

(3) "\,"间隔1/6m宽度
$$Embrace\,the\,glorious\,mess\,that\,you\,are.$$

(4) "\;"间隔2/7m宽度
$$Embrace\;the\;glorious\;mess\;that\;you\;are.$$

(5) "\ "间隔1/3m宽度
$$Embrace\ the\ glorious\ mess\ that\ you\ are.$$

(6) "\quad "间隔1m宽度
$$Embrace\quad the\quad glorious\quad mess\quad that\quad you\quad are.$$

(7) "\qquad "间隔m宽度
$$Embrace\qquad the\qquad glorious\qquad mess\qquad that\qquad you\quad are.$$

四、LaTeX中取消默认斜体

(1) 英文字母默认为斜体
$$x_{z}\ congratulation$$

(2) "\rm "取消英文中的斜体
$$\rm x_{z}\ \rm congratulation$$

五、LaTeX中字母上标

^a
$\hat{a}$	
	
¨a
$\ddot{a}$

ˉa
$\bar{a}$

→a
$\vec{a}$ 	

ˋa
$\grave{a}$

˘a
$\breve{a}$

-a
$\overline{a}$

^a
$\widehat{a}$

˙a
$\dot{a}$

ˇa
$\check{a}$

~a
$\tilde{a}$

ˊa
$\acute{a}$

~a
$\widetilde{a}$

∼ 	
$\sim$


六、LaTeX特殊的数学符号

×	
$\times$	

÷ 
$\div$


⋂ 1 n 
$\bigcap_{1}^{n}$ 

⋃ 1 n
$\bigcup_{1}^{n}$ 
​

(3 5​)
$​\binom{5}{3}$

∀
$\forall$

∃
$\exists$

∂
$\partial$

∝
$\propto$

{}
$\left\{ \right\}$

⟨⟩
$\left\langle \right\rangle$


sqrt(100)
$\sqrt{100}$

sqrt(100,3)
$\sqrt[3]{100}$

lim n→∞
$​\mathop{\lim}_{n \to \infty}$

3/7
$\frac{3}{7}$

∑ n=0 ∞
$​\sum_{n=0}^{\infty}$


∫ a b
$\int_a^b$

∫
$\int$

∮
$\oint$

∮∮
$\oiint$

∮∮∮
$\oiiint$

​
七、LaTeX中数学公式

(1) 方程
$$y = x ^ 2$$

(2) 欧拉公式
$$e ^ {i \pi} + 1 = 0$$

(3) e^x泰勒展开
$$ e^x = \sum_{n=0}^\infty \frac{1}{n!} x^i$$
$e^x = \sum_{n=0}^\infty \frac{1}{n!} x^i$

(4) 排列组合数公式
$$\frac{n!}{k!(n-k)!} = {n \choose k}$$


八、LaTeX中矩阵
$$
A_{m,n} = 
\begin{pmatrix}
	a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\     
	a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\     
	\vdots  & \vdots  & \vdots & \vdots  \\
	a_{m,1} & a_{m,2} & \cdots & a_{m,n} \\
\end{pmatrix}
$$

九、LaTeX中方程组

(1) 圆的参数方程
$$
\left\{
	\begin{aligned}
		x & = r \cos \theta \\
		y & = r \sin \theta \\
	\end{aligned}
\right.
$$

(2) 均匀分布函数
$$ 
F(x) =
\left\{
	\begin{array}{rcl}
		0, & {x<a} \\
		\frac{x-a}{b-a}, & {a<x<b} \\
		 1, & {x>b} \\
	\end{array} 
\right. 
$$

(3) 麦克斯韦方程组
$$
\begin{cases}{}
	\oint_l{Hdl} = \int_s{j ds} + \int_s{\frac{\partial D}{\partial t} ds} \\ 
	\oint_l{Edl} = - \int_s{\frac{\partial B}{\partial t}} \\
	\oint_s{ds} = 0 \\
	\oint_s{Dds} = \int_v{\rho dv} \\
\end{cases}
$$


十、demo

$$
f(x) = \frac{1}{\sqrt{2\pi} \sigma} e ^ {- \frac{(x - \mu)^2}{2 \sigma^2}}
$$

$$
f(x) = \frac{1}{\sqrt{2\pi}\sigma} exp \left\{ -\frac{(x-\mu)^2}{2\sigma^2} \right\}
$$
