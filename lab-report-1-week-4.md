
# ***Lab report of the week 3 and 4 lab section A***
---
Auther: **[Sarkis Bouzikian](https://github.com/oplikos)**
---
## Fix 1
---
In week 3 lab the understanding of the software and its bugs were limited but when we start the lab everything became clear.
getting the raw file from the professor and running out the first test to explore the potential output of the software 
we start to realize the extent of the bugs in the program, our first few attempts were to fix one char at a time such as

``'['``, ``']'`` , ``'('`` , ``')'``.

the first fix we attempt is add a couple if statements to monitor if there is a bracket or not and to skip that test eventually
I come up with one statement that combines all the if statements
```
 if (nextOpenBracket < 0 || nextCloseBracket < 0 || openParen < 0 || closeParen < 0) {
                break;
            }
 ```
 
to trace the History of this edit please click on the [link][1] 

![image](./fix 1.png)
---
## Fix 2
---

to trace the History of this edit please click on the [link][2] 
![image](./fix 2.png)
## Fix 3
![image](./fix 3.png)


[1]: https://github.com/oplikos/markdown-parse/commit/11a377c7d99b38fe39f6127d603209bc1ff5365f#diff-c703a0ec03474d601c6bf846740b293e0538bccf38d5f677a302457479e9c652
[2]: https://github.com/oplikos/markdown-parse/commit/571de421522bb9d64c11f2aff46b6540791a31e3#diff-c703a0ec03474d601c6bf846740b293e0538bccf38d5f677a302457479e9c652
[3]: https://github.com/oplikos/markdown-parse/commit/1dc9867bdf3cbd19b3de727ab515719403b6435c#diff-c703a0ec03474d601c6bf846740b293e0538bccf38d5f677a302457479e9c652
