# matlib


This is an python implementation of very useful functions in matlab:

## 1) mapminmax
https://www.mathworks.com/help/nnet/ref/mapminmax.html

Process matrices by mapping row minimum and maximum values to [-1 1]
### Description:
mapminmax processes matrices by normalizing the minimum and maximum values of each row to [ymin, ymax].

### Syntax:
[y, ps] = matlib.mapminmax(x) # default ymin=-1.0, ymax=+1.0
[y, ps] = matlib.mapminmax(x, ymin, ymax)

---
I will implement more functions.
Follow my twitter for further news about this library:
https://twitter.com/javidanmd

