# Claudy Marketplace

Marketplace des plugins Claude Code maintenus par [Gilles Bertrand](https://github.com/gilles-bertrand).

## Comment l'utiliser

### 1. Enregistrer le marketplace

Dans Claude Code :

```bash
/plugin marketplace add gilles-bertrand/claudy-marketplace
```

### 2. Explorer les plugins disponibles

```bash
/plugin
```

Puis onglet **Discover**.

### 3. Installer un plugin

```bash
/plugin install <nom-plugin>@claudy-marketplace
```

## Plugins disponibles

| Plugin | Version | Description |
|--------|---------|-------------|
| [`claudy`](https://github.com/gilles-bertrand/claudy-plugin) | 0.3.0 | Boîte à outils complète (commandes TPK-*, agents, skills, hooks sécurité) + commandes `/claudy-eject` et `/claudy-sync` pour matérialiser/évoluer les ressources par projet |

## Mise à jour

Pour récupérer les nouvelles versions publiées dans ce marketplace :

```text
/plugin marketplace update claudy-marketplace
/plugin update claudy@claudy-marketplace
```

Si vous avez utilisé `/claudy-eject` dans un projet pour matérialiser les ressources du plugin, lancez `/claudy-sync` après une mise à jour pour rapatrier les nouveautés sans toucher à vos personnalisations.

## Contribuer

Chaque plugin vit dans son propre dépôt. Pour proposer une modification :

1. Forkez le dépôt du plugin concerné (ex: `gilles-bertrand/claudy-plugin`)
2. Créez une pull request
3. Une fois mergée et taguée, la nouvelle version sera référencée dans ce marketplace

## Licence

MIT © Gilles Bertrand
