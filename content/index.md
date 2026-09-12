---
title: Ghid Modare Nintendo Switch
password: PicoFlyRomania
---
Tutorial actualizat pe data de **11.09.2026!** Foloseste [[index#^glosar|Glosarul]] pentru termeni necunoscuti. Creat de **Muresan Alvaro**. Link-ul oficial al comunitatii noastre, il gasesti pe [[https://discord.gg/Xatgkd8Tx9|Discord]]

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

![[Pasted image 20250919133246.png|800]]
![[Hekate.png|800]]

---
# Official Firmware sau Custom Firmware sau Android

## Official Firmware
Pentru a accesa Firmware-ul original cu care a venit consola, dupa ce s-a incarcat **Bootloaderul Hekate IPL** se va apasa cu degetul pe butonul de **Reboot** apoi se va selecta **OFW** (**Normal** inseamna ca va intra din nou in **HEKATE IPL**).
Aici puteti folosi Switch-ul in mod normal cum a venit din fabrica.

---

![[reboot.bmp|800]]
![[ofwornormal.bmp|800]]

---
## Custom Firmware **ATENTIE!**

Pentru a intra in Firmware-ul custom care te va lasa sa instalezi jocuri backup sau sa aplici teme custom sau tot felul de modificari software ale consolei, **MAJORITATEA TIMPULUI SE VA SELECTA EMUMMC CFW** din meniul **Launch**, celelalte optiuni sunt pentru utilizatorii avansati care stiu ce vor sa faca.

---

![[Launch.bmp|800]]
![[Launcher.bmp|800]]

---
### Instalare de jocuri
Dupa ce s-a incarcat, puteti sa va jucati jocurile instalate la cerere sau puteti instala jocuri la randul vostru.
Pentru a instala un joc, recomand sa folositi **DB Installer/DBI** care il puteti accesa din meniul de **Album**. Urmatorul pas este sa conectati consola la un **PC/Laptop** (voi folosi **Windows**), apoi se va executa **Run MTP responder** din acea lista, un folder ar trebui sa se deschida automat, puteti instala jocuri in **copiind fisierele dezarhivate(cu WinRAR sau 7zip) in partitia SD Card Install (se pot instala mai multe deodata)**. Daca jocul nu este actualizat instalati si update-ul pentru joc care de obicei este descarcat separat.

---

![[Album.jpg|800]]
![[HBMENU_DBI.jpg|800]]
![[2025091913474600.jpg|800]]
![[2025091914034900.jpg|800]]
![[Pasted image 20250919144546.png|800]]
![[Pasted image 20250919144643.png|800]]
![[Pasted image 20250919145009.png|800]]

---
### Teme personalizate
Pentru a instala o tema noua, se va utiliza **Themezer-NX** sau daca nu functioneaza folositi **NXThemes-Installer**. Cel mai simplu este sa folositi **Themezer-NX**, dar acesta poate sa nu functioneze cateodata (serverul nu este online sau nu este actualizat). Folosind **Themezer-NX** este foarte simplu, selectati o tema care va place si instalati pe rand toate "subtemele" selectandu-le si apasand butonul verde de **Install**, dupa ce ati facut acest lucru apasati pe **+** de doua ori de pe joycon pentru a instala, dati reboot pentru a aplica tema. **DACA DUPA APLICARE NU SE MAI POATE ACCESA CFW, INTRATI IN HAKATE-IPL->TOOLS->USB TOOLS->SD CARD SI CONECTATI SWITCH-UL LA PC/LAPTOP SI STERGETI FOLDERUL 0100000000001000 DIN ATHMOSPHERE/CONTENTS DIN PARTITIA SDCARD. DACA PROBLEMA PERSISTA LA MAJORITATEA TEMELOR, INCERCATI SA NU INSTALATI TEMA DE LOCKSCREEN, DACA INCA PERSISTA ESTE POSIBIL CA FIRMWARE-UL SA FIE PREA NOU SI TREBUIE ASTEPTAT PENTRU VERSIUNI MAI NOI DE THEMEZER**. Pentru varianta **NXThemes-Installer** se vor descarca temele de pe internet (de pe site-ul [Themezer](https://themezer.net/) sau alte site-uri care credeti ca sunt de incredere) apoi se vor incarca in folderul Themes (daca nu exista se v-a crea) cu switch-ul conectat la **PC/Laptop** din partitia **SD CARD**.

---
#### Themezer
![[Themezer.jpg|800]]
![[ThemezerMenu.jpg|800]]
![[SelectionThemezer.jpg|800]]
![[InstallThemezer.jpg|800]]
![[POPUPThemezer.jpg|800]]
![[ThemezerAccept.jpg|800]]
![[ThemezerReboot.jpg|800]]

---
#### NxThemes-Installer
![[NXThemes 1.jpg|800]]
![[NXMENU.jpg|800]]
![[NXThemezer.jpg|800]]
![[NXALLAPPS.jpg|800]]
![[2025091914094100.jpg|800]]

---
### Altele
Unele aplicatii nu pornesc sau dau crash la firmware un motiv ar fi ca sunt pornite in modul **Applet**, o posibila remediere este sa il porniti in modul **Full memory/Non-Applet** tinand apasat butonul **R** de pe joycon in timp ce porniti un joc si selectati user-ul, daca ati executat cu bine instructiunea se va deschide **HBMENU** si nu va aparea **Applet Mode**.

#### Applet
![[2025091914342700.jpg|800]]

#### Non-Applet
![[2025091914344400.jpg|800]]
![[2025091914342700 1.jpg|800]]

## Android
Partitia de Android se gaseste in meniul **More Configs**->**LineageOS**.
![[Options.bmp|800]]

# Aplicatia HATS Tools WIP
>[!info|Nu exista?]
>Aceasta aplicatie poate fi indisponibila pentru clientii mai vechi unde pe vremea aceea nu a existat. Asa ca trebuie facut update manual folosind calculatorul, apoi ar trebui sa apara. 
>Daca aveti instalata aplicatia asigurati-va ca sunteti conectati la **internet** pentru a evita potentiale erori.

Mai jos se poate observa meniul principal al aplicatiei cu toate facilitatile ei:
![[MeniuPrincipal HATS Tools.jpg]]

Am ajuns sa prefer aceasta aplicatie comparativ cu **DBI** deoarece include mai multe facilitati destul de importante si deasemenea include si unelete de instalat jocuri ca si in **DBI** si are un design mult mai placut. Aceasta aplicatie este esentiala pentru **actualizarea pachetului HATS** fara a mai folosi un calculator, dar mai mult si de a face **upgrade/downgrade firmware-ului** sau instalarea de **aplicatii** si **jocuri**. Mai jos voi include cateva dintre facilitatile acestei aplicatii:
## APP SHOP (Instalare aplicatii)
Aceasta facilitate a aplicatiei va usureaza mult mai mult munca de instalare a aplicatiilor, in cazul in care acestea functioneaza si nu trebuie un build custom de la comunitatea de modare. Tot ce trebuie sa faceti este dati click (cu degetul sau controlerul) pe pictograma **APP SHOP**, iar apoi la fel pe aplicatia pe care vreti sa o instalati, dupa care apasati pe butonul de **Install**. Dupa ce ati instalat aplicatia, aveti doua optiuni **Launch** sau **Remove**, prima **lanseaza** aplicatia, iar a doua o **dezinstaleaza**. Aplicatia va aparea in **HBMENU** dupa ce ati terminat instalarea. Daca doriti sa va apare pe **HOME SCREEN(Ecranul Principal)** folositi aplicatia **SPHAIRA**. 
## UPDATE HATSPACK
Folosind aceasta facilitate puteti sa vad actualizati pachetul **HATS** cu care esti pregatita consola dupa modare fara a o mai conecta la calculator sau prin intermediul severelor FTP sau asemanator. **Folositi modul overwrite everything din [[#HATS Install Mode]] pentru a pastra toate aplicatiile instalate sau varianta 4 pentru instalare curata**.

Apasati cu degetul sau cu folosind controllerul pe pictograma **UPDATE HATSPACK** si apoi se pot vedea toate versiunile disponibile ale pachetului. Apasati pe cea mai recenta versiune si apoi **Continue** daca va avertizeaza sa faceti backup, dupa care **Download**.  Cand e gata de descarcat apasati butonul **Launch** cand va intreaba **"Launch HATS Installer?"**. Consola va intra mai apoi intr-un terminal de instalare si dupa instalare puteti intra inapoi pe **CFW EMMC** astfel ati actualizat pachetul.
![[HATS TOOLS Releases.jpg]]




## ADVANCED SETTINGS
Aici gasiti setarile avansate din aplicatia [[#Aplicatia HATS Tools WIP|HATS TOOLS]]
![[HATS TOOLS Advanced Settings.jpg]]
### HATS Install Mode
Puteti face update pachetului HATS in 4 moduri diferite precum:
1. **Overwrite everything** care **suprascrie** peste pachetul vechi de HATS pastrand folderele **Atmosphere**, **Bootloader** si **Switch** de pe cardul sd.
2. **Replace Atmosphere** care sterge folderul **Atmosphere** de pe card si il schimba cu elementele noi din pachetul descarcat pastrand folderele  **Bootloader** si **Switch**.
3. **Replace Atmosphere + Bootloader** care sterge folderele **Atmosphere** si **Bootloader** de pe card si il schimba cu elementele noi din pachetul descarcat pastrand folderul **Switch**.
4. **Replace Atmosphere + Bootloader + Switch** care sterge **tot (Atmosphere, Bootloader, Switch)** si instaleaza pachetul "fresh".
![[HATS TOOLS Install Mode.jpg]]
# Emulatoare in CFW WIP
>[!tip] **Retroarch**
>Chiar daca Retroarch cuprinde majoritatea emulatoarelor, am observat de-a lungul timpului ca cele instalate individual sunt mai performante decat nucleele din Retroarch. De multe ori in Retroarch am avut probleme cu **performanta** si sistemul **audio** si am stat mult timp sa incerc sa il fac sa mearga pe dispozitivele mai low end in trecut (Nintendo avand aceeasi problema), asa ca am decis ca este mai rapid si mai performant sa introduc in tutorial emulatoarele separat!

Aici puteti vedea cum se instaleaza jocuri, precum si unele configuratii pentru emulatoarele din sistemul instalat si instalarea lor deasemenea dupa serviciul de modare. Pe aceste va puteti juca jocuri de pe console mai vechi decat consola Nintendo Switch, ca exemplu fiind **Nintendo Entertainment System (NES)**, **Super Nintendo Entertainment System (SNES)**, **PlayStation Portable(PSP)**, altele mai noi pur si simplu nu ar functiona din cauza puterii reduse a consolei, de exemplu **PlayStation 3(PS3)** sau cu performanta redusa in CFW **PlayStation 2(PS2)** dar pot functiona mai bine in mediul **Android**. Multe alte emulatoare vor fi adaugate in ghid pe rand cu tot cu explicatii si link-uri necesar. Lista cu emulatoarele si jocurile aferente poate fi gasita mai jos:
## Nintendo Entertainment System(NES)![[PNES.png|64]]
Acest emulator te va ajuta sa te joci jocurile din trecut de pe consola de jocuri **Nintendo Entertainment System(NES)** direct de pe **CFW**. Acest emulator **NU NECESITA BIOS** si trebuie doar sa puneti jocurile (**ROM**) in locatia **sdcard->switch->pnes->roms->"jocul tau.NES"** asta dupa ce ati instalat aplicatia. Exista doua variante pentru instalare:
### Varianta 1: [[#APP SHOP (Instalare aplicatii)|HATS Tools APP SHOP]] (Recomandat!)
Asta este cea mai simpla metoda de instalarea a aplicatiei. Folositi tutorialul din ghid si instalati direct aplicatia din **APP SHOP**.

# Grand Theft Auto V
Pentru a instala acest joc pe consola veti avea nevoie de urmatoarele fisiere:
1. Grand Theft Auto Legacy: Personal de pe Steam/Rockstar Launcher/Epic Games Store sau [Din alta sursa BZZHR](https://steamrip.com/gta-5-4wi/)
2. [NSPDRepackGUI.exe](https://1drv.ms/u/c/a79b792eb4b4f3eb/IQD6Y8qPFCffQpBbkM-jMfsqAbqMBD1ALg0Vu5kg5ufZzDU?e=4Q1iME)
3. [gtav-patcher-4.00.7z](https://1drv.ms/u/c/a79b792eb4b4f3eb/IQBU8wPtTK8iSZbX5v3Q9PbaASxsujUsZeQPyddf3eNWe_4?e=Zkjb7I)
4. [build-9b485eb8.7z](https://1drv.ms/u/c/a79b792eb4b4f3eb/IQAcGVG7vRwLRpg4g6oswBhCAYmssnFyuyQwvYwuHpjBFd8?e=o6lbBj)
5. [Update.zip](https://1drv.ms/u/c/a79b792eb4b4f3eb/IQCyeWHgmb5fQZ8b_GFELCc5AUyBFbOoIUmHbK--sZ5mprE?e=DhnYYd)

Dupa ce ati descarcat toate fisierele necesare, primul lucru care trebuie facut este sa le dezarhivati cu un program precum **7zip** sau ceva asemanator intr-un folder de lucru.
![[Pasted image 20260911124041.png|800]]
>[!info] 
>Folderul cu **GTACOPY** din imagine este copia jocului instalata de pe **Rockstar Games Launcher**, dumneavoastra puteti sa faceti o copie a originalului sau nu, desi este recomandat sa aveti o copie si sa nu lucrati direct pe fisierele originale.
Dupa ce totul arata ca si in imagine se vor efectua pasii de mai jos:
1. Se deschide **NSPDRepackGUI.exe** apoi se alege de la butonul de **Browse** folderul **build-9b485eb8/game_nx_master.nspd** apoi se apasa pe butonul **Start repack**, dupa ce operatiunea este completa se da click pe butonul **Open output folder** sau alternativ din **outputs/(nume build)/nsp** si acolo se va gasi fisierul **.nsp** pe care il veti instala cu DBI, dupa instalare se trece mai departe.
 ![[Pasted image 20260911125031.png]]
 ![[Pasted image 20260911233103.png]]
2. Se copiaza din folderul de **Update** descarcat fisierele care se termina in **.rpf** si se lipesc cu replace in folderul **update** din copia jocului peste fisierele **.rpf** de acolo.
![[Pasted image 20260912000412.png]]
![[Pasted image 20260912000056.png]]
![[Pasted image 20260911233642.png]]
3. Acum trebuie construit jocul pentru platforma Nintendo Switch folosind **gtav-patcher-4.00**, in acest tutorial se foloseste **win-x64**. Se folosesc setarile provenite in imaginea de mai jos. **GTA V Folder** este locatia folderului principal al jocului unde se gaseste si fisierul executabil. **Platform pack** se gaseste in folderul **build-9b485eb8/platformpack**. Dupa ce v-ati asigurat ca toate setarile sunt bune, mai jos dati click pe butonul **Patch** cu albastru si asteptati pana ce fisierele sunt convertite. Atentie, conversia dureaza destul de mult! La final daca totul a decurs bine puteti verifica daca fisierele din folderul principal al jocului are fisiere care au in nume **switch.rpf** in loc de **x64.rpf** si a aparut folderul **switch**.
![[Pasted image 20260911234039.png]]
![[Pasted image 20260911234239.png]]
![[Pasted image 20260912000509.png]]
4. Acesta este pasul final care de asemenea dureaza destul de mult, dar este si destul de usor, tot ce trebuie sa faceti este sa creati un folder denumit **romfs** in **\atmosphere\contents\0100B00B51230000** si sa copiati datele convertite ale jocului de la pasul 3 si ar trebui sa arate ca si mai jos:
![[Pasted image 20260911235938.png]]
>[!warning] Probleme
>Daca jocul da crash dupa ce ati urmat pasii, cel mai probabil nu s-au copiat toate fisierele cum trebui, mai dati odata paste si verificati manual care fisiere lipsesc, cel mai probabil lipsesc cele din folderul nou creat denumit **switch**.
>Cred ca cea mai buna solutie ca acest lucru sa nu se intample este sa scoateti cardul din consola si sa le copiati direct de pe PC.

>[!question]  Glosar
>**WIP** = Work In Progress = In lucru
>**CFW** = Custom Firmware = Sistem operare customizat
>**OFW** = Official Firmware = Sistem operare oficial
>**ROM** = Read Only Memory = Fisier binar ce contine de regula jocul ^glosar

<span  id="glosar"></span>




