<img align="right" width="150" alt="logo" src="https://user-images.githubusercontent.com/5889006/190859553-5b229b4f-c476-4cbd-928f-890f5265ca4c.png">

# Hugo Theme Stack Starter Template

This is a quick start template for [Hugo theme Stack](https://github.com/CaiJimmy/hugo-theme-stack). It uses [Hugo modules](https://gohugo.io/hugo-modules/) feature to load the theme.

It comes with a basic theme structure and configuration. GitHub action has been set up to deploy the theme to a public GitHub page automatically. Also, there's a cron job to update the theme automatically everyday.

## Get started

1. Click *Use this template*, and create your repository on GitHub.
![Step 1](https://user-images.githubusercontent.com/5889006/156916624-20b2a784-f3a9-4718-aa5f-ce2a436b241f.png)

2. Once the repository is created, create a GitHub codespace asociated with it.
![Create codespace](https://user-images.githubusercontent.com/5889006/156916672-43b7b6e9-4ffb-4704-b4ba-d5ca40ffcae7.png)

3. And voila! You're ready to go. The codespace has been configured with the latest version of Hugo extended, just run `hugo server` in the terminal and see your new site in action.

4. Check `config` folder for the configuration files. You can edit them to suit your needs. Make sure to update the `baseurl` property in `config/_default/config.toml` to your site's URL.

5. Once you're done editing the site, just commit it and push it. GitHub action will deploy the site automatically to GitHub page asociated with the repository.
![GitHub action](https://user-images.githubusercontent.com/5889006/156916881-90b8bb9b-1925-4e60-9d7a-8026cda729bf.png)

# Mon portfolio Hugo avec Docker

## Instructions

### Créer l'image Docker

Pour créer l'image Docker, exécutez la commande suivante à la racine du projet :

```bash
docker-compose build
### Démarrer le conteneur Hugo 
docker-compose up
### run hugo 
hugo server 
### Accéder au site Hugo
Web Server is available at http://localhost:1313/portfolio/ (bind address 127.0.0.1)
###Arrêter le conteneur
docker-compose down
