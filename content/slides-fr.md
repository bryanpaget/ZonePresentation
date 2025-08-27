<!-- Diapositive de titre -->
<!-- _class: lead -->
# La Zone
### Une plateforme moderne de science des données

#### Pour Statistique Canada

<br>
<br>
<br>
<br>

###### *Présenté par l'équipe de La Zone :heart:*
![bg left:33%](./img/canada-1.png)

---

<!-- Qui nous sommes -->
## L'équipe de La Zone

**Été 2025**

![bg left:33%](./img/zone-0.png)

<blockquote>
Avec Anray Liu et Justin Zhang !

Stagiaires développeurs de l'Université d'Ottawa et de Carleton
</blockquote>

###### Développeurs (TI-02) :
- Wendy Gaultier, Mathis Marcotte, Jose Matsuda, Souheil Yazji

###### Chef d'équipe (par intérim, TI-03) :
- Bryan Paget

---

<!-- Notre histoire -->
## Notre histoire

**Une plateforme, deux zones**

![bg left:33%](./img/zone-1.png)

- L’Espace d’analytique avancée (EAA)
  était la première Zone
- La Zone en est la contrepartie en zone protégée B
- Bâtie sur la même base :
  **Kubeflow sur Kubernetes**

<blockquote>
Même cœur. Mêmes capacités.
<br>
Sécurité accrue.
</blockquote>

---

<!-- Qu'est-ce que La Zone ? -->
## Qu'est-ce que La Zone ?

![bg left:33%](./img/zone-1.png)

La Zone est une plateforme de science des données basée sur **Kubeflow**, conçue pour orchestrer des notebooks, des tâches et des flux de travail en apprentissage machine.

Fonctionnalités :

- **JupyterLab** prenant en charge Python, R, SAS, Julia
- **Kubeflow** pour une infrastructure évolutive en science des données et automatisation

<blockquote>
La Zone fonctionne sur Azure AKS,
<br>
mais peut s'exécuter sur n'importe quel cluster Kubernetes.
</blockquote>

---

<!-- Inclusivité et coexistence SAS -->
## Bienvenue à tous

![bg left:33%](./img/zone-3.png)

### Et la langue ? Aucune barrière.

- Python, R, Julia, SAS sont tous pris en charge
- Migrez à votre rythme, dans votre langage
- **La seule plateforme à StatCan où
SAS et Python/R coexistent**

![](./img/languages.png)

---

<!-- Inclusivité et coexistence organisationnelle -->
## Bienvenue à tous

![bg left:33%](./img/zone-3.png)

### Et l'organisation ? Aucune barrière.

- Conçue comme solution open source : clonable, partageable, fédérable
- Nous l'avons déjà fait une fois : nous pouvons le refaire
- Prête à soutenir d'autres équipes, ministères et ordres de gouvernement

---

<!-- Pourquoi La Zone a-t-elle été créée ? -->
## Pourquoi La Zone a-t-elle été créée ?

![bg left:33%](./img/zone-5.png)

Pour offrir une plateforme de données sécurisée, moderne et autonome.

- Fournir un environnement conforme à la **sécurité protégée B**
- Réduire la dépendance aux outils propriétaires
- Réduction des coûts à long terme grâce à une infrastructure ouverte et réutilisable

<blockquote>
Il s'agit de souveraineté, de durabilité
et d'autonomie.
</blockquote>

---

<!-- Ce que nous avons construit -->
## Ce que nous avons construit

![bg left:33%](./img/zone-5.png)

- Plus de 2 200 utilisateurs intégrés
- Plus de 130 sessions de notebook par jour
- CronJobs alimentant des flux de production réels
- Une plateforme stable et éprouvée utilisée dans plusieurs divisions

<br>

<blockquote>
Ce n'est pas un prototype.
C'est une plateforme de production.
</blockquote>

---

<!-- Été 2025 -->
## Été 2025

![bg left:33%](./img/zone-8.png)

- Accélération **MKL** pour un calcul numérique plus rapide
- **Tesseract OCR** pour extraire du texte de documents scannés
- Nettoyeurs de volumes et d'espaces de noms pour un nettoyage automatique des ressources
- **CronJobs** pour planifier notre infrastructure prête pour les pipelines
- **Probe de préparation** : plus d'erreurs de chargement
- Images Docker **optimisées** pour des temps de chargement plus rapides

---

<!-- Des CronJobs aux pipelines -->
## Des CronJobs aux pipelines

![bg left:33%](./img/zone-8.png)

**Aujourd'hui :** Les CronJobs s'exécutent de façon isolée.

**Demain :** Des flux de travail connectés et observables grâce à **Argo Workflows** et **Kubeflow Pipelines**.

- Argo Workflows orchestre des séquences complexes de tâches sur Kubernetes
- Kubeflow Pipelines permet des flux ML complets avec interface, mise en cache, versionnement
- Journalisation complète, logique de réessai, gestion des erreurs, déclencheurs

<blockquote>
L'automatisation, en évolution.
</blockquote>

---

<!-- Kubernetes est conçu pour l'orchestration -->
## Kubernetes est conçu pour l'orchestration

![bg left:33%](./img/zone-9.png)

En son cœur, **Kubernetes est conçu pour orchestrer les charges de travail** : mise à l'échelle, planification et gestion des conteneurs sur des clusters.

- Alimente les applications cloud-native modernes
- Gère les flux complexes de manière fiable
- Exécute déjà les notebooks et tâches de La Zone

<blockquote>
L'orchestration n'est pas l'avenir.
<br>
Elle est déjà là, sous le capot.
</blockquote>

---

<!-- Kubeflow amène l'orchestration aux scientifiques des données -->
## Kubeflow amène l'orchestration aux scientifiques des données

![bg left:33%](./img/zone-9.png)

**Kubeflow a été conçu pour les pipelines.** Il met la puissance de Kubernetes à la portée des scientifiques des données via une interface intuitive.

- L’EAA disposait de **Kubeflow Pipelines** et **Argo Workflows**
- Nous pouvons les réactiver, sans tout réinventer, pour des flux complets : versionnés, reproductibles, surveillés

<blockquote>
Nous ne repartons pas de zéro. Nous rétablissons ce qui fonctionne, en le rendant sécurisé, évolutif et normalisé.
</blockquote>

---

<!-- Problèmes restants -->
## Des défis persistent

![bg left:33%](./img/zone-9.png)

- Connexions aux bases de données (WIFs)
- Performances des anciens serveurs de fichiers (migration des données)
- Concepts Linux et Kubernetes (formation)
- Gestion des secrets (Keycloak)
- Dépôt d’extension VS Code (à l’échelle organisationnelle)

<blockquote>
Nous travaillons à les résoudre, grâce à vos commentaires.
</blockquote>

---

<!-- Avenir fédéré -->
## Un avenir fédéré

![bg left:33%](./img/zone-10.png)

La Zone est open source et conçue pour s'agrandir. Elle peut être déployée par :

- D'autres équipes de StatCan
- Des ministères fédéraux
- Des gouvernements provinciaux et municipaux

<blockquote>
Même base. Même sécurité.
<br>
Déployée là où vous en avez besoin.
</blockquote>

---

<!-- Appel à l'action -->
## Entrez dans La Zone

![bg left:33%](./img/zone-10.png)

Vous êtes invités à :

- Accéder à la plateforme : https://zone.statcan.ca
- Participer aux formations et ateliers
- Aider à façonner l'avenir de la science des données à StatCan
- Héberger la prochaine Zone dans votre direction

<blockquote>
La Zone est un mouvement vers l'ouverture, la souveraineté
et les capacités partagées.
</blockquote>
