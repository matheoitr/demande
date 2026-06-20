Excellente idée : **Death Note est un terrain en or pour un oral de maths**, parce que toute l'enquête de L est littéralement du raisonnement probabiliste. Voici un sujet taillé pour le 20/20.

---

## 🎯 La problématique recommandée

> **« Dans quelle mesure les probabilités conditionnelles permettent-elles de raisonner efficacement dans l'incertain ? L'exemple de l'enquête de L contre Kira dans Death Note. »**

**Variantes si tu veux plus percutant :**
- « Peut-on démasquer un criminel insaisissable grâce aux mathématiques ? Le raisonnement bayésien de L dans *Death Note*. »
- « Comment le théorème de Bayes transforme-t-il des indices en certitudes ? »

**Pourquoi c'est un sujet 20/20** (selon tes propres critères) :
- ✅ Problématique **ouverte** (on ne répond pas "oui/non")
- ✅ Notions du programme **clairement identifiables** : probabilités conditionnelles, formule de Bayes, loi binomiale, exponentielle
- ✅ **Problème réel** : justice, médecine, IA utilisent exactement ces outils
- ✅ **Maîtrise** : tu peux tout expliquer avec des exemples simples + calculs
- ✅ **Touche originale** : un anime culte que le jury connaît

---

## 🗂️ PLAN DÉTAILLÉ (≈ 10 minutes)

### 🎬 INTRODUCTION — *~1 min*

**Accroche (à dire telle quelle) :**
> « Un élève trouve un carnet surnaturel : il suffit d'y écrire un nom, en visualisant un visage, pour tuer à distance. Comment attraper un meurtrier qu'on ne voit jamais, qui ne laisse aucune trace ? C'est le défi de L, le plus grand détective du monde, face à Kira dans *Death Note*. Et ce que L fait sans jamais le nommer… c'est exactement des **mathématiques** : du raisonnement probabiliste. »

**Annonce du plan :**
1. D'abord, pourquoi l'enquête de L est un problème d'**incertitude**.
2. Ensuite, **deux outils** du programme : la probabilité conditionnelle et le théorème de Bayes.
3. Enfin, les **limites** du modèle et ses applications dans le monde réel.

---

### I. Le problème : raisonner dans l'incertain — *~1 min 30*

**L'idée :** L ne peut pas *voir* Kira. Il ne dispose que d'**indices partiels**. Toute sa méthode consiste à **réduire l'incertitude** étape par étape.

**Les règles du Death Note (à rappeler vite) :** il faut **le nom + le visage** → mort par crise cardiaque en 40 secondes par défaut.

**L'exemple fondateur : le piège de Lind L. Tailor (épisode 2).**
- L fait diffuser un faux message télévisé d'un certain "L" (en réalité un condamné à mort, Lind L. Tailor) qui défie Kira.
- **Le génie** : il prétend que c'est mondial, mais la diffusion ne passe **que dans la région du Kantō** (Japon).
- Kira le tue. Or, pour tuer, Kira devait **voir le visage** → donc Kira était dans le Kantō.

👉 En une seule expérience, L fait passer le suspect de « n'importe qui sur Terre » à « quelqu'un dans le Kantō ». C'est de l'**élimination par probabilité conditionnelle**.

**Transition :** « Mathématiquement, que s'est-il passé ? C'est exactement le rôle d'une probabilité conditionnelle. »

---

### II. Le cœur mathématique : probabilités conditionnelles et Bayes — *~4 min*

#### 🔹 A. La probabilité conditionnelle : le piège de Lind L. Tailor — *~1 min 15*

**Définition à donner :**
$$P_B(A) = \frac{P(A \cap B)}{P(B)}$$
*« La probabilité de A sachant B, c'est la probabilité que A se réalise quand on sait que B est réalisé. »*

**Application :**
- A = « Kira est dans le Kantō »
- B = « Kira tue le faux L »

Comme la diffusion n'a eu lieu **que** dans le Kantō, l'événement B **ne peut se produire que si A est vrai**. Donc :
$$P_B(A) \approx 1$$

> **Argument clé :** L n'a pas « deviné ». Il a **conçu une expérience** qui force la probabilité conditionnelle à sauter vers la certitude. C'est la différence entre un amateur et un mathématicien : il **contrôle l'information** en contrôlant l'expérience.

