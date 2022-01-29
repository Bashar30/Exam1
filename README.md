#Plan van aanpak
Project
Contents 
1.	Inleiding 	3 
1.1.	Doelen 	3 
1.2.	Resultaat 	3 
1.3.	Lijst van eisen 	3 
1.4.	Functioneel ontwerp 	4 
Achtergrond informatie 	4 
Opdrachtnemer 	4 
Opdrachtgever 	4 
Probleemstelling 	4 
Functieoverzicht 	4 
1.5.	Technisch ontwerp 	5 
1.6.	Scope 	6 
1.6.1.	In-scope 	6 
1.6.2.	Uit-scope 	6 
1.7.	Uitgangspunten en randvoorwaarden 	7 
1.8.	Risico’s 	6 
2.	Project Management 	7 
2.1.	Planning-Tijd 	7 
2.2.	Organisatie 	7 
2.3.	Kosten 	8 
2.4.	Kwaliteit 	8 
2.5.	Informatie 	9 
********
1.	Inleiding 
We kregen opdracht voor de Proeve van bekwaamheid, Dat is een bedrijf die heet Hamminga Bouw en Tuinmarkt BV op donderdag 5 april door een onbekend oorzaak een brand volledig in de as gelegd. Daarbij is alleen de werkplaats gespaard gebleven. Alle servers en werkstations zijn gesneuveld. 
We gaan met de team de netwerk infrastructuur opbouwen, we gaan volgens de nieuwe.
************
1.1.	Doelen   
 
1-	Netwerk infrastructuur bouwen. 
2-	Een netwerk bouwen. 
3-	Een ruimte en faciliteiten regelen. 
4-	bestaande website hosten. 
5-	Vol Back-ups.
************
1.2.	Resultaat  
Na oplevering van dit project beschikt…….. 
 **********
1.3.	Lijst van eisen 
 
1-	Installatie van twee servers “ Windows server 2019 . Linux server”  
2-	Configureren van een fortigate firewall en Cisco Switch  
3-	Configureren van access point 
4-	En printer server maken   
5-	Web server  
6-	Beveiliging “ Ssh” 
7-	Monitoring van de hele server  
8-	Back-up aanmaken voor cliënten en volle server back-up  
 	 ********
1.4.	Functioneel ontwerp 
Achtergrond informatie 
Hamminga organisatie is een winkel bouw en tuin artikelen.
*******
Opdrachtnemer :
Bashar Almassarra
Wassem Kabbash
*****
Opdrachtgever 
Sander de groot 
Sony Fidanque 
*****
Probleemstelling 
Er is brand en alles is gesneuveld. 
******
Functieoverzicht 
De bouwmarkt zal herbouwd worden en ook er komt een nieuwe netwerk infrastructuur. 
*****
1.5.	Technisch ontwerp  
Tekening van het netwerk  
![image](https://user-images.githubusercontent.com/97803920/151669250-24cf52cc-abb4-4479-abab-b9fccf580320.png)
Gebruikte IP-adressen en instellingen  
Vlan’s  	Name vlan 	      Ip adressen 	  Subnet 	           Default gateway 
99 	      Management 	      10.10.99.0/28 	255.255.255.240 	 10.10.99.14 
3 	      Server 	          10.10.3.0/24 	  255.255.255.0 	   10.10.3.254 
13 	      Medewerkers 	    10.10.13.0/23 	255.255.254.0 	   10.10.13.254 
20        Wifi-medewerker 	10.10.20.0/23 	255.255.254.0 	   10.10.21.254 
25 	      Wifi-gast 	      10.10.25.0/23 	255.255.254.0 	   10.10.25.254 
******
 1.6.	Scope 
We gaan scopes aanmaken voor alle inkomende apparaten binnen het netwerk
******
1.6.1.	In-scope  
Medewerker scope  
Wifi-medewerker  
Wifi-gasten 
******
1.6.2.	Uit-scope 
We gaan geen scope maken voor het server vlan en management vlan  
******
1.7.	Risico’s

No. 	Omschrijving 	 	 	 	Actie 

1 	Server defect 	no 	Alles moet opnieuw 	Alles defect 	Server is Defect opnieuw geconfigureerd moet worden. 
2 	Internetverbinding los 	yes 	Gasten en medewerkers geen internet hebben 	Niemand heeft toegang tot internet  	Check de configuratie van alle netwerk apparaten. 
3 	FortiGate Polices 	yes 	Geen impact 	Geen risico 	Policy toevoegen of een verwijderen 
5 	Acces point Niet goed geconfigureerd 	yes 	Geen draadloze en internet 	Geen wifi 	Configuratie checken 
6 	Brand 	Yes 	Alles defect 	Op alle apparaten 	Alle netwerk apparaten en infrastructuur opnieuw gebouwd moet worden 

