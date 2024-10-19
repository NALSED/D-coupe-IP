

* ### **Découpage asymétrique :**

|       | Adresse réseaux | Adresse début de plage | Adresse de fin de plage	| Adresse de broadcast |
| ------    | ------    | ------    | ------    | ------    |
|Pôle informatique  |  172.16.1.0/26 	|172.16.1.1     |172.16.1.62    |172.16.1.63 |
|Pôle Administratif |172.16.1.64/27     |172.16.1.65    |172.16.1.94    |172.16.1.95|
|Pôle Technicien    |172.16.1.96/28	    |172.16.1.97    |172.16.1.126   |172.16.1.127|
|Pôle Développement |172.16.1.128/28    |  172.16.1.129 |172.16.1.142   |172.16.1.143|

* ##### Le Pôle informatique (6 bureaux, environ 50 équipements au total) 	2^6=>**64** = 62 dispos CIDR 32-6=26
* ##### Le Pôle Administratif (4 bureaux, environ 20 équipements au total) 	2^5=>**32** = 30 dispos CIDR 32-5=27
* ##### Le Pôle Technicien (4 bureaux, environ 15 équipements au total) 	2^5=>**32** = 30 dispos CIDR 32-5=27
* ##### Le Pôle développement (6 bureaux, environ 12 équipements au total) 	2^4=>**16** = 14 dispos CIDR 32-4=28

* ### **Découpage symétrique :**

|       | Adresse réseaux | Adresse début de plage | Adresse de fin de plage	| Adresse de broadcast |
| ------    | ------    | ------    | ------    | ------    |
|Pôle informatique  |  172.16.1.0/26	|172.16.1.1    |172.16.1.62    |172.16.1.63 |
|Pôle Administratif |172.16.1.64/26     |172.16.1.65    |172.16.1.126    |172.16.1.127|
|Pôle Technicien    |172.16.1.128/26	|172.16.1.129    |172.16.1.190   |172.16.1.191|
|Pôle Développement |172.16.1.192/26    |  172.16.1.193 |172.16.1.254   |172.16.1.255|

* ##### Le Pôle informatique (6 bureaux, environ 50 équipements au total) 	2^6=>**64** = 62 dispos CIDR 32-6=26 on utilisera 4 fois se résultat.
* ##### Le Pôle Administratif (4 bureaux, environ 20 équipements au total) 	
* ##### Le Pôle Technicien (4 bureaux, environ 15 équipements au total) 	
* ##### Le Pôle développement (6 bureaux, environ 12 équipements au total) 




