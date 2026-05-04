# TP-STP-README.md
# TP STP – Spanning Tree Protocol

## Objectif

Comprendre le rôle du protocole STP dans la prévention des boucles réseau.

## Contexte

Dans un réseau avec plusieurs switches et des liens redondants, des boucles peuvent apparaître.  
Ces boucles peuvent provoquer une tempête de broadcast.

STP bloque automatiquement certains ports pour créer une topologie logique sans boucle.

## Notions étudiées

- Root Bridge
- Root Port
- Designated Port
- Alternate Port
- Blocking
- Forwarding
- Tempête de broadcast

## Commandes principales

```bash
show spanning-tree
