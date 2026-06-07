**🇫🇷 Français** · [🇬🇧 English](README.en.md)

# Bonjour 👋

Je m'appelle **Éric**. J'aime construire des choses qui marchent.

Après une longue route autour des bases de données et des infrastructures Windows,
ce qui me fait toujours autant plaisir, c'est de **fabriquer mes propres outils**,
souvent en PowerShell, autonomes, sans installation, avec une petite interface web
dans le navigateur. Ça les rend utilisables partout, y compris sur les
environnements fermés ou déconnectés. Quand ils servent à d'autres, je les publie
ici en licence MIT.

## 🛠️ Mes outils

### [PS-MRTG](https://github.com/vietnamix/ps-mrtg) · supervision de bande passante réseau
Une réinterprétation moderne du vénérable MRTG, repensée pour le monde Windows.
Collecte le trafic réseau d'un serveur (SNMP, compteurs de perfs) et le restitue
en graphes lisibles directement dans le navigateur, exportables. Pensé pour
fonctionner même en environnement Windows pur et déconnecté.

### [PS-PING](https://github.com/vietnamix/ps-ping) · analyse de ping en profondeur
Bien plus qu'un `ping -t` : une analyse fine de la latence avec zoom intelligent,
qui révèle des incohérences réseau que les outils classiques (ping, SmokePing)
laissent passer. Détection automatique d'anomalies par heuristique sur fenêtres
glissantes, et interface web interactive pour explorer les mesures.

### [PS-NCDU](https://github.com/vietnamix/ps-ncdu) · analyse d'occupation disque
Dans l'esprit de NCDU (Linux) et TreeSize (Windows), mais en PowerShell natif avec
une interface web dynamique. Identifie en temps réel ce qui remplit un disque,
sans rien installer. Idéal sur les environnements régulés (banque, pharma) où
l'on ne peut pas déployer d'outil externe.

### [PS-ZIM](https://github.com/vietnamix/ps-zim) · lecture de documentation hors-ligne
Lit des archives documentaires (dumps Wikipedia, bases statiques, wikis exportés)
dans le navigateur, en local et sans aucune connexion. Serveur HTTP intégré et
parsing du format wiki. Pratique quand on travaille coupé du monde.

> Point commun : 100 % PowerShell, zéro installation, fonctionne sur n'importe
> quel Windows. Tous co-construits avec des LLM, devenu une part importante de
> ma façon de coder aujourd'hui.

---

`PowerShell` · `SQL` · infra Windows/Linux & automatisation · [LinkedIn](https://linkedin.com/in/eric-guiffault) · eric@guiffault.com · https://eric.guiffault.com
