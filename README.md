# petits-exercices-bash
Une série d'exercices et tests, faisant office de memo BASH


### exp 1

```bash
jibl@pc-alienware-jib:~$ mafonc () { return 1; exit 0; }; export AHBON=$(mafonc);
jibl@pc-alienware-jib:~$ echo "$AHBON"

jibl@pc-alienware-jib:~$ mafonc () { echo "ahdaccord"; return 1; exit 0; }; export AHBON=$(mafonc);
jibl@pc-alienware-jib:~$ echo "$AHBON"
ahdaccord
jibl@pc-alienware-jib:~$ mafonc () { echo "ahdaccord"; return 1; exit 3; }; export AHBON=$(mafonc);
jibl@pc-alienware-jib:~$ echo "$AHBON"
ahdaccord
jibl@pc-alienware-jib:~$ 

```
