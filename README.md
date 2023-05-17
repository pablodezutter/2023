# 2023 Together we'll explore more...

# don't forget if you're done in python type exit()
#Maak een txt file in de folder waar je bent
open('new.txt','x')
#Zet meer tekst in het bestand
f= open('new.txt','a')
f.write('Now the file has more content')

#Open het bestand en geef de tekst weer
 f= open('new.txt','r')
 print(f.read())
