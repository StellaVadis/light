模型的限制条件：

$$
\begin{align}
& x_3 - x_2 = \Delta x \\
& y_3 - y_2 = \Delta y \\
& \sqrt{(x_1-x_0)^2 + (y_1 - y_0)^2} = D \\
& \frac{x_2}{x_0} = \frac{y_2}{y_0} = \frac{x_3}{x_1} = \frac{y_3}{y_1} = \frac{h}{H}
\end{align}
$$

- 我们想要证明入射角不能被确定，即$\theta_1 = \arctan \left(\frac{\sqrt{x_2^2 + y_2^2}}{h}\right)$有无穷多个可能的值。

我们可以尝试对模型的限制条件进行变换，可以得到模型的一组解：
$$
\begin{align}
& x_0 = \frac{H}{h}x_2 \\
& y_0 = \frac{H}{h}y_2 \\
& x_1 = \frac{H}{h}(\Delta x + x_2) \\
& y_1 = \frac{H}{h}(\Delta y + y_2) \\
& x_3 = \Delta x + x_2 \\
& y_3 = \Delta y + y_2 \\
& x_2, y_2  \text{  are free variables.}
\end{align}
$$

可以看到，$x_2,y_2$可以是任意的值，根据$\theta_1 = \arctan \left(\frac{\sqrt{x_2^2 + y_2^2}}{h}\right)$，我们可以知道这个入射角不能被唯一的确定。

另外注意就是$\sqrt{(x_1-x_0)^2 + (y_1 - y_0)^2} = D$,将公式(5)-(8)代入可以得到： $(\frac{H}{h})^2((\Delta x)^2 + (\Delta y)^2) = D^2$, 这些条件都是已知条件，因此给出来D并没有什么用，只能用来验证系统的值是否正确。


- 如果给定了入射点$(x_0,y_0)$，那么$x_2,y_2$就是可以被计算出来，因此整个系统的$x_1,y_1,x_3,y_3$也得以被计算出来了，因此入射角度也就迎仞而解了。