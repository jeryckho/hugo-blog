---
title: "Le projet Maestro #1"
date: 2012-02-27T17:28:00+01:00
draft: false

featuredImage: ""
categories: ["récit"]
tags: ["maestro"]
author: "Jérycho"
---
adam@odyseus:~$ __*telnet symphonie.dyndns.com 8080*__  
Trying 92.122.189.95...  
Connected to symphonie.dyndns.com.  
Escape character is '^]'.  
__*&gt; GET /zatrak.php?id=adam HTTP/1.0*__  
  
HTTP/1.1 200 OK  
Server: Apache/2.0.59 (Unix) mod_ssl/2.0.59 OpenSSL/0.9.8g  
Time: 21:40:05 GMT  
Content-Length: 98  
Connection: close  
Content-Type: text/html  
  
&lt;html&gt;&lt;head&gt;&lt;title&gt;ADAM&lt;/title&gt;&lt;/head&gt;  
&lt;body&gt;  
DFDC3CD7F2AE9771381166632EF70382  
&lt;/body&gt;&lt;/html&gt;  
  
Connection closed by foreign host.  
adam@odyseus:~$ __*decrypt.pl -s DFDC3CD7F2AE9771381166632EF70382 -p flickansomelektemedelden*__  
Á²× )i¿J“N¾iÐ  
adam@odyseus:~$ __*decrypt.pl -s DFDC3CD7F2AE9771381166632EF70382 -p melenkurion*__  
H€xÝ}á?"8#7x§ã  
adam@odyseus:~$ __*decrypt.pl -s DFDC3CD7F2AE9771381166632EF70382 -p m0nalisa*__  
?P r.L¿±Ì¸ã¯Õ  
adam@odyseus:~$ __*decrypt.pl -s DFDC3CD7F2AE9771381166632EF70382 -p mithrandir*__  
124.32.60.27  
adam@odyseus:~$ __*telnet 124.32.60.27 6667*__  
NOTICE AUTH :*** Looking up your hostname  
NOTICE AUTH :*** Found your hostname, cached  
NOTICE AUTH :*** Checking Ident  
__*&gt; NICK AdaW*__  
NOTICE AUTH :*** Confirm Ident  
__*&gt; PASS flickansomelektemedelden*__  
NOTICE AUTH :*** Ident confirmed  
PING :74264576  
__*&gt; PONG :74264576*__  
:elysium 001 AdaW :Welcome back to elysium, AdaW  
:elysium 251 AdaW :There are 4 users on 1 server  
:elysium 376 AdaW :End of /MOTD command.  
__*&gt; JOIN :#arpege*__  
:AdaW JOIN #arpege  
:elysium 353 AdaW = #arpege :AdaW @ChAr +Berserk +ShadOs  
:elysium 366 AdaW #arpege :End of /NAMES list.  
(+Berserk) : ah c'est pas trop tôt  
:ChAr MODE #arpege +v AdaW  
__*&gt; MSG #arpege : Oui, je sais, je suis en retard...*__  
(@ChAr) : Un peu, oui, il faut bien le dire. Mais bienvenue tout de même, Adam.  
__*&gt; MSG #arpege : Mais j'assume totalement... En fait, j'ai mis au moins une heure pour retrouver mon mot de passe du mardi. Sérieusement, les gars, on en fait pas un peu trop question sécurité ? Un serveur perso de chat privé dont l'adresse est cryptée avec des mots de passe suivant les jours de la semaine. A part dans James Bond je n'ai jamais vu ça.*__  
(+Berserk) : principe de précaution  
(@ChAr) : Oui, la question a déjà été abordée. Il vaut mieux en faire trop que pas assez. L'an dernier on est passé entre les gouttes, mais de justesse.  
__*&gt; MSG #arpege : D'accord, je sais bien, mais tout de même. Bon peu importe, on en reparlera une autre fois... Le bon côté, c'est qu'aujourd'hui je savais que vous m'attendriez. Shadows est là ?*__  
__*&gt; IDLE ShadOs*__  
:elysium 422 AdaW :idle time for ShadOs is 0h43min12s  
(@ChAr) : Il faut le considérer comme absent... Il a programmé son bot pour se connecter un peu avant le début de la réunion, comme ça demain il pourra lire tout ce qu'on a écrit et décidé.  
__*&gt; MSG #arpege : Moi, je suis un peu en retard et vous en faites tout un plat... Lui, il est carrément absent et personne ne dit rien. Je rêve.*__  
(+Berserk) : c'est différent ! déja rien que pour le décalage horaire  
(@ChAr) : Adam, on ne te dit rien. Tu es parfois en retard, c'est comme ça. On ne va pas en faire un plat, comme tu dis. Bon, et si on disait que la réunion est commencée ? J'aimerais ne pas me coucher trop tard, moi...  
__*&gt; MSG #arpege : Oui, ok. J'imagine que c'est à moi de commencer. J'entre pas dans les détails mais j'ai récupéré les dossiers des élèves auprès de la scolarité. Juste à signaler que l'excuse du club d'informatique pourra surement nous reservir si on en abuse pas. Berserk m'a ensuite aidé à faire un premier tri. Un petit mot là-dessus ?*__  
(+Berserk) : j'avais prévu un petit programme en python... le plus dur c'était d'extraire les notes de chaque élève. après j'ai fait un filtre sur le cursus et les notes  
__*&gt; MSG #arpege : Toujours aussi laconique, mon petit Berserk, mais merci. Bref on s'est donc retrouvé avec une trentaine de candidats ayant tous une réelle culture informatique, et des aptitudes plus qu'honnêtes.*__  
(@ChAr) : Une trentaine ? Ca fait encore beaucoup de monde tout ça.  
__*&gt; MSG #arpege : Et oui, mais c'est pour ça que je suis là. Petit aparté, les résultats de l'extraction de Berserk sont dispos en xml. Je pourrais vous les envoyer ou bien les uploader sur symphonie, au choix.*__  
(@ChAr) : Pourquoi pas. On verra.  
__*&gt; MSG #arpege : En tout cas, j'ai épluché chaque dossier un par un. Je ne vous fais pas languir, j'ai retenu 3 candidats qui pourraient faire l'affaire. Mais j'ai déjà une nette préférence. Appelons-le le candidat Z. Je suis sûr que vous allez l'adorer.*__  
(+Berserk) : c'est lequel ?  
(@ChAr) : Tu nous mets l'eau à la bouche, là. Qu'est-ce qu'il a de particulier ce Z ?  
__*&gt; MSG #arpege : Tout d'abord, car c'est le plus important, sa moyenne en Administration des Bases de Données qui culmine à 64.7%, vu qu'ici on note sur 100. Pour comparaison, ça fait quasiment 13/20.*__  
(+Berserk) : t sérieux ? j'ai vu des moyennes en bases de données qui montaient à bcp bcp plus que ça... 13 c'est pas un peu lég' pour ce kon veut faire ?  
(@ChAr) : C'est vrai que ça parait peu. Mais j'imagine qu'Ada a une très bonne raison de pointer ce candidat.  
__*&gt; MSG #arpege : Toujours aussi malin, Charles, hein ? Il faut voir que cette moyenne a été récoltée sur deux trimestres. Je n'ai pas encore tous les détails, mais Z a séché le dernier, et a récolté autant de 0 en conséquence. Ce qui veut dire que sans ça, sa moyenne théorique serait plutôt de 97% soit environ 19.4/20, ce qui change les choses.*__  
(+Berserk) : mazette, la tête le mec ! mon programme se focalise juste sur la moyenne c'est pour ça que je l'avais pas remarqué ton type  
(@ChAr) : C'est vrai que c'est impressionnant. Mais je pense que ce n'est pas ça qui a le plus attiré Adam. Je me trompe ?  
__*&gt; MSG #arpege : Pas du tout, en effet. Alors d'après toi, c'est quoi ?*__  
(@ChAr) : Tu penses que ton Z est un rebelle, et que forcément, il ne pourra qu'adhérer à notre projet. Pour tout dire, je suis assez d'accord avec ça.  
__*&gt; MSG #arpege : Bingo !*__  
(@ChAr) : Alors, si tout le monde est d'accord, je pense qu'on peut partir sur cette candidature.  
__*&gt; MSG #arpege : Moi, tu as déjà mon avis.*__  
(+Berserk) : c'est ok pour moi  
(@ChAr) : Shadows, quand tu liras tout ça, préviens-moi si tu t'y opposes. Sinon, je pars du principe que tu es d'accord. Mes amis, le sous-projet Quintette peut passer en phase 2. Il faut maintenant recruter ce type.  
__*&gt; MSG #arpege : Content de voir que ma proposition est acceptée. Juste un gros détail à vous signaler.*__  
(+Berserk) : oui ?  
__*&gt; MSG #arpege : En fait, Z c'est pas un 'il', c'est une 'elle'. Et le 'elle' en question s'appelle Elise.*__  
(+Berserk) : oh zut fait chier ca va être la merde ça...  
(@ChAr) : C'est un gros détail, comme tu dis. Mais ne jouons pas les surpris. On voulait le meilleur en Bases de Données... et dans ce domaine, il y a plus de filles, et elles sont bien souvent meilleures que nous. Ca ne change rien à nos plans.  
__*&gt; MSG #arpege : +1 ChAr, on s'est fixé un objectif, et on doit pas se laisser arrêter par des considérations sexistes.*__  
(+Berserk) : d'accord d'accord mais au moins vous connaissez mon sentiment  
__*&gt; MSG #arpege : Je rajouterais que comme vous êtes des tanches manifestes avec les filles, il vaudrait mieux que je me charge de l'approcher.*__  
(+Berserk) : #!@-# adam arrête ton char tu es pas mieux loti  
(@ChAr) : Oh là, on se calme vous deux. Adam, il était prévu que je prenne contact avec le candidat, et on ne change rien au plan. Berserk, c'est une fille certes, mais si elle est intelligente (et c'est surement le cas) notre projet l'intéressera. Donc : on fait comme on a dit.  
(+Berserk) : ok  
__*&gt; MSG #arpege : Si tu le dis.*__  
(@ChAr) : Ada, tu m'envois son dossier. Messieurs, fin de la réunion. On se voit demain. Bonne nuit à tous. (Je suis crevé moi...)  
:Berserk QUIT : tcho les gars  
__*&gt; QUIT : J'ai sa photo, elle a l'air kawai*__  
  
Connection closed by foreign host.  
adam@odyseus:~$ __*exit*__  

{{< lien lnk="chapter/maestro/chapitre-2.md" />}}