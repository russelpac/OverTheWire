# OverTheWire
EJERCICIOS OVERTHEWIRE
# BANDIT
1.  level 1
- comandos: ssh, cat, ls
>clave: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
2.  level 2
- comandos: ls, cad ./-
>clave: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
3.  level 3
- comados: ls, cat "spaces in this filename"
>clave: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
4.  level 4
- comandos: ls,cd inhere,find, cat ...Hiding-From-You 
>clave: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
5.  level 5
-comandos: ls, cd inhere, cat ./-file07,cd .
>clave: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
6.  level 6
- comandos: ls, cd inhere,find . -size 1033c,cd maybehere07,cat .file2
>clave:HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
7.  level 7
- comandos: find / -user bandit7 -group bandit6 -size 33c,cat /var/lib/dpkg/info/bandit7.password
>clave: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
8.  level 8
- comandos: ls, grep "millionth" data.txt
>clave: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
9.  level 9
- comandos: cat data.txt ,sort data.txt | uniq -u
>clave: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
10. level 10
- comandos: strings data.txt 
>clave:FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
11.  level 11
- comandos:echo "" | base64 --decode
>clave :dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
12.  level 12
- comandos: echo "Gur cnffjbeq vf 7k16JArUVv5LxVuJfsSVdbbtaHGlw9D4" | tr 'A-Za-z' 'N-ZA-Mn-za-m'
>clave:7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4 
13.  level 13
- comandos: ls, mktemp -d,cat,cd,cp,cat data.txt |xxd -r >man,file, gzip -d,bzip2 -d,mv,tar -xvf 
>clave: FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
14.  level 14
- comandos: ls, ssh -p 2220 badit14@localhost -i sshkey.private,cat /etc/bandit_pass/bandit14
>clave: MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
15.  level 15
- comandos:ssh -p 30000 bandit14@localhost,nc 127.0.0.1 30000
>clave: 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
16.  level 16
- comandos:openssl s_client -connect localhost:30001
>clave: kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
17.  level 17
- comandos:nmap -p 31000-32000,ncat 127.0.0.1 --ssl 31790
- mkdir /tmp/bandit777,nano sshkey.private,chmod 400 sshkey.private
- ssh -p 2220 -i sshkey.private bandit17@bandit.labs.overthewire.org,whoami
cat /etc/bandit_pass/bandit17
>clave:EReVavePLFHtFlFsjn3hyzMlvSuSAcRD
18.  level 18
- comandos:ls, diff passwords.new passwords.old
>clave: x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO
19.  level 19
- comandos:ssh -p 2220 bandit18@bandit.labs.overthewire.org "cat readme"
- ssh -p 2220 bandit18@bandit.labs.overthewire.org "ls"
>clave:cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8
20.  level 20
- comandos:  ./bandit20-do cat /etc/bandit_pass/bandit20
>clave: 0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO
21.  level 21
- comandos: nc -lvpn 4444, ./suconnect 4444
>clave: EeoULMCra2q0dSkYj561DX7s1CpBuOBt
22.  level 22
- comandos: cd /etc/cron.d, cat /usr/bin/cronjob_bandit22.sh, cd /tmp
- cat t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
>clave: tRae0UfB9v0UzbCdn9cY0gQnds9GF58Q
23.  level 23
-  comandos: echo I am user bandit23|  md5sum | cut -d ' ' -f 1
- cd /tmp, cat 8ca319486bfbbc3663ea0fbe81326349
>clave: 0Zf11ioIjMVN551jX3CmStKLYqjk54Ga
24.  level 24
- comandos:echo "cat /etc/bandit_pass/bandit24 > /tmp/russ_test.txt" > script.sh
- chmod 777 script.sh, cat /tmp/russ_test.txt
>clave:gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8
25.  level 25
- comannos:cd /tmp, mkdir testeo, nano testeo.sh, chmod 777 testeo.sh, ./testeo.sh | nc 127.0.0.1 30002
> clave:iCi86ttT4KSNe1armKiwbQNmB3YJP3q4
26.  level 26
- comandos:ssh -p 2220 -i bandit26.sshkey bandit26@bandit.labs.overthewire.org, :e /etc/bandit_pass/bandit26
>clave: s0773xxkk0MXfdqOfPRVr9L3jJBUOgCZ
27. level 27
- comandos: shell, id, ./bandit27-do cat /etc/bandit_pass/bandit27
>clave: upsNCc7vzaRDx6oZC6GiR6ERwe1MowGB
28.  level 28
- comados:git clone ssh://bandit27-git@localhost:2220/home/bandit27-git/repo, cd /tmp, mkdir test_01
- cd test_01, cd repo,cat README
>clave:Yz9IpL0sBcCeuG7m9uQFt8ZNpS4HZRcN
29.  level 29
- comandos: cd /tmp, mkdir temp_03,cd mkdir temp_03, cd repo
- git clone ssh://bandit28-git@localhost:2220/home/bandit28-git/repo,git log 
- git show 3621de89d8eac9d3b64302bfb2dc67e9a566decd
>clave:4pT1t5DENaYuqnqvadYs1oE4QLCdjmJ7
30.  level 30
- comandos:cd /tmp, mkdir temp_04,cd mkdir temp_04, cd repo
- git clone ssh://bandit29-git@localhost:2220/home/bandit29-git/repo,git log
-  git branch -a,git checkout remotes/origin/dev, cat README.md 
>clave:qp30ex3VLz5MDG1n91YowTv4Q8l7CDZL
31.  level 31
- comandos:cd /tmp, mkdir temp_05,cd mkdir temp_05, cd repo
- git clone ssh://bandit30-git@localhost:2220/home/bandit30-git/repo ,git tag
- git show secret
>clave:fb5S2xb7bRyFmAvQYQGEqsbhVyJqhnDy
32.  level 32
- comandos:cd /tmp, mkdir temp_07, git clone ssh://bandit31-git@localhost:2220/home/bandit31-git/repo, 
- cd repo, nano key.txt, git add-f key.txt,git commit -m "Upload a file"
- git push -u origin master
> clave:3O9RfhqyAlVBEZpVb6LYStshZoqoSx5K 
33.  level 33
- comandos:$0, cat /etc/bandit_pass/bandit33
> clave:tQdtbs5D5i2vJwkO8mEyYEyTL8izoeJ0
# NATAS
1.  level 1
- clave:0nzCigAq7t2iALyvU9xcHlYN4MlkIwlq
2.  level 2
- clave:TguMNxKo1DSa1tujBLuZJnDUlCcUAPlI
3.  level 3
- clave: 3gqisGdR0pjm6tpkDKdIWO2hSvchLeYH
4.  level 4
- clave: QryZXc2e0zahULdHrtHxzyYkj59kUxLQ
5.  level 5
- clave: 0n35PkggAPm2zbEpOU802c0x0Msn1ToK 
6.  level 6
- clave: 0RoJwHdSKWFTYR5WuiAewauSuNaBXned
7. level 7
- clave: bmg8SvU1LizuWjx3y7xkNERkHxGre0GS
8. level 8
- clave: xcoXLmzMkoIP9D7hlgPlh9XD7OgLAe5Q 
9. level 9
- clave: ZE1ck82lmdGIoErlhQgWND6j2Wzz6b6t 
10. level 10
- clave: t7I5VHvpa14sJTUGV0cbEsbYfFP2dmOu
11. level 11
- clave: UJdqkK1pTu6VLt9UHWAgRZz6sVUZ3lEk
12.  level 12
- cookie: HmYkBwozJw4WNyAAFyB1VUc9MhxHaHUNAic4Awo2dVVHZzEJAyIxCUc5
- clave: yZdkjAYZRd3R7tq7T5kXMjMJlOIkzDeB
# LEVIATHAN
1.  LEVEL 1
- comandos: ls -la, grep "leviathan" bookmarks.html, cd .backup
> clave: 3QJ3TgzHDq
2.  LEVEL 2
- comandos:ls -la, ltrace ./check, password:sex,./check, cat /etc/leviathan_pass/leviathan2
> clave: NsN1HwFoyN
3.  LEVEL 3
- comandos:cd /tmp, mkdir testeo, touch "pro;bash", ~/printfile "pro;bash", whoami, cat /etc/leviathan_pass/leviathan3
> clave:f0n8h2iWLP
4.  LEVEL 4
- comandos: ltrace ./level3,password snlprintf, whoami, cat /etc/leviathan_pass/leviathan4
> clave: WG1egElCvO
5 .LEVEL 5
- comandos: cd .trash, ./bin, traducimos de binario a texto
> clave: 0dyxT7F4QD
6. LEVEL 6 
- comandos: ls,ltrace ./leviathan5, ln -s "/etc/leviathan_pass/leviathan6" "/tmp/file.log"
> clave: szo7HDB88w
7. LEVEL 7
- comandos:./leviathan6, for i in {0000..9999}; do ./leviathan6 $i | grep -v "Wrong"; done
- whoami, cat /etc/leviathan_pass/leviathan7
> clave: qEs5Io5yM8
# KRYPTON
1.  level 1
- comandos: Decodificamos S1JZUFRPTklTR1JFQVQ= en base64
> clave: KRYPTONISGREAT
2. level 2
- comandos:cd /krypton/, cd krypton1, ls, cat krypton2
- decodificamos YRIRY GJB CNFFJBEQ EBGGRA en ROT13
> clave: ROTTEN
3. level 3
- comandos:cd /tmp, mkdir testeo, cd testeo, ln -s /krypton/krypton2/keyfile.dat, chmod 777
-  /krypton/krypton2/encrypt /etc/issue, touch text, nano text "copiamos:ABCDEFGHIJKLMNOPQRSTUVWXYZ "
- /krypton/krypton2/encrypt text, cat ciphertext "nos da el texto de text codificado"
- cat /krypton/krypton2/krypton3 | tr "[MNOPQRSTUVWXYZABCDEFGHIJKL]"" "[A-Z]"
> clave: CAESARISEASY
4. level 4
- comandos:
> clave: 
5. level 5
- comandos:
> clave: 
6. level 6
- comandos:
> clave: 
7. level 7
- comandos:
> clave:
8.  level 8 