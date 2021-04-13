# Rossmann_story_telling
L'ensemble de données que nous étudions comprend les ventes quotidiennes pour 1115 magasins Rossmann différents en Allemagne. l'objectif sera d'analyser et proposer un storytelling de l'activité économique de ces 1115 magasins

Nous disposons de 3 fichiers: train.csv - contient les données de ventes test.csv - contient les données de ventes Rossman_store.csv - contient les informations sur chaque magasin

# Les variables d'entrée

Magasin - un identifiant unique pour chaque magasin

Ventes - le chiffre d'affaires par jour 

Clients - le nombre de clients un jour donné

Ouvert - un indicateur pour savoir si le magasin était ouvert: 0 = fermé, 1 = ouvert

StateHoliday - indique un jour férié. Normalement, tous les magasins, à quelques exceptions près, sont fermés les jours fériés. Notez que toutes les écoles sont fermées les jours fériés et les week-ends. a = jour férié, b = vacances de Pâques, c = Noël, 0 = aucun
Vacances scolaires - indique si le (magasin, date) a été affecté par la fermeture des écoles publiques

StoreType  - fait la différence entre 4 modèles de magasins différents: a, b, c, d

Assortiment - décrit un niveau d'assortiment: a = basique, b = extra, c = étendu

CompetitionDistance - distance en mètres du magasin concurrent le plus proche

CompetitionOpenSince [Mois / année] - donne l'année et le mois approximatifs de l'ouverture du concurrent le plus proche

Promo - indique si un magasin propose une promotion ce jour-là

Promo2 - Promo2 est une promotion continue et consécutive pour certains magasins: 0 = le magasin ne participe pas, 1 = le magasin participe

Promo2Since [année / semaine] - décrit l'année et la semaine civile auxquelles le magasin a commencé à participer à Promo2

PromoInterval - décrit les intervalles consécutifs de démarrage de Promo2, en nommant les mois de redémarrage de la promotion. Par exemple, "février, mai, août, novembre" signifie que chaque cycle commence en février, mai, août et novembre d'une année donnée pour ce magasin.

# Plan

1- Dataprocessing

2- storytelling_1: Exploration du jeu de données de comportement d'achat

3- story telling_2: Analyse approfondie des habitudes d'achats

