# Aventuriers Livrets — Commande Club des Aventuriers

Page web statique pour la commande des **livrets des 6 classes du Club des Aventuriers** (Église Adventiste du 7ème Jour / MJA).

## Fonctionnalités

- **Identité visuelle officielle** : 3 logos téléchargés des sites officiels :
  - Logo SDA français centré blanc — `cdn.adventist.org`
  - Logo Adventist Youth (MJA) — `gcyouthministries.org`
  - Logo Adventurer Club — `adventurers.adventistchurch.com`
  - 6 logos individuels des classes (NAD Club Ministries)
- **N° de commande automatique** `YYYYMMDD-HHMMSS` (non modifiable)
- **6 classes officielles francophones** avec leur logo, nom FR + EN, âge :
  - 🐑 Petits Agneaux (Little Lamb) — 4 ans
  - 🦫 Castors Curieux (Eager Beaver) — 5 ans
  - 🐝 Abeilles Actives (Busy Bee) — 6 ans
  - ☀️ Rayons de Soleil (Sunbeam) — 7 ans
  - 🔨 Constructeurs (Builder) — 8 ans
  - 🤝 Mains Utiles (Helping Hand) — 9 ans
- **Tarif unique** : 1 000 FCFA par livret
- **Calcul du total en direct**
- **Date limite affichée** : vendredi 6 juin 2026 (bandeau bourgogne)
- **2 modes de paiement** : Wave et Orange Money (pas d'espèces)
- **Numéro Chef Charles** : +223 74 13 00 84
- **Envoi WhatsApp formaté** au Chef Charles via lien `wa.me` pré-rempli

## Exemple de message WhatsApp envoyé

```
🎯 *NOUVELLE COMMANDE LIVRETS AVENTURIERS*
━━━━━━━━━━━━━━━━━━

📌 *N° Commande* : 20260520-143752
👤 *Nom & Prénom* : Diarra Aïssata
⛪ *Club / Église* : Église Adventiste de Bamako-Sotuba
⏰ *Date limite* : vendredi 6 juin 2026

📚 *DÉTAIL DE LA COMMANDE*
• 🐑 Petits Agneaux (Little Lamb) : 3 × 1 000 = 3 000 FCFA
• 🐝 Abeilles Actives (Busy Bee) : 5 × 1 000 = 5 000 FCFA
• 🤝 Mains Utiles (Helping Hand) : 2 × 1 000 = 2 000 FCFA
• *Total livrets* : 10

💰 *TOTAL À PAYER : 10 000 FCFA*

💳 *Mode de paiement* : Wave
📱 N° Chef Charles : +223 74 13 00 84

📸 _Capture d'écran du paiement à envoyer juste après ce message._
━━━━━━━━━━━━━━━━━━
_Commande envoyée via GuideHub Aventuriers_
```

## Déploiement GitHub Pages

1. Créer un nouveau repo public : `aventuriers-livrets`
2. Glisser-déposer `index.html`, `README.md` et le dossier `assets/` entier
3. **Settings → Pages → Source : Deploy from a branch → main → /(root) → Save**
4. URL finale : `https://<ton-username>.github.io/aventuriers-livrets/`

## Personnalisation rapide

Tout est configurable en haut du `<script>` dans `index.html` :

```js
const PRIX_UNITAIRE = 1000;
const WHATSAPP_NUM = "22374130084";   // Chef Charles
const DEADLINE = "vendredi 6 juin 2026";
```

## Structure

```
aventuriers-livrets/
├── index.html                                    # Page complète
├── README.md
└── assets/
    ├── adventist-fr-centered--white.svg          # Logo SDA officiel
    ├── adventist-symbol--white.svg               # Symbole SDA seul
    ├── AY_Logo.png                               # Logo Adventist Youth (MJA)
    ├── AdvClub_Adventurer_Logo-1.png             # Logo officiel Adventurer Club (utilisé)
    ├── AdvClub_adventurer_World_Logo.png         # Variante World
    ├── AdvClub_new-logo2.png                     # Variante 2016+
    ├── LittleLambLogo.png                        # 🐑 Petits Agneaux
    ├── EagerBeaverLogo.png                       # 🦫 Castors Curieux
    ├── BusyBeeLogo.png                           # 🐝 Abeilles Actives
    ├── SunbeamLogo.png                           # ☀️ Rayons de Soleil
    ├── BuilderLogo.png                           # 🔨 Constructeurs
    └── HelpingHandLogo.png                       # 🤝 Mains Utiles
```

---

> « Laissez venir à moi les petits enfants, et ne les en empêchez pas ; car le royaume de Dieu est pour ceux qui leur ressemblent. » — Marc 10:14
