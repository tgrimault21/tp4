# Answers

Nom : Grimault
Prénom : Théophile
NB : 

# 1.
A quoi sert l'A/B testing ? 
Cela permet de voir ce qu'une montée de niveau aura comme impact sur les utilisateurs.

Comment appliquer de l'A/B testing grâce à Istio ?
Istio permet de créer 2 routes pour deux versions différentes, et d'appliquer un poids à ces routes, en sorte que la somme des deux poids fasse 100.

# 2.
Comment simuler un problème de timeout avec Istio ?
Avec du fault injection.

Comment le résoudre ?
Il faut faire en sorte que l'application soit plus performante, plus rapide. Pour ça, on peut changer les timeout dans les réglages d'une appli.

# 3.
Qu'est-ce que le canary release ?
C'est une technique qui permet de filtrer les utilisateurs à chaque release d'une nouvelle version, pour pouvoir la faire tester sans qu'elle soit trop chargée, avant qu'elle soit totalement validée.

En quoi est-ce utile ?
Voir réponse au dessus.


Comment l'implémenter dans Istio ?
La même chose que pour A/B testing

# 4.

# 5.
Qu'est-ce qu'un Circuit Breaker ?
C'est un outil qui permet de rediriger des données lorsqu'une application est défaillante, pour limiter les pertes.

Comment l'implémenter dans un contexte Kubernetes ?
Comme si on ajoutait des règles dans la configuration de Kubernetes.

# 6.
Pourquoi avoir besoin de mirrorer le traffic vers un autre composant ?
Cela permet de modifier de manière sûre la production.

# 7.
Pourquoi bloquer le traffic vers un service ?
Si d'autres processus dépendent d'un service, ils seront également ralentis, donc mieux vaut bloquer le traffic vers ce service.

Comment l'implémenter simplement avec Istio ?

# 8.
Quel est la problématique de tracing distribué ?
Il faut comprendre comment fonctionne l'application et comment résoudre les problèmes.

Quel est la spécification du tracing distribué et son implémentation dans Istio ?


# 9.
Comment s'appelle l'outil de récupération des métrics ?
Promotheus

# 10.

# 11.
Comment s'appelle l'outil de visualisation des métrics ?
Grafana

# 12.
A quoi sert un servicegraph ?

Quel serait l'utilité dans le quotidien d'un ops ?
