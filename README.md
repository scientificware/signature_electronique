# signature_electronique
Documention liée à la signature électronique

# Règlement Européen eIDAS : Identité Numérique & Services de Confiance (Mise à jour : Octobre 2026)

Le règlement européen **eIDAS** (*electronic IDentification, Authentication and trust Services*) est le cadre juridique de l'Union européenne qui harmonise et sécurise les **échanges électroniques, l'identité numérique et les services de confiance** au sein du marché unique. 

Initialement adopté en 2014 (eIDAS 1), le dispositif a été profondément modernisé par la révision **eIDAS 2.0** (établie par le **règlement (UE) 2024/1183** entré en vigueur en mai 2024).

---

## 1. Le grand tournant : eIDAS 2.0 et le "Wallet" européen (EUDI Wallet)

La mise à jour **eIDAS 2.0** accélère la souveraineté et la numérisation des usages en fixant des échéances de déploiement précises :

* **Le Portefeuille Européen d'Identité Numérique (EUDI Wallet) :** 
  * **Pour les États membres :** Ils ont l'obligation juridique de fournir au moins une solution de portefeuille numérique mobile gratuite et facultative pour les citoyens, résidents et entreprises d'ici le **24 décembre 2026**.
  * **Pour les organismes et entreprises (échéance 24 décembre 2027) :** Les organismes du secteur public, les entreprises privées non-micro soumises à une obligation d'authentification forte, ainsi que les Très Grandes Plateformes en Ligne (VLOPs visées par le DSA) devront être en mesure d'accepter l'EUDI Wallet.
* **À quoi sert-il ?** Il permet de stocker de manière hautement sécurisée (dans le respect strict du RGPD et de la minimisation des données) des documents d'identité (carte d'identité, permis de conduire), des diplômes ou des justificatifs. Il sert à s'authentifier en ligne/hors-ligne et à signer des documents électroniquement avec un contrôle total de l'utilisateur sur le partage de ses attributs.

---

## 2. Les Services de Confiance Numérique

