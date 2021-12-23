

# TP 

Combien de fois le client avec une adresse ip commencant par 198, 
a acceder au serveur pour voir le logo.png => 

# Client 

Le nombre de client qui ont acceder au serveur avec un mozzila firefox

# Client connectes 
Le nombre de client connectes au serveur
`cut -d ' ' -f 1 file | sort -u | wc -l`

# Client connectes par interval de temps
Le nombre de client connectes au serveur de 08-12h
`grep -E '2021:0[8-9]: | 1[0-1]:[0-5][0-9]:[0-5][0-9] | 2021:12:00:00' file`
