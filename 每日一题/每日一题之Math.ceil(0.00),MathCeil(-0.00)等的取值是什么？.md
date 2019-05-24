# Math.ceil(0.00),MathCeil(-0.00)等的取值是什么？

Math.ceil(0.00),MathCeil(-0.00),Math.round(0.00),Math.round(-0.00),Math.floor(0.00),Math.floor(-0.00)的取值是什么？

答：.Math.ceil 为大于当前数目的最小整数。

Math.round为四舍五入，相当于当前数字加0.5，在去最小整数。

Math.floor为小于当前数字的最大整数。

Math.ceil(0.00):0.0

Math.ceil(-0.00):-0.0

Math.ceil(0):0.0

Math.ceil(-0):0.0

Math.round(0.00):0

Math.round(- 0.00):0

Math.round(0):0

Math.round(- 0):0

Math.floor(0.00):0.0

Math.floor(-0.00):-0.0

Math.floor(0):0.0

Math.floor(-0):0.0