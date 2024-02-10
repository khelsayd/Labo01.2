# Cycle de vie du logiciel #

## Description ##

## Implémentation ##
- codage / programmaion
- test
- analyse 
- conception

```mermaid
flowchart LR
    A(analyse fonctionnelle)
    C(conception)
    D(codage)
    T(test)

A --> C
C --> D
D --> T
```


## Source Control ##
La gestion du code source.
On utlise git, mais il y a d'autre systèmes (subversion, mercurial)


Le flux quand on développe:
```mermaid
flowchart LR
C(code)
R(local repository)
G(github)

C -- commit --> R
R -- push --> G


```

Mais avant il faut initier le repository:
