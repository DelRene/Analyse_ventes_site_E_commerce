# Analyser les ventes d'un site E-commerce
*Ce projet a été réalisé dans le cadre de ma formation chez OpenClassrooms.*

### Un projet de plus passionnant !!
2 ans après l'ouverture de leur site E-commerce, l'entreprise LAPAGE, spécialisée dans la vente de livre, fait appel à moi pour analyser l'activité E-commerce de ses 2 premières années sur internet.

Pour cette mission, 3 étapes ont été réalisées :  
* Le Nettoyage des données  
* L'analyse uni et bivariée des données  
* Tests statistiques  

<ins>Les données (3 tables) </ins>  
 * La table <ins>client</ins> : (Dimensions : 8623 lignes * 3 colonnes)  
> - **client_id** : L'identification unique du client (*object*)  
> - **sex** : Le genre du client (*object*)  
> - **birth** : L'année de naissance du client (*int*)  
        
 * La table <ins>livre</ins> : (Dimensions : 3287 lignes * 3 colonnes)  
> - **id_prod** : L'identification unique du livre (*object*)  
> - **price** : Le prix du livre en euros (*float*)
> - **categ** : La catégorie du livre (*int*)  
        
 * La table <ins>transaction</ins> : (Dimensions : 679532 * 4 colonnes)  
> - **id_prod** : L'identification unique du livre (*object*)  
> - **date** : L'heure et la date de la transaction (*object*)  
> - **client_id** : L'identification unique du client (*object*)  
> - **session_id** : La session de connexion du client (*object*)  


The analyses performed in this project are in French. If you want a translated version, please contact me on linkedin*.


**Analyses et tests statistiques :** (Scipy | Matplotlib | Seaborn |)
