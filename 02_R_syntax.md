### Rstudio
- Case-sensitive
- Tab for auto-complete
- Check environment window at right-side for data integrity
# Syntax
`=` assignment
`== `, `!=` comparsion
### Vector
`c()` vector init (shorten for Combind)
`B = c(2,3,4)`
`rep()` repeatation (value, repeat_times)
`seq()` sequence (from, to, by) inclusive
```
z = rep(c(1, 10), 2) print(z) 1 10 1 10
y = rep(c(1,10), c(2,2)) print(y) 1 1 10 10
x = seq(from=1, to=10, by=2) print(x) 1 3 5 7 9
```
### Data set generation with `matrix()` `data.frame()`
R analysis is done with `matrix` or `data.frame` data

```
x1 = seq(1,10,1)
matrix(data, nrow, ncol, byrow)
MATRIX_R = matrix(data=x1, nrow=5)
print(MATRIX_R)
1 6
2 7
3 8
4 9
5 10
```