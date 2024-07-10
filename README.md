```
❯ while true; do
docker compose pull && docker compose up   
sleep 1
done

[+] Pulling 1/1
 ✔ app Pulled                                                                              0.8s 
[+] Running 1/0
 ✔ Container app  Created                                                                  0.0s 
Attaching to app
app  | version 1.3.0
app exited with code 0
[+] Pulling 2/2
 ✔ app 1 layers [⣿]      0B/0B      Pulled                                                 1.9s 
   ✔ 422ed46b1a92 Already exists                                                           0.0s 
[+] Running 1/0
 ✔ Container app  Recreated                                                                0.0s 
Attaching to app
app  | version 1.5.0
```


latest 指定しておけば、docker compose pull することで最新になる！
