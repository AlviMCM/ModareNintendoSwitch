---
title: "Ghid Modare Nintendo Switch"
---
Tutorial actualizat pe data de **09.08.2026!**

Bun venit la tutorialul care te va ajuta sa folosesti Nintendo Switch-ul modat.
Site-uri pentru jocuri:
* https://not.ultranx.ru - **Recomandare primara**
* https://nxbrew.net/
* https://taodung.com/
* https://switchgamesmall.icu/
* https://romslab.com/
* https://switchroms.io/

---
# Pornirea consolei

Pentru inceput daca consola este oprita pentru a executa payload-ul instalat dupa modare se va apasa scurt butonul de pornire si se va astepta cateva secunde pentru ca consosola sa intre in bootloaderul **HEKATE IPL**. Este posibil ca consola sa nu porneasca din prima incercare din diverse motive, astfel se va repeta din nou apasarea butonului pana ce va intra in bootloader.
**ATENTIE! A NU SE APASA LUNG PE BUTONUL DE PORNIRE** 

![[Pasted image 20250919133246.png]]
![[Hekate.png]]

---
# Official Firmware sau Custom Firmware sau Android

## Official Firmware
Pentru a accesa Firmware-ul original cu care a venit consola, dupa ce s-a incarcat **Bootloaderul Hekate IPL** se va apasa cu degetul pe butonul de **Reboot** apoi se va selecta **OFW** (**Normal** inseamna ca va intra din nou in **HEKATE IPL**).
Aici puteti folosi Switch-ul in mod normal cum a venit din fabrica.

---

![[reboot.bmp]]
![[ofwornormal.bmp]]

---
## Custom Firmware **ATENTIE!**

Pentru a intra in Firmware-ul custom care te va lasa sa instalezi jocuri backup sau sa aplici teme custom sau tot felul de modificari software ale consolei, **MAJORITATEA TIMPULUI SE VA SELECTA EMUMMC CFW** din meniul **Launch**, celelalte optiuni sunt pentru utilizatorii avansati care stiu ce vor sa faca.

---

![[Launch.bmp]]
![[Launcher.bmp]]

---
### Instalare de jocuri
Dupa ce s-a incarcat, puteti sa va jucati jocurile instalate la cerere sau puteti instala jocuri la randul vostru.
Pentru a instala un joc, recomand sa folositi **DB Installer/DBI** care il puteti accesa din meniul de **Album**. Urmatorul pas este sa conectati consola la un **PC/Laptop** (voi folosi **Windows**), apoi se va executa **Run MTP responder** din acea lista, un folder ar trebui sa se deschida automat, puteti instala jocuri in **copiind fisierele dezarhivate(cu WinRAR sau 7zip) in partitia SD Card Install (se pot instala mai multe deodata)**. Daca jocul nu este actualizat instalati si update-ul pentru joc care de obicei este descarcat separat.

---

![[Album.jpg]]
![[HBMENU_DBI.jpg]]
![[2025091913474600.jpg]]
![[2025091914034900.jpg]]
![[Pasted image 20250919144546.png]]
![[Pasted image 20250919144643.png]]
![[Pasted image 20250919145009.png]]

---
### Teme personalizate
Pentru a instala o tema noua, se va utiliza **Themezer-NX** sau daca nu functioneaza folositi **NXThemes-Installer**. Cel mai simplu este sa folositi **Themezer-NX**, dar acesta poate sa nu functioneze cateodata (serverul nu este online sau nu este actualizat). Folosind **Themezer-NX** este foarte simplu, selectati o tema care va place si instalati pe rand toate "subtemele" selectandu-le si apasand butonul verde de **Install**, dupa ce ati facut acest lucru apasati pe **+** de doua ori de pe joycon pentru a instala, dati reboot pentru a aplica tema. **DACA DUPA APLICARE NU SE MAI POATE ACCESA CFW, INTRATI IN HAKATE-IPL->TOOLS->USB TOOLS->SD CARD SI CONECTATI SWITCH-UL LA PC/LAPTOP SI STERGETI FOLDERUL 0100000000001000 DIN ATHMOSPHERE/CONTENTS DIN PARTITIA SDCARD. DACA PROBLEMA PERSISTA LA MAJORITATEA TEMELOR, INCERCATI SA NU INSTALATI TEMA DE LOCKSCREEN, DACA INCA PERSISTA ESTE POSIBIL CA FIRMWARE-UL SA FIE PREA NOU SI TREBUIE ASTEPTAT PENTRU VERSIUNI MAI NOI DE THEMEZER**. Pentru varianta **NXThemes-Installer** se vor descarca temele de pe internet (de pe site-ul [Themezer](https://themezer.net/) sau alte site-uri care credeti ca sunt de incredere) apoi se vor incarca in folderul Themes (daca nu exista se v-a crea) cu switch-ul conectat la **PC/Laptop** din partitia **SD CARD**.

---
#### Themezer
![[Themezer.jpg]]
![[ThemezerMenu.jpg]]
![[SelectionThemezer.jpg]]
![[InstallThemezer.jpg]]
![[POPUPThemezer.jpg]]
![[ThemezerAccept.jpg]]
![[ThemezerReboot.jpg]]

---
#### NxThemes-Installer
![[NXThemes 1.jpg]]
![[NXMENU.jpg]]
![[NXThemezer.jpg]]
![[NXALLAPPS.jpg]]
![[2025091914094100.jpg]]

---
### Altele
Unele aplicatii nu pornesc sau dau crash la firmware un motiv ar fi ca sunt pornite in modul **Applet**, o posibila remediere este sa il porniti in modul **Full memory/Non-Applet** tinand apasat butonul **R** de pe joycon in timp ce porniti un joc si selectati user-ul, daca ati executat cu bine instructiunea se va deschide **HBMENU** si nu va aparea **Applet Mode**.

---
#### Applet
![[2025091914342700.jpg]]

---
#### Non-Applet
![[2025091914344400.jpg]]
![[2025091914342700 1.jpg]]

---
## Android
Partitia de Android se gaseste in meniul **More Configs**->**LineageOS**.
![[Options.bmp]]

