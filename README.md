# Aetheris Infrastructure Deployment Scripts (`infra-deploy-scripts`)

**Maintainer:** Alexandre Chen (`a.chen@aetheris-logistics.tech` / `@alex-chen-cloud`)  
**Project:** Cerberus Disaster Recovery Gateway (`aetheris-logistics.tech`)

## Procédure de recouvrement d'urgence (`token.enc`)

Pour déverrouiller le jeton contenu dans `token.enc` via **CyberChef**, appliquez séquentiellement :
1. **`From Base64`**
2. **`From Hex`**
3. **`XOR`** avec la clé `AETHERIS_MASTER_XOR_KEY` (encodage **UTF8**, mode `Standard`).
