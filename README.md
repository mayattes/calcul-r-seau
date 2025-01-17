# calcul-réseau

-Pôle informatique : 50 équipements + 2 → 64 adresses.
-Pôle développement : 12 équipements + 2 → 16 adresses. 
-Pôle administratif : 20 équipements + 2 → 32 adresses.
-Pôle technicien : 15 équipements + 2 → 16 adresses.

## Symétrique
|  Informations  | Pôle Informatique        |  Pôle Développement |  Pôle Technicien   |  Pôle Administration  |
|:---------------|---------------|---------------|-------------|------------:|
**Nombre de Machine**  | 50 |  12  |  15  |  20  |
**Adresse du réseau**  | 172.16.1.0/26  |  172.16.1.54/27  |  172.16.1.68/28  |  172.16.1.85/28  |
**Début IP***  | 172.16.1.1/26  | 172.16.1.55/27  |  172.16.1.69/28  |  172.16.1.86/28  |  
**Fin IP** | 172.16.1.50/26  |  172.16.1.66/27  |  172.16.1.83/28  |  172.16.1.105/28  |
**Broadcast**  | 192.16.1.52/26  |  172.16.1.67/27  |  172.16.1.84/28  |  172.16.1.106/28  |


## Asymétrique
|  Informations | Pôle Informatique        |  Pôle Administration |  Pôle Technicien   |  Pôle Développement  |
|:---------------|---------------|---------------|-------------|------------:|
**Nombre de Machine**  | 50 |  20  |  15  |  12  |
**Adresse du réseau**  | 172.16.1.0/26  |  172.16.1.53/27  |  172.16.1.75/28  |  172.16.1.92/28  |
**Début IP***  | 172.16.1.1/26  | 172.16.1.54/27  |  172.16.1.76/28  |  172.16.1.94/28  |
**Fin IP** | 172.16.1.50/26  |  172.16.1.73/27  |  172.16.1.90/28  |  172.16.1.104/28  |
**Broadcast**  | 192.16.1.52/26  |  172.16.1.74/27  |  172.16.1.91/28  |  172.16.1.105/28  |
