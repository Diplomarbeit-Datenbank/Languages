# Languages
![image](https://user-images.githubusercontent.com/87471423/127821136-d2b1f932-1cad-4690-b0c0-3d8dbe353dad.png)

Eine Library, um am tkinter Fenster und im Terminal mehr als eine Sprache darzustellen

## Funktionen:
    o Ausgabe präzieser Warnungen und Fehler bei verwendung der Library
    o Ermöglicht es durch die Funktion refactor() strings in andere Sprachen zu konvertieren
    o Einfache ausbesserung von Rechtschreibfehlern durch änderung des text Dokumentes
    o Einfaches hinzufügen weiterer Sprachen

## Benötigte Librarys:
    o inspect:        -> Für genaue angabe der Zeile, aus der die angegebene Warnung entspringt
                      -> pip install inspect
    o termcolor:      -> Für angabe der Warnungen in gelb auf der Konsolo und rot für Fehler
                      -> pip install termcolor
    o Encode_umlauts: -> Für auslesen von Umlauten aus einem Text Dokument
                      -> Beschreibung unter follgendem Link: https://github.com/Diplomarbeit-Datenbank/Encode_Umlauts

## Verwendung:
    -> Einfach starten des main Programms im File: languages.py und schon hat man ein
       ausführliches beispiel der Funktionen parat.
    
    Main:
    
    def main():
    """
    : this is only to test the software
    """
    lang = Language('example_text_file.txt', language='german')
    print(lang.refactor_data)
    print(lang.refactor('sun'))

    return 0
    
                      
    
