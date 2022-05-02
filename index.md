<nav class="w3-container w3-teal w3-center w3-margin-top">
<br>
  <a href="https://www.facebook.com/profile.php?id=100075972987666"><i class="fa fa-facebook-official w3-hover-opacity"></i></a>
  <a href="https://www.instagram.com/russellclarke821"><i class="fa fa-instagram w3-hover-opacity"></i></a>
  <a href="https://www.pinterest.co.uk/russellclarke821/"><i class="fa fa-pinterest-p w3-hover-opacity"></i></a>
  <a href="https://twitter.com/Developing821"><i class="fa fa-twitter w3-hover-opacity"></i></a>
  <a href="https://www.linkedin.com/in/russell-clarke-09a1a5238"></a><i class="fa fa-linkedin w3-hover-opacity"></i>
<br>
</nav>
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
<head>
    <meta content="text/html; charset=utf-8" http-equiv="Content-Type">
    <meta charset="UTF-8">
    <meta name="description" content="Projects and Portfolio">
    <meta name="keywords" content="HTML, CSS, JavaScript, PHP, MySQLi, Python, Java, C, C++, C#, Time, Shapes">
    <meta name="author" content="Russell Clarke">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<footer class="w3-container w3-teal w3-center w3-margin-top">
  <p>Find me on social media.</p>
  <a href="https://www.facebook.com/profile.php?id=100075972987666"><i class="fa fa-facebook-official w3-hover-opacity"></i></a>
  <a href="https://www.instagram.com/russellclarke821"><i class="fa fa-instagram w3-hover-opacity"></i></a>
  <a href="https://www.pinterest.co.uk/russellclarke821/"><i class="fa fa-pinterest-p w3-hover-opacity"></i></a>
  <a href="https://twitter.com/Developing821"><i class="fa fa-twitter w3-hover-opacity"></i></a>
  <a href="https://www.linkedin.com/in/russell-clarke-09a1a5238"></a><i class="fa fa-linkedin w3-hover-opacity"></i>
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
</footer>
