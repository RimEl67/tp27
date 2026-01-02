# TP 27 – Test de charge & Observabilité  
# Par: Rim EL ABBASSI


## Présentation du TP

Ce TP a pour objectif d’évaluer le comportement d’une application microservices face à une **charge concurrente élevée**, tout en garantissant :

- la **cohérence des données** (stock jamais négatif),
- la **résilience aux pannes** via Resilience4j,
- la **visibilité des métriques** grâce à Spring Boot Actuator.

Le cas d’étude repose sur un **service de gestion de livres**, permettant l’emprunt concurrent d’un stock limité.

---

## Ce que ce TP permet de vérifier

- Gestion correcte de la **concurrence multi-instances**
- Efficacité du **verrouillage en base de données**
- Résilience face à un service distant indisponible
- Fonctionnement du **fallback**
- Exposition et analyse des **métriques Actuator**
- Comportement du **Circuit Breaker** et du **Retry**

<img width="1050" height="543" alt="image" src="https://github.com/user-attachments/assets/557a2033-0044-4e0a-9b29-921231fdc9e7" />

<img width="1049" height="537" alt="image" src="https://github.com/user-attachments/assets/5eadd790-f1ad-4324-9673-c2551502efd1" />

<img width="967" height="497" alt="image" src="https://github.com/user-attachments/assets/35341cea-14d0-424a-af60-356583e93c4a" />

