# calcul-réseau
##### Le pôle qui a le plus grand nombre de machine est le Pôle Informatique, 50 équipements, 2^6: 64-2=62  adresses. CIDR: 32-6=26 pour tout les pôles

## Symétrique
|  Pôles  | Pôle Informatique        |  Pôle Développement |  Pôle Technicien   |  Pôle Administration  |
|:---------------|---------------|---------------|-------------|------------:|
**Adresse du réseau**  | 172.16.1.0/26  |  172.16.1.64/26  |  172.16.1.128/26  |  172.16.1.192/26  |
**Début IP***  | 172.16.1.1/26  | 172.16.1.65/26  |  172.16.1.129/26  |  172.16.1.193/26  |  
**Fin IP** | 172.16.1.62/26  |  172.16.1.126/26  |  172.16.1.190/26  |  172.16.1.254/26  |
**Broadcast**  | 192.16.1.63/26  |  172.16.1.127/26  |  172.16.1.191/26  |  172.16.1.255/26  |

## Asymétrique

##### Pôle informatique : 50 équipements, 2^6: 64-2=62  adresses. CIDR: 32-6=26
##### Pôle administratif : 20 équipements, 2^5: 32-2=30 adresses CIDR: 32-5=27
##### Pôle technicien : 15 équipements, 2^4: 16-2=14 adresses. CIDR: 32-4=28
##### Pôle développement : 12 équipements, 2^4: 16-2=14 adresses. CIDR: 32-4=28


|  Pôles | Pôle Informatique        |  Pôle Administration |  Pôle Technicien   |  Pôle Développement  |
|:---------------|---------------|---------------|-------------|------------:|
**Adresse du réseau**  | 172.16.1.0/26  |  172.16.1.64/27  |  172.16.1.96/28  |  172.16.1.116/28  |
**Début IP***  | 172.16.1.1/26  | 172.16.1.65/27  |  172.16.1.97/28  |  172.16.1.117/28  |
**Fin IP** | 172.16.1.62/26  |  172.16.1.94/27  |  172.16.1.114/28  |  172.16.1.132/28  |
**Broadcast**  | 192.16.1.63/26  |  172.16.1.95/27  |  172.16.1.1115/28  |  172.16.1.133/28  |