**Transition :** « Mais un seul indice ne suffit pas. Comment L *accumule*-t-il les preuves ? C'est le théorème de Bayes. »

#### 🔹 B. Le théorème de Bayes : la vraie arme de L — *~2 min*

**La formule (à écrire au brouillon / citer) :**
$$P_E(H) = \frac{P_H(E) \times P(H)}{P(E)} \quad \text{avec} \quad P(E)=P_H(E)P(H)+P_{\bar H}(E)P(\bar H)$$

**Le principe en une phrase :** on part d'une suspicion *a priori* $P(H)$, et on la **met à jour** avec un nouvel indice $E$.

**Exemple concret — « Light est-il Kira ? »** (Light = le fils du chef de la police, que L soupçonne très tôt).

Soit H = « Light est Kira ».

**Étape 1 — Premier indice :** « les meurtres s'arrêtent quand Light est confiné/surveillé ».

| | Valeur | Signification |
|---|---|---|
| $P(H)$ | 0,05 | suspicion de départ (L dit "5 % de chances") |
| $P_H(E)$ | 0,95 | s'il est Kira, très probable que les morts s'arrêtent |
| $P_{\bar H}(E)$ | 0,10 | s'il ne l'est pas, ce serait une coincidence |

$$P(E) = 0{,}95 \times 0{,}05 + 0{,}10 \times 0{,}95 = 0{,}1425$$
$$\boxed{P_E(H) = \frac{0{,}95 \times 0{,}05}{0{,}1425} \approx 0{,}33}$$

👉 La suspicion passe de **5 % à 33 %**.

