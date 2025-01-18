# calcul-réseau

-Pôle informatique : 50 équipements + 2 → 64 adresses.
-Pôle développement : 12 équipements + 2 → 16 adresses. 
-Pôle administratif : 20 équipements + 2 → 32 adresses.
-Pôle technicien : 15 équipements + 2 → 16 adresses.

## Symétrique
|  Pôles  | Pôle Informatique        |  Pôle Développement |  Pôle Technicien   |  Pôle Administration  |
|:---------------|---------------|---------------|-------------|------------:|
**Adresse du réseau**  | 172.16.1.0/26  |  172.16.1.54/27  |  172.16.1.68/28  |  172.16.1.85/28  |
**Début IP***  | 172.16.1.1/26  | 172.16.1.55/27  |  172.16.1.69/28  |  172.16.1.86/28  |  
**Fin IP** | 172.16.1.50/26  |  172.16.1.66/27  |  172.16.1.83/28  |  172.16.1.105/28  |
**Broadcast**  | 192.16.1.52/26  |  172.16.1.67/27  |  172.16.1.84/28  |  172.16.1.106/28  |


## Asymétrique
|  Pôles | Pôle Informatique        |  Pôle Administration |  Pôle Technicien   |  Pôle Développement  |
|:---------------|---------------|---------------|-------------|------------:|
**Adresse du réseau**  | 172.16.1.0/26  |  172.16.1.64/27  |  172.16.1.116/28  |  172.16.1.103/28  |
**Début IP***  | 172.16.1.1/26  | 172.16.1.65/27  |  172.16.1.99/28  |  172.16.1.117/28  |
**Fin IP** | 172.16.1.562/26  |  172.16.1.96/27  |  172.16.1.114/28  |  172.16.1.132/28  |
**Broadcast**  | 192.16.1.63/26  |  172.16.1.97/27  |  172.16.1.1115/28  |  172.16.1.133/28  |
