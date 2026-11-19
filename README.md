# rtacollection-licences

Ce depot ne contient qu'un fichier, `etat_licences.json` : l'etat des licences du logiciel RTAcollection.

Le logiciel lit ce fichier pour confirmer qu'une licence est toujours en vigueur. Le fichier est signe par l'editeur
(Ed25519) ; il ne contient que des identifiants de licence, aucun nom de client ni aucune donnee de client.

Ne pas modifier ce fichier a la main : une modification invalide la signature et le logiciel l'ignore.