**Étape 2 — On réinjecte le résultat comme nouvelle suspicion** (c'est ça, la force de Bayes : on *itère*).

Nouvel indice $E_2$ (ex. le comportement de Light, ses alibis trop parfaits) : $P_H(E_2)=0{,}90$, $P_{\bar H}(E_2)=0{,}20$.

$$P(E_2)=0{,}90 \times 0{,}33 + 0{,}20 \times 0{,}67 \approx 0{,}433$$
$$\boxed{P_{E_2}(H) \approx \frac{0{,}90 \times 0{,}33}{0{,}433} \approx 0{,}69}$$

👉 **5 % → 33 % → 69 %** (et une 3ᵉ itération donnerait ≈ 93 %).

> **Argument clé :** Bayes, c'est une **machine à faire converger vers la certitude**. Chaque indice, même faible, rapproche de la vérité. C'est *exactement* la patience de L : il ne clame jamais "c'est lui !", il **fait monter le pourcentage** jusqu'à ne plus pouvoir douter.

**Transition :** « Et quand un seul indice ne suffit pas, L multiplie les petits pièges. Là intervient un autre outil du programme. »

#### 🔹 C. Loi binomiale : la stratégie des "petits pièges" — *~45 sec*

**L'idée :** L pose plein de **petits tests indépendants** (caméras, fausses infos…). Chacun n'a qu'une faible chance $p$ de faire trébucher Kira… mais **répétés**, ils deviennent redoutables.

Le nombre de "réussites" suit une **loi binomiale** $\mathcal{B}(n,p)$. La probabilité d'**au moins une** réussite :
$$P(\text{au moins 1}) = 1 - (1-p)^n$$

**Exemple :** $p = 0{,}10$ par piège, $n = 30$ pièges :
$$P = 1 - 0{,}9^{30} \approx 1 - 0{,}042 \approx 0{,}96$$

> **Argument clé :** avec des pièges qui n'ont que 10 % de chances chacun, L atteint **96 % de chances** de coincer Kira. C'est la stratégie de l'**accumulation** : beaucoup de coups faibles valent mieux qu'un seul coup risqué. (Et on retrouve la fonction **exponentielle** dans le $(1-p)^n$.)

---

### III. Limites et ouverture — *~2 min 15*

#### 🔹 A. Les limites du modèle — *~1 min*

1. **Le *prior* est subjectif** : pourquoi partir de 5 % et pas 20 % ? Le choix de $P(H)$ initial **influence tout le résultat**. Deux détectives peuvent calculer différemment.
2. **Kira manipule les données** : dans l'anime, Light **fabrique de faux indices** (fausse règle des 13 jours, perte de mémoire, seconde Kira = Misa). Un modèle probabiliste n'est bon que si les **données sont fiables** — *« garbage in, garbage out »*.
3. **Corrélation ≠ causalité** : « les morts s'arrêtent quand Light est confiné » prouve un lien, pas forcément que Light *est* Kira.

#### 🔹 B. Ouverture sur le monde réel + critique — *~1 min 15*

> « Ce qui est bluffant, c'est que le "truc de L" est utilisé **partout** dans la vraie vie. »

- **Médecine** : probabilité d'être *vraiment* malade sachant un test positif (Bayes explique pourquoi un test "fiable à 99 %" peut donner beaucoup de **faux positifs**).
- **Justice** : évaluation des preuves ADN.
- **IA / réseaux sociaux** : les **filtres anti-spam** et la recommandation utilisent le **classifieur bayésien naïf**.

**La critique qui montre ton recul (le point 20/20) :**
> « Mal utilisé, Bayes devient dangereux. C'est le **biais du procureur** : confondre $P(\text{preuve} \mid \text{innocent})$ et $P(\text{innocent} \mid \text{preuve})$. Ce ne sont **pas** les mêmes probabilités ! Cette erreur a causé de vraies erreurs judiciaires, comme l'affaire **Sally Clark** au Royaume-Uni. »

---

### 🏁 CONCLUSION — *~30 sec*

> « L nous montre que les probabilités conditionnelles sont un **outil redoutable pour raisonner dans l'incertain** : elles font converger vers la vérité, indice après indice. Mais *Death Note* nous avertit aussi : l'outil est **aussi fiable que celui qui le manie** et que les **données** qu'on lui donne. Les maths ne remplacent pas la rigueur — elles l'exigent. »

---

## ⏱️ Récap du timing

| Partie | Durée |
|---|---|
| Intro | 1 min |
| I. Le problème | 1 min 30 |
| II. Bayes + binomiale | 4 min |
| III. Limites + ouverture | 2 min 15 |
| Conclusion | 30 s |
| **Total** | **≈ 9 min 45** |

---

## 🧠 Questions probables du jury (+ réponses express)

1. **« Pourquoi le choix du *prior* pose problème ? »**
→ Parce que $P_E(H)$ dépend directement de $P(H)$. Si je pars de 20 % au lieu de 5 %, toute la convergence change. Le résultat n'est donc jamais "objectif" à 100 %.

2. **« C'est quoi la différence entre $P_H(E)$ et $P_E(H)$ ? »**
→ $P_H(E)$ : proba de l'indice **si** Light est coupable (facile à estimer). $P_E(H)$ : proba qu'il soit coupable **sachant** l'indice (ce qu'on cherche). Les confondre = biais du procureur.

3. **« Pourquoi une loi binomiale et pas autre chose ? »**
→ Parce qu'on répète $n$ épreuves **identiques et indépendantes** à deux issues (succès/échec) : c'est exactement le schéma de Bernoulli.

4. **« Ton sujet, c'est de la philo ou des maths ? »**
→ Les deux : la **démonstration** est mathématique (Bayes, binomiale), l'**ouverture** est citoyenne (justice, IA). C'est justement ce qu'attend le Grand Oral.

---

## ⚠️ Pièges à éviter

- ❌ **Raconter l'anime** au lieu de faire des maths → le jury note les *maths*, pas ta culture manga. 30 secondes de contexte max.
- ❌ **Réciter** les formules sans exemple → fais toujours le calcul concret (5 % → 33 % → 69 %, ça marque les esprits).
- ❌ **Sur-promettre** : ne dis jamais que Bayes "prouve" la culpabilité. Dis qu'il **quantifie** l'incertitude.
- ✅ **Maîtrise tes chiffres** : sache refaire les 3 calculs au brouillon si on te le demande.

Si tu veux, je peux aussi te rédiger le **discours mot pour mot** (le texte intégral à apprendre), ou te préparer une **fiche de révision des formules** + d'autres exemples Death Note pour les questions. Tu préfères quoi ?
