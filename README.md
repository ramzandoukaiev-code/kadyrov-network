# Réseau Kadyrov — Cartographie OSINT

Cartographie de sources ouvertes des réseaux familiaux, sécuritaires, économiques et d'influence de Ramzan Kadyrov, avec une attention particulière à la dimension Moyen-Orient (Émirats arabes unis) et au volet européen (élimination d'opposants).

Construite exclusivement à partir d'enquêtes journalistiques publiques.

## Deux vues complémentaires

L'outil propose deux modes consultables, basculables d'un clic :

- **Carte** : les entités sont positionnées sur leurs coordonnées géographiques réelles (Grozny, Dubaï, Abou Dhabi, Hanovre, Vienne), avec les liens tracés entre elles. Fond cartographique vectoriel sombre, sans dépendance à un serveur de tuiles externe.
- **Réseau** : un graphe relationnel radial centré sur Ramzan Kadyrov.

## Fonctionnalités

- **Recherche** par nom, active dans les deux vues (met l'entité en évidence et estompe le reste).
- **Filtres par catégorie** : clan/famille, sécurité, business/actifs, politique, international.
- **Filtres par niveau de certitude** : Avéré, Probable, Allégué (double encodage : style de trait + badge).
- **Fiche détaillée** au clic sur une entité : type, catégorie, localisation, et liste complète des relations avec sources cliquables et niveau de certitude.

## Contenu du dépôt

- `index.html` — l'application (à ouvrir dans un navigateur).
- `region.geojson` — frontières des pays de la zone (Natural Earth, domaine public).
- `leaflet.js` / `leaflet.css` / `images/` — librairie cartographique (embarquée localement).
- `vis-network.min.js` — librairie de graphe (embarquée localement).
- `matrice_relations.csv` — la matrice de relations sourcée (cœur des données).

## Méthode

Chaque relation est qualifiée par un niveau de certitude inspiré de la logique de cotation des sources (Amirauté / OTAN) :

- **Avéré** : établi par document public ou registre officiel.
- **Probable** : rapporté par plusieurs enquêtes concordantes.
- **Allégué** : présomption rapportée, non établie comme fait.

Les liens « allégués » sont des présomptions, non des faits établis. Les sources d'État sont traitées comme nécessitant corroboration.

## Sources principales

IStories / OCCRP, CORRECTIV, OC Media, RUSI, Novaya Gazeta, Ukrainska Pravda, Der Spiegel, Meduza, Dubai Unlocked.

---

*Outil pédagogique et analytique. Aucune donnée privée, confidentielle ou non sourcée. Construit dans le cadre d'un portfolio en conformité / criminalité financière.*
