---
marp: true
size: 16:9
paginate: true
footer: "Statistics Canada | Statistique Canada"
header: "26 août 2025"
theme: default
style: |
  /* Statistics Canada Marp Theme */

  /* Import Inter font from Google Fonts */
  @import url("https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap");

  :root {
      /* Color variables */
      --primary-color: #26374a;
      /* Statistics Canada blue */
      --secondary-color: #ea5936;
      /* Statistics Canada orange */
      --accent-color: #3e6ca7;
      --light-gray: #f5f5f5;
      --dark-gray: #333;
      --text-color: #333;
      --background-color: #fff;

      /* Font variables */
      --main-font: "Inter", sans-serif;
      --code-font: "Fira Code", "Consolas", monospace;

      /* Size variables */
      --base-font-size: 16px;
      --h1-size: 2em;
      --h2-size: 1.5em;
      --h3-size: 1.2em;
      --p-size: 0.9em;
      --code-size: 0.85em;

      /* Spacing variables */
      --section-padding: 1.5rem;
      --element-margin: 0.75rem;
  }

  /* Apply the font to all elements */
  * {
      font-family: var(--main-font);
  }

  /* Top alignment for content */
  section {
      display: flex;
      flex-direction: column;
      justify-content: flex-start;
      padding-top: 4rem;
  }

  /* Header styles */
  h1 {
      font-size: var(--h1-size);
      color: var(--primary-color);
      font-weight: 600;
      margin-bottom: var(--element-margin);
      margin-top: 0;
  }

  h2 {
      font-size: var(--h2-size);
      font-weight: 500;
      margin-bottom: var(--element-margin);
      margin-top: 0;
  }

  h3 {
      font-size: var(--h3-size);
      font-weight: 500;
      margin-bottom: var(--element-margin);
      margin-top: 0;
  }

  h6 {
      margin-top: 0.1rem;
  }

  /* Paragraph styles */
  p {
      font-size: var(--p-size);
      color: var(--text-color);
      line-height: 1.2;
      margin-bottom: var(--element-margin);
  }

  /* Code block styles */
  pre>code {
      font-family: var(--code-font);
      font-size: var(--code-size);
      background-color: var(--light-gray);
      padding: 1rem;
      border-radius: 4px;
      line-height: 1.4;
  }

  /* Blockquote styles */
  blockquote {
      border-left: 4px solid var(--secondary-color);
      margin-bottom: 1.1rem;
      font-size: 0.8rem;
      line-height: 1.8;
      margin-left: 0;
      color: var(--dark-gray);
      font-style: italic;
      font-weight: 700;
  }

  /* List styles */
  ul,
  ol {
      font-size: var(--p-size);
      margin-bottom: var(--element-margin);
  }

  li {
      margin-bottom: 0.5rem;
  }

  /* Footer and header customization */
  footer,
  header {
      font-size: 0.8em;
      color: var(--primary-color);
      opacity: 0.8;
  }

  /* Background image adjustments */
  img[bg] {
      opacity: 0.15;
  }

  /* Link styling */
  a {
      color: var(--accent-color);
      text-decoration: none;
  }

  a:hover {
      text-decoration: underline;
  }

  /* Custom classes for special elements */
  .highlight {
      background-color: rgba(234, 89, 54, 0.1);
      padding: 0.2rem 0.4rem;
      border-radius: 3px;
      font-weight: 500;
  }

  .callout {
      border-left: 4px solid var(--secondary-color);
      background-color: var(--light-gray);
      padding: 1rem;
      margin: 1rem 0;
  }

  /* Center the lead/title slide */
  .lead {
      justify-content: center;
      text-align: center;
  }
---

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
![bg left:33%](./canada-1.png)

---

<!-- Qui nous sommes -->
## L'équipe de La Zone

**Été 2025**

![bg left:33%](./zone-0.png)

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

![bg left:33%](./zone-1.png)

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

![bg left:33%](./zone-1.png)

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

![bg left:33%](./zone-3.png)

### Et la langue ? Aucune barrière.

- Python, R, Julia, SAS sont tous pris en charge  
- Migrez à votre rythme, dans votre langage  
- **La seule plateforme à StatCan où  
SAS et Python/R coexistent**

![](./languages.png)

---

<!-- Inclusivité et coexistence organisationnelle -->
## Bienvenue à tous

![bg left:33%](./zone-3.png)

### Et l'organisation ? Aucune barrière.

- Conçue comme solution open source : clonable, partageable, fédérable  
- Nous l'avons déjà fait une fois : nous pouvons le refaire  
- Prête à soutenir d'autres équipes, ministères et ordres de gouvernement

---

<!-- Pourquoi La Zone a-t-elle été créée ? -->
## Pourquoi La Zone a-t-elle été créée ?

![bg left:33%](./zone-5.png)

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

![bg left:33%](./zone-5.png)

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

![bg left:33%](./zone-8.png)

- Accélération **MKL** pour un calcul numérique plus rapide  
- **Tesseract OCR** pour extraire du texte de documents scannés  
- Nettoyeurs de volumes et d'espaces de noms pour un nettoyage automatique des ressources  
- **CronJobs** pour planifier notre infrastructure prête pour les pipelines  
- **Probe de préparation** : plus d'erreurs de chargement  
- Images Docker **optimisées** pour des temps de chargement plus rapides

---

<!-- Des CronJobs aux pipelines -->
## Des CronJobs aux pipelines

![bg left:33%](./zone-8.png)

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

![bg left:33%](./zone-9.png)

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

![bg left:33%](./zone-9.png)

**Kubeflow a été conçu pour les pipelines.** Il met la puissance de Kubernetes à la portée des scientifiques des données via une interface intuitive.

- L’EAA disposait de **Kubeflow Pipelines** et **Argo Workflows**  
- Nous pouvons les réactiver, sans tout réinventer, pour des flux complets : versionnés, reproductibles, surveillés

<blockquote>
Nous ne repartons pas de zéro. Nous rétablissons ce qui fonctionne, en le rendant sécurisé, évolutif et normalisé.
</blockquote>

---

<!-- Problèmes restants -->
## Des défis persistent

![bg left:33%](./zone-9.png)

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

![bg left:33%](./zone-10.png)

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

![bg left:33%](./zone-10.png)

Vous êtes invités à :

- Accéder à la plateforme : https://zone.statcan.ca  
- Participer aux formations et ateliers  
- Aider à façonner l'avenir de la science des données à StatCan  
- Héberger la prochaine Zone dans votre direction

<blockquote>
La Zone est un mouvement vers l'ouverture, la souveraineté  
et les capacités partagées.
</blockquote>
