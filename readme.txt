Hi,

um gr��ere Dateien (z.B. PDFs, Fotos, was-auch-immer) pushen zu k�nnen muss man noch folgendes unter Eclipse einstellen:

Im Men� unter "Window" -> "Preferences" -> "Team" -> "Git" -> "Configuration":

"Add Entry" klicken und folgende Werte eintragen:

Key: http.postBuffer
Value: 524288000

Dann mit "Ok" best�tigen.

Gru