# Exercice 1 : Configuration Réseau Multi-VLAN avec Packet Tracer

## Objectif
Creation d'un minilab pour configurer un réseau avec 4 VLANs, DHCP et routage inter-VLAN.

1. **Topologie** :
   - Routeur Cisco 1941
   - 1 Core Switch ( pour la distribution) + 3 Switches d'accès
   - VLANs :
     - VLAN 1 (VoIP)
     - VLAN 10 (Wi-Fi)
     - VLAN 20 (PC fixes)
     - VLAN 30 (Admin)
  - 3 points d'accès Wi-fi PT-AC
  - 3 PC portables
  - 6 PC fixes
  - 3 téléphones IP Cisco

2. ## Méthodologie :
    - Mise en place de la topologie réseau sur packet tracer
    - Configuration du routeur pour servir de passerelle internet, de serveur DHCP et de gestionnaire de VLAN
    - Configuration du Switch de distribution qui sera relié au routeur et aux autres switchs
    - Configuration des 3 switchs pour la création des vlans et les ports en mode Trunk
    - Configuration des autres équipements réseaux
    - Vérification si les équipement réseaux reçoivent des adresses IP via DHCP
    - Tests de ping entre les équipement si tout marche

3. ## Fichiers Inclus
- `exo1.pkt` : Fichier Packet Tracer
- `configs/` : Exports des configurations
