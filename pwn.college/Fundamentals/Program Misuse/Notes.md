

### level 1 - cat

```bash
$ cat /flag
```

### level 2 - more

```bash
$ more /flag
```

### level 3 - less

```bash
$ less /flag
```

### level 4 - tail

```bash
$ tail /flag
```

### level 5 - head

```bash
$ head /flag
```

### level 6 - sort

```bash
$ sort /flag
```

### level 7 - vim 

```bash
$ vim /flag
```

### level 8 - e acs 

```bash
$ emacs /flag
```

### level 9 - nano 

```bash
$ nano /flag
```

### level 10 - rev

```bash
$ rev /flag | rev
```

### level 11 - od

```bash
$ od /flag --format=c
```

### level 12 - hd

```bash
$ hd /flag
```

### level 13 - xxd

```bash
$ xxd /flag
```

### level 14 - base32

```bash
$ base32 /flag | base32 -d
```

### level 15 - base64

```bash
$ base64 /flag | base64 -d
```

### level 16 - split

```bash
$ split /flag | cat xaa
```

### level 17 - gzip

```bash
$ gzip /flag && gzip -dc /flag.gz
```

### level 18 - bzip2

```bash
$ bzip2 -z /flag && bzip2 -dc /flag.bz2
```

### level 19 - zip

```bash
$ zip test2.zip /flag && unzip -c test2.zip
```

### level 20 - tar

```bash
$ tar -cf test.tar /flag && tar -xf test.tar -O
```

### level 23 - genisoimage

```bash
$ genisoimage -sort /flag 
```

### level 26 - make

```bash
$ make -s --eval=$'x:\n\t-'"cat /flag"
```

### level 27 - nice

```bash
$ nice /bin/sh -p
```

### level 28 - timeout

```bash
$ timeout 1 cat /flag
```

### level 29 - stdbuf

```bash
$ stdbuf --output=L cat /flag
```

### level 30 - setarch

```bash
$ setarch x86_64 cat /flag
```

### level 31 - watch

```bash
$ watch -x cat /flag
```

### level 32 - socat

```bash
$ socat -u EXEC:'cat /flag' STDOUT
```

### level 33 - whiptail 

```bash
$ whiptail --textbox "/flag" 50 50 
```

### level 34 - awk

```bash
$ 
```

### level 35 - sed

```bash
$ 
```

### level 36 - ed

```bash
$ 
```

### level 37 - chown

```bash
$ 
```

### level 38 - chmod

```bash
$ 
```

### level 39 - cp

```bash
$ 
```

### level 41 - perl 

```bash
$ 
```

### level 42 - python

```bash
$ 
```

### level 45 - date

```bash
$ 
```

### level 46 - dmesg

```bash
$ 
```

### level 47 - wc

```bash
$ 
```

### level 48 - gcc

```bash
$ 
```

### level 49 - as

```bash
$ 
```

### level 50 - wget

```bash
$ 
```

### level 51 - ssh-keygen

```bash
$ 
```
