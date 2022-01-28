
# ***Lab report of the first week lab***
---
Auther: **[Sarkis Bouzikian](https://github.com/oplikos)**
---
* Im studing [computer engineering at UCSD][2]
* currently student of [Revelle College][3]
---
week 2 of CSE15L we did some example work on testing diffrent layout Using MarkDown style in [Github][4] 
to explore the diffretn output of Markdown assgiment [Click here Example.md](https://oplikos.github.io/cse15l-lab-reports/example.html)

---
# The following is the week 1 activity
---
## Part 1
  
  the following image is the proof of succecsfuly installing the Virtual studio code by following this link [click here][1]
  
---
![image](./1.png)

---

## Part 2
 ```
for this part i had some issue with my vscode i wasnt able to connect to the school server using my vscode but then
i used moaXtreamto access school server (other class account and remotly from that class access this class sshdoing the 
 ```
![image](./2.png)

---
## Part 3
---

Im a window user for that reason i had to downloed a program called
OpenSSH, which is a program that can connect your computer to other computers
that have this kind of account:
[Install OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)

to find CSE15L course-specific account [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)

Then, in Visual Studio Code, we are going to connect to the remote computer
using VSCode's remote option.  For reference, we're following the steps in
[“Connect to a remote
host”](https://code.visualstudio.com/docs/remote/ssh#_connect-to-a-remote-host)
step.

For the first step, open a terminal in VSCode (Ctrl or Command + \`, or use the
Terminal → New Terminal menu option).

```
$ ssh cs15lwi22zz@ieng6.ucsd.edu
```
but the `zz` should be replaced by your class id 

### Example of the output when connecting for the first time 
```
⤇ ssh cs15lwi22zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
```

![image](./3.png)

---
## Part 4
---
running some commands in the terminal susch as 
- `cd ~`
- `cd`
- `ls -lat`
- `ls -a`
- `ls <directory>` where `<directory>` is
`/home/linux/ieng6/cs15lwi22/cs15lwi22abc`, where the `abc` is replace by my personal class signiture 
- `cp /home/linux/ieng6/cs15lwi22/public/hello.txt ~/`
- `cat /home/linux/ieng6/cs15lwi22/public/hello.txt`


![image](./4.png)

---
## Part 5
---
this part was about to creat a java file with the following code 

```
class WhereAmI {
  public static void main(String[] args) {
    System.out.println(System.getProperty("os.name"));
    System.out.println(System.getProperty("user.name"));
    System.out.println(System.getProperty("user.home"));
    System.out.println(System.getProperty("user.dir"));
  }
}
```
and save it the local computer then 
using `scp command 
```
scp WhereAmI.java cs15lwi22zz@ieng6.ucsd.edu:~/

```

sending it to the remote computer 

![image](./5.5.png)

![image](./5.png)

---
## Part 6
---
this part is to creat ssh-keygen, creates a pair of files called the public key and private key to gain easy access to our personal class directory

the following should be the set of code to expect but when we first did it ssh wasnt working on my local computer so i had delet ssh client and reinstall it to work (incase window user gets this kind of errors

```
# on client (your computer)
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/joe/.ssh/id_rsa): /Users/joe/.ssh/id_rsa
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /Users/joe/.ssh/id_rsa.
Your public key has been saved in /Users/joe/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:jZaZH6fI8E2I1D35hnvGeBePQ4ELOf2Ge+G0XknoXp0 joe@Joes-Mac-mini.local
The key's randomart image is:
+---[RSA 3072]----+
|                 |
|       . . + .   |
|      . . B o .  |
|     . . B * +.. |
|      o S = *.B. |
|       = = O.*.*+|
|        + * *.BE+|
|           +.+.o |
|             ..  |
+----[SHA256]-----+
```

If you're on Windows, follow the extra `ssh-add` steps here: [https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_keymanagement#user-key-generation](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_keymanagement#user-key-generation)



---
## Part 7
---

this part is when we i did it first time my ssh didnt work so i had to redot this week and counted
how many keystroks took me to run the commend 
starting by selecting the code  it was
`select->ctr+C->click->crt+v->enter->click->select->crt+c->click->ctr+v->enter`
in totale of `11` key strocks to complet the assigment 

![image](./6.png)

---
[1]: https://code.visualstudio.com/docs
[2]: https://ece.ucsd.edu/undergraduate/undergraduate-programs/computer-engineering-major
[3]: https://builder.guidebook.com/g/#/guides/revelle/details
[4]: https://github.com/
