# 2020-2021_DemoGit

My New Project

Contact : [ArnauldDev](biganzol@insa-toulouse.fr)

---

## TODO Git

- [x] Ajouter de nouveaux fichiers
- [x] Les ajouter à l'index de suivi
- [x] Faire un commit (en local sur mon PC)
- [x] Pousser le ou les commit vers le serveur
- [x] Créer une nouvelle branche
- [x] Basculer sur cette branche

### Arduino Project

[Communication > Serial](https://www.arduino.cc/reference/en/language/functions/communication/serial/)

[SerialEvent](https://www.arduino.cc/en/Tutorial/BuiltInExamples/SerialEvent)

```c++
// print the string when a newline arrives:
if (stringComplete)
{
    Serial.println(); // faire un saut de ligne entre les réponses
    Serial.print("Vous avez repondu ");
    Serial.println(inputString);
    // test de la réponse du joueur
    if (inputString == "kicad")
    {
        Serial.println("Go for a new PCB board!");
    }
    else
    {
        Serial.println("C'est pas tout a fait ca...");
    }
    // clear the string:
    inputString = "";
    stringComplete = false;
}

```

---

## Fabrication des circuits imprimés (PCB)

<iframe title="vimeo-player" src="https://player.vimeo.com/video/75387605" width="640" height="360" frameborder="0" allowfullscreen></iframe>

---

## TODO Concevoir une carte avec KiCad

- [x] Créer un projet de PCB pour réaliser une shield Arduino
- [x] Saisi du schéma
- [x] Vérification des tests électriques **ERC**
- [x] Association des empreintes de composants avec leur boitier
- [ ] Génération de la netlist

### Electrical diagram

![Schematic](Images/schematic.png)
