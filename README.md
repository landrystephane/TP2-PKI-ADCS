# TP2 PKI / AD CS : déployer et administrer une PKI

Formation « Implémenter une PKI avec Microsoft AD CS », jour 2.
Réalisé par Landry TOUOTAP, octobre 2026.

## Contenu

| Élément | Description |
|---|---|
| Rapport PDF | Rapport du TP (missions A à E, défi RSSI, note d'architecture, procédure de dépannage) |
| Captures/ | Preuves citées dans le rapport, nommées par mission (A0 à E3, R1 à R3) |
| Captures/TP2_architecture_PKI.png | Schéma du laboratoire (source .drawio à côté) |

## Laboratoire

| Machine | Adresse IP | Rôle |
|---|---|---|
| SRV-DC01 | 192.168.178.10 | AD DS + DNS, domaine pki.lab |
| SRV-CA01 | 192.168.178.11 | AD CS, AC racine d'entreprise ALPINA-LAB-CA |
| CLIENT01 | 192.168.178.21 | Poste autorisé (groupe ALPINA-PKI-Pilote) |
| CLIENT-TEST | 192.168.178.22 | Poste non autorisé (défi RSSI) |

Réseau isolé VMware (VMnet1, host-only). Aucun compte administrateur ni clé privée n'est publié.