eIDAS encadre juridiquement plusieurs services clés fournis par des prestataires de services de confiance qualifiés (PSCE), sous le contrôle d'autorités nationales (comme l'[ANSSI](https://cyber.gouv.fr) en France) :

* **La Signature Électronique :** Pour les personnes physiques (3 niveaux de sécurité) :
  1. *Simple :* Preuve faible (ex. case à cocher, scan).
  2. *Avancée (SEA) :* Liée de manière univoque au signataire avec critères stricts d'intégrité.
  3. *Qualifiée (SEQ) :* Repose sur une vérification stricte de l'identité en amont via un Dispositif Sécurisé de Création de Signature (QSCD). **Même valeur légale qu'une signature manuscrite** dans toute l'UE.
* **Le Cachet Électronique :** L'équivalent de la signature, mais réservé aux personnes morales (entreprises, administrations) pour certifier l'origine et l'intégrité des documents.
* **L'Horodatage Électronique :** Appose une date et une heure certifiées et infalsifiables.
* **L'Envoi Recommandé Électronique (ERDS) :** L'équivalent numérique de la lettre recommandée avec accusé de réception.
* **Nouveaux services qualifiés (eIDAS 2.0) :** Intégration réglementaire de services pour **l'archivage électronique sécurisé** de documents et les **registres électroniques**.

---

## 3. Les Niveaux de Garantie de l'Identité (eID)

Le règlement structure la robustesse des systèmes d'identification selon 3 niveaux d'assurance :

* **Faible :** Simple identifiant / mot de passe.
* **Substantiel :** Exige généralement un double facteur d'authentification (ex. connexion à [FranceConnect](https://franceconnect.gouv.fr) via l'Identité Numérique La Poste).
* **Élevé :** Niveau maximal contre l'usurpation d'identité, impliquant des contrôles cryptographiques ou biométriques stricts (ex. application *France Identité* couplée à la nouvelle carte d'identité à puce).

---

## Liens Utiles & Sources Officielles

* [Règlement européen sur l'identité numérique (EUDI) - Commission Européenne](https://digital-strategy.ec.europa.eu/fr/policies/eudi-regulation)
* [Portefeuille européen d'identité numérique - numerique.gouv.fr (DINUM)](https://numerique.gouv.fr/actualites/portefeuille-europeen-identite-numerique-eu-digital-identity-wallets/)
* [Réglementation Identité & Confiance Numérique - ANSSI](https://cyber.gouv.fr)
* [Niveaux de garantie eIDAS - FranceConnect](https://franceconnect.gouv.fr)


# Signature de documents PDF avec l'EUDI Wallet (France Identité)

**Il est signer des documents PDF** avec cette technologie. C'est l'une des fonctionnalités majeures apportées par le cadre réglementaire européen de l'EUDI Wallet. 

Cependant, **l'application France Identité ne dispose pas d'un bouton "Signer un PDF" directement dans son interface**. Elle sert de clé de sécurité (de "fournisseur d'identité") pour valider votre signature sur des plateformes de signature externes.

---

### 1. Valeur juridique de la signature
En associant votre application France Identité (liée à votre nouvelle carte d'identité) à une plateforme de signature, vous générez une **Signature Électronique Qualifiée (SEQ)** :
* Il s'agit du niveau de sécurité le plus élevé de la réglementation européenne eIDAS.
* Elle possède la **même valeur juridique qu’une signature manuscrite**.
* Le document PDF signé devient infalsifiable et est légalement contraignant dans toute l'Union européenne.

### 2. Procédure pour signer un PDF
Pour signer votre document, vous devez passer par un site tiers ou un prestataire de services de confiance (comme *Goodflag*, *Namirial*, *DocuSign*, etc.) qui intègre l'écosystème France Identité / EUDI Wallet.

1. **Téléversez** votre document PDF sur la plateforme de signature choisie.
2. Au moment de signer, sélectionnez l'option d'authentification par **France Identité** ou **FranceConnect+**.
3. **Ouvrez la notification** qui apparaît sur votre smartphone.
4. **Validez l'action** dans votre application France Identité en saisissant votre code personnel et en scannant votre carte d'identité en NFC au dos du téléphone.
5. Votre PDF est instantanément **signé et certifié**.
Utilisez le code avec précaution.
Souhaitez-vous que je génère ce contenu sous la forme d'un fichier Markdown (.md) téléchargeable, ou préférez-vous obtenir des exemples de plateformes de signature compati
bles ?

markdown
# Intégration de l'écosystème France Identité / EUDI Wallet sur Android

Pour intégrer l'écosystème **France Identité / EUDI Wallet** dans votre application Android en tant que **Partie Vérifiante** (Relying Party), vous devez implémenter le protocole standardisé européen **OID4VP** (OpenID for Verifiable Presentations), qui régit les échanges décentralisés d'identités.

Trois approches techniques permettent d'y parvenir :

---

### 🛠️ Les 3 méthodes d'intégration

#### 1. Le Raccordement EUDI Wallet (Via protocole standard OID4VP)
C'est la méthode native et interopérable recommandée par l'Union européenne. Elle s'appuie sur le framework d'architecture **ARF 3.0**.
* **Le flux :** Votre application Android effectue une requête d'authentification ou de vérification d'attributs. L'utilisateur bascule automatiquement vers son application *France Identité* (ou un autre portefeuille européen compatible) pour consentir au partage, puis revient sur votre application.
* **Le protocole :** L'échange se fait en **OpenID4VP**. L'application Android agit comme une interface qui redirige vers le portefeuille mobile ou affiche un QR code cross-device.
* **Pour coder sur Android :** La Commission européenne fournit des SDK de référence open source. Vous devez implémenter le client de vérification en utilisant les bibliothèques officielles disponibles sur le [GitHub de l'European Digital Identity Wallet](https://github.com).

#### 2. Le Raccordement Direct (Via OpenID Connect - OIDC)
Si vous souhaitez une intégration plus classique et directement centralisée au niveau de votre serveur (backend) :
* Vous utilisez le protocole **OpenID Connect (OIDC)** classique.
* Votre application Android intègre un flux d'authentification web standard (via les *Custom Tabs* d'Android).
* La cinématique renvoie l'utilisateur vers le serveur de France Identité qui gère la liaison avec l'application mobile et vous renvoie les *claims* (données d'identité vérifiées) au format JWT.

#### 3. Le Raccordement via le "Playground" (Environnement de Test)
Avant de passer en production, France Identité met à disposition un espace d'expérimentation appelé **Playground**. Il permet de simuler des parcours utilisateurs complets avec de fausses puces NFC et des profils de test pour valider le comportement de votre application Android sans manipuler de vraies données régaliennes.

---

### 💻 Architecture technique d'un échange OID4VP sur Android

Le schéma d'intégration mobile suit une logique décentralisée appelée le **Triangle de Confiance** (Émetteur de l'identité → Titulaire du portefeuille → Votre application de vérification) :

Utilisez le code avec précaution.
+------------------------+                    +---------------------------+
| Votre App Android      | -- 1. Request ---->|  Portefeuille Mobile      |
| (Partie Vérifiante)    | <-- 2. Response -- | (France Identité / EUDI)   |
+------------------------+                    +---------------------------+
|                                                ^
3. Crypto Check                                    NFC / Puce
v                                                |
+------------------------+                                  v
| Votre Serveur / API    | <======================== [ Carte d'identité CNIe ]
+------------------------+

1. **La Requête (Presentation Request) :** Votre application formule une demande signée spécifiant les attributs strictement nécessaires (ex: `age_over_18` ou `given_name`) au format JSON-LD / SD-JWT.
2. **Le Deep Linking :** Sur Android, vous utilisez un *App Link* ou un *Intent scheme* spécifique pour ouvrir l'application France Identité installée sur le téléphone de l'utilisateur.
3. **La Réponse (Presentation Submission) :** Une fois le consentement donné par l'utilisateur (via son empreinte ou son code PIN), France Identité renvoie un jeton chiffré à votre application (ou à votre serveur de redirection).
4. **La Vérification :** Votre backend valide cryptographiquement la signature émise par l'ANTS (Agence Nationale des Titres Sécurisés) pour s'assurer que les données n'ont pas été altérées.

---

### 🚀 Par où commencer ?

Pour démarrer le développement technique sur votre application Android :

1. Accédez à l'espace développeur et contactez l'équipe d'intégration officielle via l'adresse dédiée [contact@france-identite.gouv.fr](mailto:contact@france-identite.gouv.fr) afin d'obtenir vos identifiants clients de test.
2. Consultez la documentation officielle de l'architecture européenne (ARF) pour comprendre les formats d'attestation retenus (SD-JWT et mDoc ISO 18013-5).
3. Intégrez le SDK Android de vérification d'identifiants présent sur le GitHub de l'UE pour automatiser le traitement des réponses chiffrées dans votre code Kotlin ou Java.
Préférez-vous que je génère un exemple de code Kotlin pour configurer l'Intent de redirection vers le Wallet, ou souhaitez-vous un modèle de structure JSON pour une requête de présentation d'attributs (OID4VP) ?
