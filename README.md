# kalipi-fix-re4son
Fix sources list for good update/upgrade kali 2020.3a

1.open your terminal
  # sudo -i
-tipp your acc/user passwort
  # cd ..
  # cd etc/apt
  # nano sources.list
2.(delete) replace the lyrics  with :

 deb http://http.kali.org/kali kali-rolling main contrib non-free

 deb-src http://http.kali.org/kali kali-rolling contrib non-free

 deb http://http.kali.org/kali kali-rolling-only main contrib non-free

 deb-src http://http.kali.org/kali kali-rolling-only main contrib non-free

 deb http://http.kali.org/kali kali-debian-picks main contrib non-free

 deb-src http://http.kali.org/kali kali-debian-picks contrib non-free

   # -ctrl + c
   # -click y and 2x ENTER
  # cd sources.list.d
  # nano re4son.list
 3.(delete) replace the lyrics  with :
 
 deb http://http.re4son-kernel.com/re4son kali-pi main 

 deb http://http.re4son-kernel.com/re4son kali-pi-next main

 deb http://http.re4son-kernel.com/re4son kali-gem main
 
   # -ctrl + c
   # -clck y and 2x ENTER
   
  # cd
  # apt update -y
  # apt upgrade -y
  
 
   
