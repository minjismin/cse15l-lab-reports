
#Lab report 3

## Streamlining ssh Configuration

### 1

![ssh config](show ssh config file.png)

I created config file which contained 

```
Host ieng6
  HostName ieng6.ucsd.edu
  User cs15lsp22aqj
```

By creating this I could login to ieng6 remote server by just typing >ssh ieng 6


### 2

![login ssh with ieng6](log in ssh  and scpusing ieng6.png)

So as I said, I could login using ieng6 and also could copy the file from my local account by using command "scp"


## Setup Github Access from ieng6

### 1
I created new public key to access my github account

![github public key](public key stored in github.png)

### 2
My private key is saved under the file named id_rsa

![private key saved](private key in id_rsa.png)

### 3
By setting up that, I could commit and push while I logged into ieng6 account

![ieng6 push and commit](git commit and push.png)

### 4
The link of my commit
[commit link](https://github.com/minjismin/markdown-parser/commit/8e72ba3baf603a9ba367eb1409cb098d75d365b4)

## Copy whole directories with scp -r

### 1 copy using scp -r

! [scp-r](scp-r.png)

### Show logging into your ieng6 account after doing this and compiling and running the tests for your repository

! [test](test.png)

### how (like in the last step of the first lab) combining scp, ;, and ssh to copy the whole directory and run the tests in one line

! [oneline](oneline.png)

but since my file is in icloud it copied my whole icloud file, so it didn't work I moved my file to my computer file from icloud as TA said but it didn't work too. 

