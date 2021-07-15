# Codebuch Spielerinnennetzwerk #

Codebuch Stand 2021- Juli
erstellt von Anina Kemmerling


## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der DatensÃ¤tze)

# EDGE-Attribute

**from**  
Definiert den Sender in gerichteten Netzwerken.
Entspricht id in der Nodelist.

**to**   
Definiert den Empfänger in ungerichteten Netzwerken.
Entspricht id in der Nodelist.

**relation* 
Definiert die Art der Beziehung zwischen den Knoten;
1 = Mitgliedschaft in Verein
2 = Herkunftsland


# NODE-Attribute  
  
**id**  
Eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.

**name**  
Name oder Bezeichnung des Knotens.
  
**type**    
Definiert, um welche Art von Knoten es sich handelt;
0 = Person,
1 = Organisation (wie Verein oder Land)


**birth**    
Definiert das Geburtsjahr. 

  
**age**  
Definiert das Alter der Spielerinnen;
1 = unter 20 Jahre alt,
2 = 20-23 Jahre alt,
3 = 24-26 Jahre alt,
4 = über 27 Jahre alt
  
**position**    
Definiert die Position der Spielerinnen auf dem Feld;
1 = Mittelblock,
2 = Zuspiel,
3 = Außenangriff,
4 = Diagonal,
5 = Libera

**country**  
Definiert die Herkunft der Spielerinnen;
1 = Deutschland,      
2 = Niederlande,   
3 = Bulgarien,    
4 = Belgien,  
5 = Polen,  
6 = Finnland,  
7 = USA
8 = Spanien

##
