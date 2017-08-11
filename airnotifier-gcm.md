# Mise à jour d'AirNotifier

## Contenu du paquet
- `gcm.py` : Script Python gérant la transmission des notifications à Firebase Cloud Messaging (anciennement Google Cloud Messaging).

## Installation
Avec le compte `root`, copier le script `gcm.py` dans le dossier `/root/airnotifier/pushservices` puis relancer le service AirNotifier à l'aide de la commande `service airnotifier restart` :

~~~sh
bdf-guest@server ~$ sudo -s
root@server ~# cp gcm.py /root/airnotifier/pushservices/
root@server ~# service airnotifier restart
Redirecting to /bin/systemctl restart  airnotifier.service
root@server ~#
~~~
