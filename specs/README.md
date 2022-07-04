# Document de spécification - KSell
Nous aurons 3 profils dans l'application:
- `Le demandeur`: Il fait part d'un besoin sur la plateforme
- `Le voyageur`: Il se déplace d'une zone à l'autre transportant les objets demandés à la requête du demandeur.
- `L'administrateur`: Il administre la plateforme et s'assure de son bon fonctionnement.

## Fonctionnalités
- Le `demandeur` ajoute une requête sur la plateforme. Dans cette requête, il fait part des biens qu'il aimerait faire transporter et la destination. Il peut ajouter la rémunération (optionnel mais ceci occasionnera des négociations).
- Les `voyageurs` répondent aux besoins des demandeur en faisant des propositions. Ces propositions comportent:
    * Sa rémunération
    * La date limite pour livrer
- Le `voyageur`, peut en outre, soumettre un déplacement et rendre disponible sa charge de voyage restante. Dans ce cas de figure, les demandeurs intéressés viennent soumettre leur propositions.
- Une fois le `demandeur` et `voyageur` d'accord, un contrat est créé contenant les termes de cet accord. Il contient notamment:
    * La rémunération finale.
    * Le délai de réalisation.
    * Trace des transactions et des activités.
    * Les objets concernés.
- Un contrat ne peut être clos que lorsque les deux parties sont satisfaites. A l'établissement du contrat, le demandeur va effectuer un dépôt de la somme mise à jeu pour ce travail. Le voyageur ne percevra sa part que lorsque le travail est accompli. Cette somme sera stocké sur la plateforme jusqu'au remplissement du contrat.

