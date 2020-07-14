| Variable   | Signification   | Type     | longeur     | Remarque |
| --- | --- |--- | --- |--- |
| id_u | Identifiant  de l'université | N   |  |
| nom_u | Nom de l'université | A | 30|  |
| logo_u |  logo de l'université | Image | Pixel |  |
| contact_u |  Contact de l'université | AN   | 20 |  |
| user_nom_u |  Nom de l'admin de l'université | A | 30 |  |
| user_prenom_u |  Prenom de l'admin de l'université | AN   | 40 |  |
| user_email_u | Addresse mail de l'admin de l'université | AN   | 40 |  |
| user_mdp_u | Mot de passe de l'admin de l'université | AN  | 40 |  |
| user_photo_u | Photo de l'admin de l'université | Image | Pixel |  |
| id_ufr | Identifiant  UFR | N   |  |  |
| nom_ufr | le nom de l'UFR | A | 30 |  |
| libele_ufr | le libele de l'UFR | AN |  | Ce libélé servira également d'identifiant dans ce système Au format : nom_u - nom_ufr  |
| id_c | Identifiant  Cycle | N   |  |  |
| nom_c | le nom du Cycle | A | 30 |  |
| id_f | Identifiant  Filière | N   |  |  |
| nom_f | le nom de la Filière | A | 30 |  |
| libele_f | le libele de la Filière | AN |  | Ce libélé servira également d'identifiant dans ce système Au format : libele_ufr - nom_f  |
| photo_f | Photo de la Filière  | Image | Pixel |  |
| id_niv | Identifiant  Niveau | N   |  |  |
| nom_niv | le nom du Niveau | AN | 7 |  |
| id_cls | Identifiant  Classe | N   |  |  |
| libele_cls | le libele de la Filière | AN |  | Ce libélé servira également d'identifiant dans ce système Au format : libele_f - nom_niv  |
| id_ue | Identifiant  Ue | N   |  |  |
| nom_ue | le nom de l' Ue | A | 30 |  |
| libele_ue | le libele de l' Ue | AN |  | Ce libélé servira également d'identifiant dans ce système Au format : libele_cls - nom_ue  |
| photo_ue | Photo de l' Ue  | Image | Pixel |  |
