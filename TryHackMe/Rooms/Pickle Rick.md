# Pickle Rick

- Xρήση ```nikto -h IP``` για εύρεση [αδυναμιών](#vulnerability) στον server
> Να ψάξω και το nessus και πως σχετίζονται 
- Επίσης directories scan με ```gobuster dir -u IP  -w```
> Με -x flag προσδιορίζεις συγκεκριμένα file extensions 


- Καλό [writeup του john hammond](https://www.youtube.com/watch?v=oCAtfcr3iUw&t=933s) 
> Σε search field ,για online και απλό injection δείχνει τα </br>```grep -R . (anything) ,grep -R . clue.txt (anything inside clue.txt) ``` </br> και </br> ```while read line; do echo $line; done < clue.txt```</br>
- Για [σύνθετο reverse shell](https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet) , όπου προφανώς αλλάζει η εκάστοτε εντολή , με ip 
απο ```ip addr show tun0```</br>και port ίδιο με την εντολή ```nc -lnvp``` που τρέχεις μετά για να επιτευχθεί η επικοιωνία 
## Χρήσιμα Sites

- <span id="vulnerability">Vulnerability Scanner</span>

https://cirt.net/Nikto2

https://www.freecodecamp.org/news/an-introduction-to-web-server-scanning-with-nikto/

https://www.youtube.com/watch?v=K78YOmbuT48

https://github.com/sullo/nikto

- <span id="shell">Reverse Shell</span>

https://www.youtube.com/watch?v=qDLtEP58bao

https://www.youtube.com/watch?v=bXCeFPNWjsM&t=24s

https://www.youtube.com/watch?v=vOEO_6xfsdo

https://www.youtube.com/watch?v=5Hyg9ZuC1i0
