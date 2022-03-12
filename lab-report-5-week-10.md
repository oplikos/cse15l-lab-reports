
# ***Lab report 5 of the week 9 and 10 lab section A***
---
Auther: **[Sarkis Bouzikian](https://github.com/oplikos)**
---

# Part 1:

---

running bash on my script.

![running bash on my code](mtScript.jpg)

my scripte results

![My script result](myscriptresult.jpg)

changing scripts to run on main markdown parse

![changing Script to main](mainscript.jpg)

running bash script on main and exporting result to main.txt and then do ```diff```

![changing and running script on main and export to main then use diff to compair files](changingandrunningbashtomaintxt.jpg)

compairing the results and checking what whent wrong 

![checking diff result](checkindiffresult.jpg)

acording to my bash run i can see that i have couple resultes fail due to 
```
java.lang.StringIndexOutOfBoundsException:
```
and the test file 148 and 149 i got exported link where the main code did not

for the file 148 and 149 i got result because ive changed my code completly and made it as it reads the ```.``` and grabs the link that is in between the ```(  )``` but that approch of my code failed due that the file 148 and 149 dont containe any links which will not produce proper result

![mayc code wrong part](mycodewrongpart.jpg)

fix: i should add anif statment where if there is not words after ```.``` in this case i should not grab the link name and add it to the array so skipping the sentancese that are not complite as a link 


and the part that ```java.lang.StringIndexOutOfBoundsException:``` to examin this issue i run the bash solo to see which files are causing it and open those file up to see what is common issue in between 

![where the exaption is happening](otherfilessameissue.jpg)

the file 259 for example 

![file 259](file250.jpg)

and the issue nited in here that the file 259 and the other one dont contain any ``` [ , ] , ( , ) ``` which is the result should be emptystring but my code is crushing to fix this issue all i have to do is check if the file dose not contain any ``` [ , ] , ( , ) ``` then return empty string.


---
[BACK TO MAIN](https://oplikos.github.io/cse15l-lab-reports/)
