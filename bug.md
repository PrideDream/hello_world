Sorry, I'm a C++ newbie and didn't notice the compiled executable.

I have three qusetion.

# The first one is installation.

I used the following command to install

```
 make OPT=-DUSE_OPENMP ENV=LINUX
```

![image-20221009190606027](bug.assets/image-20221009190606027.png)

when i run the following command

```
./bcpd -x lucy-x.txt -y lucy-y.txt
```

![image-20221009190833073](bug.assets/image-20221009190833073.png)

The last line reports: Segment error (core dumped)