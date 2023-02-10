# Installer ansible sur macos

brew install ansible

# Voir la version de ansible

ansible --version

# Prérequis

## Installer python3 sur le server

## Générer un clé ssh pour se connecter au server

ssh-keygen

- Puis envoyer la clé au niveau du server avec la commande:
  ssh-copy-id root@ip_server
- Vous pouvez vous connecter au server sans tapper de mot de pass
  ssh root@ip_sever

# Créer un fichier hosts pour mettre la liste des server a configurer

ansible-playbook -i hosts playbook.yml
