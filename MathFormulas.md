# MathFormulas

## 一元微分篇

### 基本求导公式

$$
\left( C \right) '=0
$$
$$
\left( x^{\mu} \right) '=\mu x^{\mu -1}
$$
$$
\left( \sin x \right) '=\cos x
$$
$$
\left( \cos x \right) '=\sin x
$$
$$
\left( \tan x \right) '=\sec ^2x
$$
$$
\left( \cot x \right) '=-\csc ^2x
$$
$$
\left( \sec x \right) '=\sec x\tan x
$$
$$
\left( \csc x \right) '=-\csc x\cot x
$$
$$
\left( a^x \right) '=a^x\ln a
$$
$$
\left( e^x \right) '=e^x
$$
$$
\left( \log _ax \right) '=\frac{1}{x\ln a}
$$
$$
\left( \ln x \right) '=\frac{1}{x}
$$
$$
\left( \arcsin x \right) '=\frac{1}{\sqrt{1-x^2}}
$$
$$
\left( \arccos x \right) '=-\frac{1}{\sqrt{1-x^2}}
$$
$$
\left( \arctan x \right) '=\frac{1}{1+x^2}
$$
- 注:
  $$
  \sec x = \frac{1}{\cos x}
  $$

  $$
  \csc x = \frac{1}{\sin x}
  $$

  ### 泰勒展开

  $$
  \sin x=x-\frac{x^3}{3!}
  $$
  $$
  \arcsin x=x+\frac{x^3}{3!}
  $$
  $$
  \tan x=x+\frac{x^3}{3}
  $$
  $$
  \arctan x=x-\frac{x^3}{3}
  $$
  $$
  \cos x=1-\frac{x^2}{2!}+\frac{x^4}{4!}
  $$
  $$
  e^x=1+x+\frac{x^2}{2!}+\frac{x^3}{3!}
  $$
  $$
  \ln \left( 1+x \right) =x-\frac{x^2}{2!}+\frac{x^3}{3!}
  $$
  $$
  \left( 1+x \right) ^a=1+ax+\frac{a\left( a-1 \right)}{2!}x^2
  $$
  
  

## 一元积分篇

### 不定积分的基本积分公式

$$
\int{k\text{d}x}=kx+C
$$
$$
\int{x^{\mu}\text{d}x}=\frac{x^{\mu +1}}{\mu +1}+C\left( \mu \ne 1 \right) 
$$
$$
\int{\frac{1}{x}\text{d}x}=\ln \left| x \right|+C
$$
$$
\int{\frac{1}{1+x^2}\text{d}x}=\arctan x+C
$$
$$
\int{\frac{1}{\sqrt{1-x^2}}\text{d}x}=\arcsin x+C
$$
$$
\int{\cos x\text{d}x}=\sin x+C
$$
$$
\int{\sin x\text{d}x}=-\cos x+C
$$
$$
\int{\frac{1}{\cos ^2x}\text{d}x}=\int{\sec ^2x\text{d}x}=\tan x+C
$$
$$
\int{\frac{1}{\sin ^2x}\text{d}x}=\int{\csc ^2x\text{d}x}=-\cot x+C
$$
$$
\int{\sec x\tan x\text{d}x}=\sec x+C
$$
$$
\int{\csc x\cot x\text{d}x}=-\csc x+C
$$
$$
\int{e^x\text{d}x}=e^x+C
$$
$$
\int{a^x\text{d}x}=\frac{a^x}{\ln a}+C
$$
$$
\int{\text{sh}x\text{d}x}=\text{ch}x+C
$$
$$
\int{\text{ch}x\text{d}x}=\text{sh}x+C
$$
$$
\int{\tan x\text{d}x}=-\ln \left| \cos x \right|+C
$$
$$
\int{\cot x\text{d}x}=\ln \left| \sin x \right|+C
$$
$$
\int{\sec x\text{d}x}=\ln \left| \sec x+\tan x \right|+C
$$
$$
\int{\csc x\text{d}x}=\ln \left| \csc x-\cot x \right|+C
$$
$$
\int{\frac{1}{a^2+x^2}\text{d}x}=\frac{1}{a}\arctan \frac{x}{a}+C
$$
$$
\int{\frac{1}{x^2-a^2}\text{d}x}=\frac{1}{2a}\ln \left| \frac{x-a}{x+a} \right|+C
$$
$$
\int{\frac{1}{\sqrt{a^2-x^2}}\text{d}x}=\arcsin \frac{x}{a}+C
$$
$$
\int{\frac{1}{\sqrt{x^2+a^2}}\text{d}x}=\ln \left( x+\sqrt{x^2+a^2} \right) +C
$$
$$
\int{\frac{1}{\sqrt{x^2-a^2}}\text{d}x}=\ln \left( x+\sqrt{x^2 - a^2} \right) +C
$$

### 积分中值定理

##### 常规形式

$$
\text{若函数在闭区间}\left[ a,b \right] \text{上连续，则}
$$
$$
\exists \xi \in \left[ a,b \right] 
$$
$$
\int_a^b{f\left( x \right) \text{d}x}=f\left( \xi \right) \left( b-a \right)
$$

##### 推广

$$
\text{若}f\left( x \right) \text{、}g\left( x \right) \text{在闭区间}\left[ a,b \right] \text{上可积，且}g\left( x \right) \text{在此区间上不变号，则}
$$
$$
\exists \xi \in \left[ a,b \right] 
$$
$$
\int_a^b{f\left( x \right) g\left( x \right) \text{d}x}=f\left( \xi \right) \int_a^b{g\left( x \right) \text{d}x}
$$