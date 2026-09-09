Pour résoudre ce problème, nous somme revenu sur la dernière version viable avec la commande : git reset --hard "4fb99b27cc145ed1683d8cc442e3690cf5b05852"
Nous avons ensuite forcé le push pour que ça soit la bonne version sur git hub avec la commande : git push origin main --force-with-lease

Le membre B est aller chercher localement la dernière version viable avec les même commande, car il y avait une discordance avec l'origine, donc il ne pouvait pas faire un simple pull.