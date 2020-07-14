| Variable   | Signification   | Type     | longeur     | Remarque |
| --- | --- |--- | --- |--- |
| id_u | Identifiant  de l'université | N   |  |
| nom_u | Nom de l'université | A | 30|  |
| logo_u |  logo de l'université | Image | Pixel |  |
| contact_u |  Contact de l'université | AN   | 20 |  |
| user_nom_u |  Nom de l'admin de l'université | A | 30 |  |
| user_prenom_u |  Prenom de l'admin de l'université | AN   | 40 |  |
| user_email_u | Addresse mail de l'admin de l'université | AN   | 100 |  |
| user_mdp_u | Mot de passe de l'admin de l'université | AN  | 40 |  |
| user_photo_u | Photo de l'admin de l'université | Image | Pixel |  |
| date_add_u | date de creation  de l'université | Date   | 15 |  |
| id_ufr | Identifiant  UFR | N   |  |  |
| nom_ufr | le nom de l'UFR | A | 30 |  |
| libele_ufr | le libele de l'UFR | AN |  | Ce libélé servira également d'identifiant dans ce système Au format : nom_u - nom_ufr  |
| date_add_ufr | date de creation  de l'UFR | Date   | 15 |  |
| id_c | Identifiant  Cycle | N   |  |  |
| nom_c | le nom du Cycle | A | 30 |  |
| date_add_c | date de creation  du Cycle | Date   | 15 |  |
| id_f | Identifiant  Filière | N   |  |  |
| nom_f | le nom de la Filière | A | 30 |  |
| libele_f | le libele de la Filière | AN |  | Ce libélé servira également d'identifiant dans ce système Au format : libele_ufr - nom_f  |
| photo_f | Photo de la Filière  | Image | Pixel |  |
| date_add_f | date de creation  de la Filière | Date   | 15 |  |
| id_niv | Identifiant  Niveau | N   |  |  |
| nom_niv | le nom du Niveau | AN | 7 |  |
| date_add_niv | date de creation  du Niveau | Date   | 15 |  |
| id_cls | Identifiant  Classe | N   |  |  |
| libele_cls | le libele de la Classe | AN |  | Ce libélé servira également d'identifiant dans ce système Au format : libele_f - nom_niv  |
| date_add_cls | date de creation  de la Classe | Date   | 15 |  |
| id_ue | Identifiant  Ue | N   |  |  |
| nom_ue | le nom de l' Ue | A | 30 |  |
| libele_ue | le libele de l' Ue | AN |  | Ce libélé servira également d'identifiant dans ce système Au format : libele_cls - nom_ue  |
| photo_ue | Photo de l' Ue  | Image | Pixel |  |
| date_add_ue | date de creation  de l' Ue| Date   | 15 |  |
| id_ucue | Identifiant  UCUE (cours) | N   |  |  |
| nom_ucue | nom UCUE (cours) | A | 30 |  |
| libele_ucue | libele UCUE (cours) | AN |  | Ce libélé servira également d'identifiant dans ce système Au format : libele_ue - nom_ucue  |
| photo_ucue | Photo UCUE (cours)  | Image | Pixel |  |
| video_intro_ucue | Video UCUE (cours)  | Video | Pixel |  |
| description_ucue | description UCUE (cours) | texte |  | |
| prix_ucue | prix UCUE(cours)  | N   |  |  |
| date_add_ucue | date de creation  UCUE(cours) | Date   | 15 |  |
| id_l | Identifiant  Lecon  | N   |  |  |
| titre_l | titre Lecon  | AN | 40 |  |
| description_l | Lecon  | texte |  | |
| date_add_l | date de creation  Lecon | Date   | 15 |  |
| id_tr | Identifiant  Type de Ressource  | N   |  |  |
| titre_tr | titre Type de Ressource  | AN | 40 |  |
| date_add_tr | date de creation Type de Ressource | Date   | 15 |  |
| id_rs | Identifiant   Ressource de la lecon | N   |  |  |
| titre_rs | titre de la Ressource de la lecon | AN | 40 |  |
| lien_rs | lien de la Ressource de la lecon | AN |  |  |
| date_add_rs | date de creation de la Ressource de la lecon | Date   | 15 |  |
| id_ins | Identifiant  de l'Instructeur  | N   |  |  |
| user_nom__ins | nom de l'Instructeur | A | 40 |  |
| user_prenom__ins | prenom de l'Instructeur | A | 40 |  |
| user_email__ins | email de l'Instructeur | A | 40 |  |
| user_mdp__ins | mot de passe de l'Instructeur | AN | 40 |  |
| user_photo_ins | Photo de de l'Instructeur| Image | Pixel |  |
| user_diplome_ins | diplome de l'Instructeur | A | 100 |  |
| user_contact_ins | contact de l'Instructeur | AN | 20 |  |
| user_addresse_ins | addresse de l'Instructeur| AN | 100 | |
| date_add_ins | date de creation de l'Instructeur | Date   | 15 |  |
| id_etud | Identifiant  de l'Etudiant  | N   |  |  |
| nom_etud | nom de l'Etudiant | A | 40 |  |
| prenom_etud | prenom de l'Etudiant | A | 40 |  |
| email_etud | email de l'Etudiant | A | 40 |  |
| mdp_etud | mot de passe de l'Etudiant | AN | 40 |  |
| photo_etud | Photo de de l'Etudiant| Image | Pixel |  |
| statpro_etud | statut professionel de l'Etudiant | A | 100 |  |
| contact_etud | contact de l'Etudiant | AN | 20 |  |
| addresse_etud | addresse de l'Etudiant| AN | 100 | |
| birthday_etud | date  de naissance de l'Etudiant | Date | 15 |  |
| certificat_etud | certificat de scolarité de l'Etudiant | AN | 20 |  |
| addresse_etud | addresse de l'Etudiant| AN | 100 | |
| date_add_etud | date de creation de l'Etudiant | Date  | 15 |  |
| id_ac | Identifiant  de l'Année AcademiQue  | N   |  |  |
| encour_ac | statut de l'Année AcademiQue Qui est en cour | B |  |  |
| passer_ac | statut de l'Année AcademiQue Qui vient de finir| B |  |  |
| date_add_ac | date de creation de l'Année AcademiQue | Date  | 15 |  |
| id_al | Identifiant  de l'almuni  | N   |  |  |
| fonction_al | la fonction de l'almuni  | A |  50| dans le cas ou il est en fonction  |
| nom_entreprise_al | le nom de l'entreprise ou travaille l'almuni  | AN |  50 |dans le cas ou il est en fonction  |
| date_add_al | date de creation de l'Année AcademiQue | Date  | 15 |  |
| id_di | Identifiant  de la Demande d'Inscription  | N   |  |  |
| nom_di | nom de l'apprenant Qui fait la  Demande d'Inscription  | A |  10|  |
| prenom_di | prenom de l'apprenant Qui fait la  Demande d'Inscription  | A |  50 |  |
| prenom_di | prenom de l'apprenant Qui fait la  Demande d'Inscription  | A |  50 |  |
| email_di | email de l'apprenant Qui fait la  Demande d'Inscription  | AN |  100 |  |
| contact_di | contact de l'apprenant Qui fait la  Demande d'Inscription  | AN |  20 |  |
| valider_di | statut de la demande de l'apprenant Qui fait la  Demande d'Inscription | B |  |  |
| refuser_di | statut de la demande de  l'apprenant Qui fait la  Demande d'Inscription| B |  |  |
| date_add_di | date de creation de l'Année AcademiQue | Date  | 15 |  |
