# realistic-flux-gitops-workflow
A demo about a quite realistic workflow using Flux in a Kubernetes GitOps workflow

## Abstract
T’en as assez des talks qui déploient des _hello-world_ pour démontrer la pertinence de l’outil _younameit_.  
Ça tombe bien : ce qui nous intéresse, c’est plutôt d’essayer une mise en situation _DevSecOps_ un peu réaliste. On va donc construire pas à pas un scénario d’entreprise avec une _dev team_, qui déploie / _update_ / _rollback_ des _WebApps_ Pokémon sur `Kubernetes` via des _charts_ `Helm`.  
Une seconde _dev team_ utilisera `Kustomize`, pour le même usage.  
Et côté _Ops_, on va aussi se préoccuper des enjeux de sécurité de la plateforme : ségrégations des droits des équipes, des flux réseau des _WebApps_, _patch management_ transparent sur la _stack_ technique, métrologie, contrôle des activités sur le _cluster_.  
On va voir comment ces équipes collaborent entre elles au quotidien dans un _workflow GitOps_ qui s’appuie sur `Kubernetes`, `FluxCD`, `Azure DevOps`, et plein d’autres choses encore…

