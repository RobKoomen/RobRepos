# Samenwerken met Git

## Introductie
Dit document beschrijft hoe je effectief kunt samenwerken met Git.

## Belangrijke concepten

### Branches
- Branches stellen je in staat om parallel aan verschillende features te werken
- Elke branch is een onafhankelijke ontwikkellijn

### Pull Requests
- Pull requests worden gebruikt om code reviews te faciliteren
- Ze maken het mogelijk om wijzigingen te bespreken voordat ze worden gemerged

### Merge Conflicts
- Ontstaan wanneer twee branches dezelfde regels hebben gewijzigd
- Moeten handmatig worden opgelost

## Best Practices
1. Maak regelmatig commits met duidelijke commit messages
2. Houd branches klein en gefocust
3. Pull regelmatig de laatste wijzigingen van main/master
4. Test je code voordat je pusht
5. Gebruik beschrijvende branch namen

## Workflow
1. Maak een nieuwe branch aan: git checkout -b feature/naam
2. Maak wijzigingen en commit: git add . en git commit -m "beschrijving"
3. Push naar remote: git push -u origin feature/naam
4. Maak een pull request aan
5. Na review en goedkeuring: merge naar main

