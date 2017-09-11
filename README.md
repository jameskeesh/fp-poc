# Widevine
## Plan Action
1. Lire la spec
2. Relire la spec
3. Faire une recherche Google : Widevine Proxy
4. Lire le résultat de la page 1 et 2 de la recherche Google
5. Faire un workflow complet (UX)  
6. Récupérer les certificats/credentiels et commencer une implémentation à partir de code source example
  

## Questions
0. Pourquoi Python ?
1. Comment se fait l'authentification du client par le proxy ?
2. Est ce que le PARSE_ONLY doit être implémenté ? (à priori oui)
3. Quelles sont les business rules au niveau du proxy ? Sous quelle forme ?
4. Ou sera déployé le proxy ? sur le routeur ? dans le cloud ?  
5. Volumétrie en nb de demandes de licences / s, h ou jours  
6. temps de réponse du proxy. Est ce une demande synchrone ou asynchrone de la part du client ?  

## Divers
> Rechercher si il y a beaucoup de devs fait avec cette techno  
rechercher les bugs  
Rechercher des implémentations du proxy déjà réalisées  
- dash.js https://github.com/Dash-Industry-Forum/dash.js  
- shaka-khan  
- Etudier Framework MSL https://github.com/Netflix/msl/wiki/  

## Réferences
https://storage.googleapis.com/wvdocs/Widevine_DRM_Proxy_Integration.pdf
https://support.google.com/widevine/answer/6048495?hl=en
https://www.wowza.com/community/questions/6614/recommend-a-widevine-license-server.html
https://www.wowza.com/docs/how-to-secure-mpeg-dash-streaming-using-common-encryption-cenc
