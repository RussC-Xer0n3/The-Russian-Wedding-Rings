# The Russian Wedding Rings
## A look at returning a single value from several differing radii

### Purpose
A quick search returns the following information in Symbolic representation of The Russian Wedding Rings;

**Symbolism of Russian Wedding Rings The Russian wedding ring symbolises more than the original roots of Russian marriage. In religious terms, the ring represents, the Father, Son and Holy Spirit of the Catholic church, coming together to form the Holy Trinity.**

I wondered if it would be possible to complete the task using various sized radii in the variables, let's take a look;

**P.S. Rusher was my old handle, so was whiterabbit**

### Some were too large
```
#! /in/env/python

pi = 3.14159

r1 = 1
r2 = 2
r3 = 3

r = (r3**(r1**(r2)**3))**3

area = (pi*(r)**3)

print(area**area)
exit(1)
#Thu 11 Apr 2019 18:21:53 BST  with love from rusher kiss kiss
```

### Some were not meant to be
```
#! /in/env/python

pi = 3.14159

r1 = 2
r2 = 1
r3 = 0

r = 1*(r3**(r1**(r2)**3))

area = (pi*(r)**3)

print(area)
exit(1)
#Thu 11 Apr 2019 18:21:53 BST  with love from rusher kiss kiss
```

### Others married up nicely
```
#! /in/env/python

pi = 3.14159

r1 = 2
r2 = 1
r3 = 0

r = 1*(r3**(r1**(r2)**3))

area = ((pi*(r**3))**3)

print(area**area)
exit(1)
#Thu 11 Apr 2019 18:21:53 BST  with love from rusher kiss kiss
```

### Finally, the Wedding
Finally, they all marry up and the value returns 1.0, true, one.
```
#! /in/env/python

pi = 3.14159

r1 = 2
r2 = 1
r3 = 0

r = 1*(r3**(r1**(r2)**3))

area = (pi*(r)**3)

print(area**area)
exit(1)
#Thu 11 Apr 2019 18:21:53 BST  with love from rusher kiss kiss
```

### Further exploration
There was then further exploration into equilateral infinite loops to form a self-reinforcing helictical sphere which I dubbed [Fusion in the github repository](https://github.com/RussC-Xer0n3/The-old-Fusion-Repository) which you can read about properly [in these GitHub pages](https://RussC-Xer0n3.github.io/The-old-Fusion-Repository).
