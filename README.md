# Android Gateway SMS
Il s'agit d'une application Android qui permet l'émission et la reception des SMS.
Notre application consiste:
⦁	  Crée une application android à l'aide du logiciel Android Studio avec une base de donnée local SQLite.
   Cette application android est l'intermédiaire entre SI et le GSM.
⦁	  Crée un service windows et une petite base de donnée qui contient les messages d'envoie et de reception au niveau du
systéme d'information.
---> la relation entre le SI(systéme d'information) et l'application se fait à partir de web service et à travers la réquete :
         -Http GET au niveau de l'émission .
         -Http POST au niveau de reception.
