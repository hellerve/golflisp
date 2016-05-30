# golflisp

A few macros and aliases for zepto for better code golf performance.

## Installation

Don't.

But if you really want to, `zeps install hellerve/golflisp` is your friend.

## Why

```
$ cat fizzbuzz.zp
(for 100 ((write (cond ((= (mod i 15) 0) "fizzbuzz") ((= (mod i 5) 0) "fizz") ((= (mod i 3) 0) "buzz") (else i)))))
$ wc -c fizzbuzz.zp
  116 fizzbuzz.zp
$ cat fizzbuzz-golf.zp
(Σ 100 ((w (Ο ((n? (% i 15)) "fizzbuzz") ((n? (% i 5)) "fizz") ((n? (% i 3)) "buzz") (χ i)))))
$ wc -c fizzbuzz-golf.zp
  98 fizzbuzz-golf.zp
```

Also the code gets less readable, which is nice.

<hr/>

Cheers
