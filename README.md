# Nethunter-In-Termux
This is a script by which you can install Kali nethunter (Kali Linux) in your termux application without rooted phone 
### Steps For Installation
1. Download Termux from Play store or Appstore
2. Open it and type `apt update && apt install upgrade `
3. type `pkg install curl`
1. then download net-hunter type   `curl -LO https://raw.githubusercontent.com/Hax4us/Nethunter-In-Termux/master/kalinethunter`
2. Give execution permission `chmod +x kalinethunter`
3. Run script `./kalinethunter`
4. Now just start kali nethunter `startkali`
### If it does not work
1. `pkg install fish`
2. type  command - `fish`
1. inside fish type `curl -LO https://raw.githubusercontent.com/Hax4us/Nethunter-In-Termux/master/kalinethunter`
2. Give execution permission `chmod +x kalinethunter`
3. Run script `./kalinethunter`
4. Now just start kali nethunter `startkali`


### Compulsory Steps For First Time Use (Only for Fisrt Time After Installation)
1. So after `startkali`, execute this command `wget https://http.kali.org/kali/pool/main/k/kali-archive-keyring/kali-archive-keyring_2018.1_all.deb`
2. `apt install ./kali-archive-keyring_2018.1_all.deb`

### In Case Of SSL error: certificate verify failed
Rerun script with extra parameter `--insecure` or copy paste this command `./kalinethunter --insecure`E 
https


