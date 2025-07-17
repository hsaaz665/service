# ${{ values.name }}

${{ values.description }}

**🚀 Généré automatiquement via Backstage**

## ℹ️ Informations

- **Nom**: ${{ values.name }}
- **Propriétaire**: ${{ values.owner }}
- **Type**: Service Simple
- **Status**: ✅ Actif

## 🎯 Test du template

Ce service a été créé pour tester l'intégration GitHub avec Backstage.

### Fonctionnalités testées :

- ✅ Génération de code depuis template
- ✅ Création automatique de repository GitHub  
- ✅ Enregistrement dans le Catalog Backstage
- ✅ Métadonnées de service

## 🚀 Utilisation

```bash
# Cloner le repository
git clone https://github.com/your-org/${{ values.name }}.git

# Aller dans le dossier
cd ${{ values.name }}

# Lancer le service (Python requis)
python -m http.server 8000

# Ou avec Node.js
npx serve .
