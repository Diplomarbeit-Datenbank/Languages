# Languages
![image](https://user-images.githubusercontent.com/87471423/127837904-aa31c64f-ab59-4ca8-aef3-01c12f8b5212.png)



Eine Library, um am tkinter Fenster und im Terminal mehr als eine Sprache darzustellen

## Funktionen:
    o Ausgabe präziser Warnungen und Fehler bei Verwendung der Library
    o Ermöglicht es durch die Funktion refactor() strings in andere Sprachen zu konvertieren
    o Einfache Ausbesserung von Rechtschreibfehlern durch Änderung des Text Dokumentes
    o Einfaches hinzufügen weiterer Sprachen


## Benötigte Librarys:
    o inspect:        -> Für genaue Angabe der Zeile, aus der die angegebene Warnung entspringt
                      -> pip install inspect
    o termcolor:      -> Für angabe der Warnungen in Gelb auf der Konsole und rot für Fehler
                      -> pip install termcolor
    o Encode_umlauts: -> Für auslesen von Umlauten aus einem Text Dokument
                      -> Beschreibung unter folgendem Link: https://github.com/Diplomarbeit-Datenbank/Encode_Umlauts


## Entwickler Verwendung:
    -> Einfach starten des main Programms im File: languages.py und schon hat man ein
       ausführliches Beispiel der Funktionen parat.
    
    Main:
    
    def main():
        """
        : this is only to test the software
        """
        lang = Language('example_text_file.txt', language='german')
        print(lang.refactor_data)
        print(lang.refactor('sun'))

        return 0

## Eigenschaften:
    o Copyright Christof Haidegger
    o Erstellt von Christof Haidegger
    o Debugging von Christof Haidegger
    
    o Geschriebene Zeilen in Python-Code: 155
    o Geschriebene Zeilen in README-Code: 50
    
                      
    
