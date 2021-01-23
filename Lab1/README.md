# 題目
利用 Bisection, False Position, Modify False Position, Secant , Newton, Fixed Point 算出 $x$
1. $e^x-3\cos(2x)=8.3,x\in (-10,2)$
2. $e^{x\sin x}-x\cos(2x)=2.8,x-\in(-5,5)$
3. $7x^2\sin(4x)-6x\cos(x)=-5.6$
4. $4x+e^x-3\cos(x)$

## 1. $e^x-3\cos(2x)=8.3,x\in (-10,2)$
Answer Set: $-8.79929905512278…, -6.86108366470742..., -5.74873075092705...,$$-3.46759919923776..., -2.95425050915349..., 1.43002820651934...$
* Epsilon=$1e-6$

|                       | 答案 | 誤差 | 迴圈次數 |
| --------------------- | ---- | ---- | -------- |
| Bisection             | 1.4300284386     | $2.32 × 10^{−7}$     | 22         |
| False Position        | 1.4300282192     | $1.26 × 10^{−8}$     | 8         |
| Modify False Position | 1.4300279207     | $2.85 × 10^{−7}$     | 21         |
| Secant                | 1.4300282066     | $8.06 × 10^{−11}$     | 9         |
| Newton                | -6.8610836647     | $7.42 × 10^{−12}$     | 6         |
| Fixed Point           | 1.3366435100     | $9.33 × 10^{−2}$     | 27         |

* Epsilon=$1e-8$

|                       | 答案 | 誤差 | 迴圈次數 |
| --------------------- | ---- | ---- | -------- |
| Bisection             | 1.4300282039      | $2.61 × 10^{−9}$     | 29         |
| False Position        | 1.4300282066      | $8.06 × 10^{−11} $     | 10         |
| Modify False Position | 1.4300282088      | $2.11 × 10^{−9}$     | 28         |
| Secant                | 1.4300282065      | $1.93 × 10^{−11}$     | 10         |
| Newton                | -6.8610836647     | $7.42 × 10^{−12}$     | 6         |
| Fixed Point           | 1.3366436015      | $9.33 × 10^{−2}$     | 30         |

## 2. $e^{x\sin x}-x\cos(2x)=2.8,x-\in(-5,5)$
Answer Set: $-3.52615250912331...,-1.44679581196116..., 1.01169156675946...,$$2.58294853520121..., 4.28036194164056...$

* Epsilon=$1e-6$

|                       | 答案 | 誤差 | 迴圈次數 |
| --------------------- | ---- | ---- | -------- |
| Bisection             | 1.0116913915      | $1.75 × 10^{-7}$     | 27         |
| False Position        | 4.2803619447      | $3.05 × 10^{−9}$     | 7         |
| Modify False Position | 4.2803622528     | $3.11 × 10^{−7}$     | 22         |
| Secant                | -1.4467958120     | $3.88 × 10^{−11}$     | 11         |
| Newton                | 5.2156151936      | $9.35 × 10^{−1}$     | 5         |
| Fixed Point           | nan     |      | 7         |

* Epsilon=$1e-8$

|                       | 答案 | 誤差 | 迴圈次數 |
| --------------------- | ---- | ---- | -------- |
| Bisection             | 1.0116915638     | $2.95 × 10^{−9}$     | 30         |
| False Position        | 4.2803619417      | $5.94 × 10^{−11}$     | 8         |
| Modify False Position | 4.2803619392     | $2.44 × 10^{−9}$     | 29         |
| Secant                | -1.4467958120      | $3.88 × 10^{−11}$     | 11         |
| Newton                | 5.2156151936     | $9.35 × 10^{−1}$     | 5         |
| Fixed Point           |      |      | 7         |

## 3. $7x^2\sin(4x)-6x\cos(x)=-5.6$
Answer Set: $-3.95161157194427..., -3.09299398945330..., -2.38654183004128...,$
$-1.63745784120068..., 0.889442561257829..., 1.49093790619175...,$
$2.4598319871287..., 3.04788652865807...$

* Epsilon=$1e-6$

|                       | 答案 | 誤差 | 迴圈次數 |
| --------------------- | ---- | ---- | -------- |
| Bisection             | -3.0929937959     | $1.93 × 10^{−7}$     | 27         |
| False Position        | -1.6374578393     | $1.90 × 1^{−9}$     | 13         |
| Modify False Position | -1.6374581326     | $2.91 × 10^{−7}$     | 23         |
| Secant                | 0.8894425613     | $4.21 × 10^{−11}$     | 14         |
| Newton                | 0.8894425613     | $4.21 × 10^{−11}$     | 5         |
| Fixed Point           | nan     |      | 10         |

* Epsilon=$1e-8$

|                       | 答案 | 誤差 | 迴圈次數 |
| --------------------- | ---- | ---- | -------- |
| Bisection             | -3.0929939868      | $2.65 × 10^{−9}$     | 30         |
| False Position        | -1.6374578411      | $1.00 × 10^{−10}$     | 14         |
| Modify False Position | -1.6374578389      | $2.30 × 10^{−9}$     | 30         |
| Secant                | 0.8894425613      | $4.21 × 10^{−11}$     | 14         |
| Newton                | 0.8894425613      | $4.21 × 10^{−11}$     | 5         |
| Fixed Point           | nan     |      | 10         |

## 4. $4x+e^x-3\cos(x)$
Answer Set: $-1.91476068112171...$

* Epsilon=$1e-6$

|                       | 答案 | 誤差 | 迴圈次數 |
| --------------------- | ---- | ---- | -------- |
| Bisection             | -1.9147607684      | $8.72 × 10^{−8}$     | 24         |
| False Position        | -1.9147607684      | $1.72 × 10^{−5}$     | 200         |
| Modify False Position | -1.9147687271     | $8.04 × 10^{−6}$     | 104         |
| Secant                | -1.9147606811     | $2.17 × 10^{−11}$     | 7         |
| Newton                | -1.9147606811     | $2.17 × 10^{−11}$     | 6         |
| Fixed Point           | nan     |      | 13         |

* Epsilon=$1e-8$

|                       | 答案 | 誤差 | 迴圈次數 |
| --------------------- | ---- | ---- | -------- |
| Bisection             | -1.9147606799     | $1.22 × 10^{−9}$     | 30         |
| False Position        | -1.9147608560      | $1.74 × 10^{−7}$     | 285         |
| Modify False Position | -1.9147607658      | $8.46 × 10^{−8}$     | 145         |
| Secant                | -1.9147606811      | $2.17 × 10^{−11}$     | 8         |
| Newton                | -1.9147606811      | $2.17 × 10^{−11}$     | 6         |
| Fixed Point           | nan     |      | 13         |



# 結論
Newton 和 Secant 是比較好的演算法，在迴圈終止條件 epsilon < $10^{−6}$ 的狀況下，誤差就在 $10^{−11}$ 到 $10^{−12}$ 內，且迴圈次數也偏小。其次是 False Position，迴圈次數雖然和 Secant 差不多，但誤差劣於 Secant。再來是 Bisection 和 Modify False Position，次數偏高，且誤差也大於前面所提三種演算法。

至於 Fixed Point，在這次使驗發現他的應用範圍有限制，除了第一個式子有跑出結果(並且有很大的誤差)，其他三者最終皆發散。

此外，在這次實驗中，發現根據中間值定理所發展出的演算法(Bisection, False Position, Modify False Position)，所形成的誤差會根據迴圈終止條件 epsilon 大小而有明顯變化。