# Anovel
Website for Anovel application project

## Auteur: ROBION Alban

## Installation/Configuration

### Serveur Web local

Lancez le serveur Web local avec cette commande :
```bash
composer start
```

### Accéder au server

aller à l'addresse indiqué sur lignes de commande 

### Style de codage

Le code suit la recommandation [PSR-12](https://www.php-fig.org/psr/psr-12/) :
- il peut être contrôlé avec `composer test:cs`
- il peut être reformaté automatiquement avec `composer fix:cs`


### Tests

Pour lancer les tests :
- général et complet : `composer test`
- de mise en forme : `composer test:cs`
- de code en lui-même : `composer test:codeception`
