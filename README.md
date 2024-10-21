**Faire un projet Wordpress avec Bedrock et Composer**
```bash
composer create-project roots/bedrock nom_du_projet
```

**Configurer l'environnement de développement**
```bash
cp .env.example .env
```

**Installer theme Sage**
```bash
cd web/app/themes
```
```bash
composer create-project roots/sage votre-theme
```

**Installer les dependances du theme Sage**
```bash
cd votre-theme
composer install
yarn
yarn build
```

**Installez ACF via Composer :**
```bash
composer require wpackagist-plugin/advanced-custom-fields
```
