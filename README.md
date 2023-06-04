# Light-Blueprints

  # Lichtwecker 
   Einfacher Lichtwecker 
   Licht wird über einen definierten Zeitraum vom Min Helligkeitswert bis Max Helligkeitswert hoch gedimmt.
   Das Ausschaltten des Lichts  deaktiviert den Lichtwecker.
   Es werden zwei Helfer benöttigt.
   - Ein input_datetime -> Weckzeit
   - Ein input_boolean -> Zum aktivieren/ deaktivieren des Lichttweckers
   Die Zeit des Lichtweckers erechnet sich aus der Max Helligkeit - Min Helligkeit und der Verzögerung zwischen der Helligkeit Anpassung.
   Beispiel. Das Licht soll startend mit der Helligkeit 10 auf 200 in 30 min gedimmt werden. 200 - 20 = 180
   30*60 / 180  = 10. Dies  ergibt eine Verzögerung von 10s
   
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FSmartHomeForDummies%2FLight-Blueprints%2Fblob%2Fmain%2FLichtwecker.yaml)
    
  # Lichtwecker mit Farbtemperatur
   Licht wird über einen definierten Zeitraum vom Start Helligkeitswert bis Ziel Helligkeitswert hoch gedimmt.
   Eine gleichmässige Anpasung der Farbtemperatur erfolgt ebenfalls über die Zeit vom Start Wert zum Ziewert der Farbtemperatur.
   Ist dr Start Wert und der Ziel Wert der Farbtemperatur gleich. Bleibt die Farbtemperatur konstant.
   Für Lichter ohne Farbtemperatur kann diese deaktiviert werden.
   Das Ausschaltten des Lichts deaktiviert den Lichtwecker. 
   Es werden zwei Helfer benöttigt.
   - Ein input_datetime -> Weckzeit
   - Ein input_boolean -> Zum aktivieren/ deaktivieren des Lichttweckers
  
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FSmartHomeForDummies%2FLight-Blueprints%2Fblob%2Fmain%2FLichtwecker_mit_Farbtemperatur.yaml)
    
  # Lichtwecker mit Farbtemperatur und Sensor als Weckzeit
   Licht wird über einen definierten Zeitraum vom Start Helligkeitswert bis Ziel Helligkeitswert hoch gedimmt.
   Eine gleichmässige Anpasung der Farbtemperatur erfolgt ebenfalls über die Zeit vom Start Wert zum Ziewert der Farbtemperatur.
   Ist der Start Wert und der Ziel Wert der Farbtemperatur gleich. Bleibt die Farbtemperatur konstant.
   Für Lichter ohne Farbtemperatur kann diese deaktiviert werden.
   Das Ausschaltten des Lichts deaktiviert den Lichtwecker. 
   Es wird ein Datum & Uhrzeit Helfer (input_datetime) oder ein Sensor mit Datum & Uhrzeit mit der Device Class timestamp benötigt,
   der den Start des Lichtweckers definiert.
   
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FSmartHomeForDummies%2FLight-Blueprints%2Fblob%2Fmain%2FLichtwecker_mit_Farbtemperatur_und_Sensor_als_Weckzeit.yaml)


### SmarHome for Dummies Community Diskussion

[![SmarHome for Dummies Community Diskussion](https://community.smarthome-for-dummies.de/styles/black_darkblue/theme/images/logo_hd.png)
](https://community.smarthome-for-dummies.de/viewtopic.php?t=689)
-----
[![Donate with PayPal](https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-200px.png)
](https://community.smarthome-for-dummies.de/donate)

