# Sekans Studio — mises à jour

Canal de mise à jour des postes clients de Sekans Studio.

Chaque paquet (`clients/<id>/<version>.maj`) est chiffré (AES-256-GCM) avec la licence du client concerné : il est illisible sans elle.
`<id>` est dérivé de la licence et ne révèle ni le nom du client ni sa clé.

Publié par `installer/publier-maj.sh` (dépôt sekans-studio).

`clients/<id>/statut.json` (facultatif) : `{"statut":"suspendu"}` met les nouveaux montages du poste en pause. Absent = actif.
