---
title: AllowInteriorWeapons
description: Indiquez si l'utilisation d'armes dans les intérieurs est autorisée ou non.
tags: []
---

## Description

Indiquez si l'utilisation d'armes dans les intérieurs est autorisée ou non.

| Name          | Description                                                                               |
| -----         | ----------------------------------------------------------------------------------------- |
| autorisation  | 1 pour activer, 0 pour désactiver les armes en intérieur.                                 |

## Retours

Cette fonctione ne retourne rien.

## Exemples

```c
public OnGameModeInit()
{
    // Autoriser les armes en intérieur.
    AllowInteriorWeapons(1);
    return 1;
}
```

## Notes

:::avertissement

Cette fonction ne fonctionne pas dans la version actuelle de SA:MP.

:::

## Fonctions Relatives

- [AreInteriorWeaponsAllowed](AreInteriorWeaponsAllowed): Retourne sur les armes sont autorisées en intérieur.
- [SetPlayerInterior](SetPlayerInterior): Définir l'intérieur d'un joueur.
- [GetPlayerInterior](GetPlayerInterior): Acquérir l'intérieur actuel d'un joueur.
- [OnPlayerInteriorChange](../callbacks/OnPlayerInteriorChange): Appelé quand un joueur change (ou est changé) d'intérieur.
