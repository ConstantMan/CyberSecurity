# Kali Linux : Σημειώσεις

- Πακέτα  before upgrade 64x,
2472
- Αρχικά sudo apt update && sudo apt upgrade + [sudo apt-get dist-upgrade](https://linuxhint.com/apt_get_upgrade_dist_upgrade/) και εγκατάσταση του neofetch
Packages: 2514(dpkg) + 6
- [Static IP](https://pimylifeup.com/raspberry-pi-static-ip-address/) με interface τον adapter
- Eπόμενο βήμα Aντιγραφή των αρχείων .zsh από το arch και δημιουργία aliases 
<br>**Παρατηρώ ότι υπάρχει ήδη αρχείο zsh** το οποίο θα αλλάξω και θα αποθηκέυσω εδώ το πρωτότυπο 
- Αντιγραφή του original zsh στο repsoitory και δαιγραφή του από το kali καθώ και προσθήκη των άλλων αρχείων
>Να θυμάσαι για [copy/paste](https://unix.stackexchange.com/questions/106480/how-to-copy-files-from-one-machine-to-another-using-ssh) μέσω zsh πχ αποστολή ολόκληρου του φακέλου από Αrch σε Kali : scp -r  /home/konstantman/.zsh/zsh-syntax-highlighting kali@192.168.1.4:/home/kali/.zsh
- Δημιουργία aliases και αρχείου στο repository για τα πακέτα που κατεβάζω
- [Καθαρισμός Server](#clean) 
- Έλεχος της κατάστασης με [ncdu](ncdu.md)
> Crash με το ncdu / και με την χρήση ncdu --exclude-kernfs ,να δοκιμάσω το mc για έλεγχο του storage
- Όλες μου οι δοκιμές με τον [network adapter](#network) αυτές οι [οδηγίες](https://gitlab.com/kalilinux/packages/realtek-rtl8188eus-dkms)
είναι για kali μεν αλλά όχι για το [rasberry](#pi) και τον [kernel](#Kernel) του
- Δοκιμή Wifite και monitor/packet injection με ethernet όλα δουλεύουν ακόμα και η εντολή ``` sudo airmon-ng check kill``` που μαλλον κολλάει γιατί ουσιαστικά σκοτώνει τον networkmanager,και κατέβασμα των hcxdumptool hcxtools 
- Πρέπει να φτιάξω τα configs και το home να 
 https://pimylifeup.com/raspberry-pi-static-ip-address/
- Εγκατάσταση [sherlock.py](https://github.com/sherlock-project/sherlock) 
 
 
 
 








## Χρήσιμα Sites

- <span id="clean">Για καθάρισμα</span> 

https://www.fossmint.com/keep-ubuntu-system-clean/

https://www.esds.co.in/kb/how-to-clean-up-ubuntu-server/ 

- <span id="network">Network Adapter</span> 

https://gitlab.com/kalilinux/packages/realtek-rtl8188eus-dkms

https://github.com/davidbombal/Kali-Linux/blob/main/TP-Link%20TL-WN722N%20adapter

https://www.youtube.com/watch?v=tYnjMiTTdms

https://www.youtube.com/watch?v=RyUFLEpyr-E&t=35s

- <span id="pi">Rasbery</span>
 
https://github.com/aircrack-ng/rtl8188eus/issues/86

https://github.com/aircrack-ng/rtl8188eus/issues?q=Raspberry+

- <span id="Kernel">Kernel</span> 

https://linuxhint.com/install-linux-headers-kali-linux/

https://re4son-kernel.com/re4son-pi-kernel/

https://http.kali.org/kali/pool/main/l/linux/






