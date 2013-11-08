# perlrer #
Use perl regex syntax, get perl results in R!


```perl
$string = 'This is a test';
print scalar $string =~ m/this/i;
```

```
## 1
```


```r
library(perlrer)
string = "This is a test"
string %m% "/this/i"
```

```
## [1] TRUE
```


```perl
$string = 'This is a test';
$string =~ s/this/that/i;
print $string;
```

```
## that is a test
```


```r
library(perlrer)
string = "This is a test"
string %s% "/this/that/i"
```

```
## [1] "that is a test"
```

