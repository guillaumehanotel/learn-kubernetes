# TD Kubernetes - Hello World

## Guillaume HANOTEL

## Consignes :

• Créez un namespace avec un fichier de conf, assignez 
lui des quotas 

• Mettre en place le dockercloud/hello-world sur le 
namespace, sur un nom de domaine ou un chemin 

• Mettre en place un LoadBalancer IP sur votre hébergeur 
Cloud qui redirige vers toutes vos machines. En utilisant 
cette IP vous devriez pouvoir afficher le hello-world 

• Éteindre une des machines, et vérifier que tout 
fonctionne toujours.

## Solution :

Il Faut : 
- Un namespace
- Un Pod
- Des quotas
- Un Service
- Un Deployment

Appliquer la conf :

kubectl --insecure-skip-tls-verify run -f ./hello-world# learn-kubernetes
