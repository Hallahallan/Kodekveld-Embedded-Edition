# Ressurser og Datasheets

Dette dokumentet inneholder nyttige ressurser, datasheets og inspirasjon til prosjekter som kan være til stor hjelp under hackathonen.

## 📚 Datasheets

### Sensorer og Moduler

#### Denne inneholder de aller fleste basismoduler tilgjengelig:

- [Kjell & Company Large Sensor Kit](https://www.kjell.com/globalassets/mediaassets/768118_87291_datasheet_en.pdf?ref=FBF87146FA)

#### Modulspesifikke datasheets:

##### Vanlige moduler:
- [DHT11 Temperature & Humidity Sensor](https://components101.com/sites/default/files/component_datasheet/DHT11-Temperature-Sensor.pdf)
- [PIR Motion Sensor](https://cdn-learn.adafruit.com/downloads/pdf/pir-passive-infrared-proximity-motion-sensor.pdf)
- [Joystick Module](https://components101.com/sites/default/files/component_datasheet/Joystick%20Module.pdf)
- [BMP280 Pressure Sensor](https://cdn-shop.adafruit.com/datasheets/BST-BMP280-DS001-11.pdf)
- [Ultrasonic Distance Sensor HC-SR04](https://cdn.sparkfun.com/datasheets/Sensors/Proximity/HCSR04.pdf)
- [IR Receiver Module](https://www.sparkfun.com/datasheets/Sensors/Infrared/tsop382.pdf)
- [Flame Sensor Module](https://components101.com/sites/default/files/component_datasheet/Flame-Sensor-Module.pdf)
- [Hall Effect Sensor](https://components101.com/sites/default/files/component_datasheet/A3144-Hall-Effect-Sensor.pdf)
- [Light Dependent Resistor](https://components101.com/sites/default/files/component_datasheet/LDR%20Datasheet.pdf)

##### Hard Mode moduler:
- [Sparkfun 16x2 LCD Screen](https://cdn.sparkfun.com/datasheets/LCD/Monochrome/ADM1602K-NSW-FBS-3.3v.pdf)
- [4x4 Keypad](https://cdn.sparkfun.com/datasheets/Components/Switches/keypad.pdf)
- [7-Segment Display](https://www.sparkfun.com/datasheets/Components/LED/7-Segment/YSD-439AB4B-35.pdf)
- [GY-346 Accelerometer](https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Datasheet1.pdf)
- [BME280 Environment Sensor](https://cdn-shop.adafruit.com/datasheets/BST-BME280_DS001-10.pdf)
- [MQ-2 Gas Sensor](https://www.pololu.com/file/0J309/MQ2.pdf)
- [UV Sensor Module](https://cdn.sparkfun.com/assets/learn_tutorials/2/0/6/GUVA-S12SD_DataSheet20150519.pdf)
- [Adafruit LCD Screen](https://cdn-shop.adafruit.com/datasheets/TC1602A-01T.pdf)
- [IR Remote Control](https://cdn.sparkfun.com/datasheets/Sensors/Infrared/tsop382.pdf)
- [Spectra Flex](https://cdn-shop.adafruit.com/datasheets/SpectraSymbol-Flex-Sensor-DJ1-118A-L004.pdf)

### Arduino Uno R4 Minima

- [Arduino Uno R4 Minima Dokumentasjon](https://docs.arduino.cc/hardware/uno-r4-minima/)
- [Arduino Uno R4 Minima Pinout Diagram](https://docs.arduino.cc/resources/pinouts/ABX00080-full-pinout.pdf)

## 🧠 Læringsressurser

### Arduino Grunnleggende

- [Arduino Offisielle Veiledninger](https://www.arduino.cc/en/Tutorial/HomePage)
- [Arduino Språkreferanse](https://www.arduino.cc/reference/en/)
- [SparkFun Arduino Veiledninger](https://learn.sparkfun.com/tutorials/tags/arduino)
- [Adafruit Arduino Veiledninger](https://learn.adafruit.com/category/learn-arduino)

### Kretsdesign

- [Fritzing](https://fritzing.org/) - For å lage kretsdiagrammer
- [Tinkercad Circuits](https://www.tinkercad.com/learn/circuits) - For å simulere Arduino-kretser

## 🎨 Inspirasjonsprosjekter

### Superenkle prosjekter (15-30 minutter)

1. **Blinkende LED**
   - Bare koble en LED med motstand til en digital pin
   - Få LED-en til å blinke med ulike hastigheter
   - [Eksempel Kode](https://www.arduino.cc/en/Tutorial/BuiltInExamples/Blink)

2. **Knapp med LED**
   - En trykknapp som skrur en LED på eller av
   - Perfekt første interaktive prosjekt
   - [Eksempel Kode](https://www.arduino.cc/en/Tutorial/BuiltInExamples/Button)

3. **Lysregulering med Potentiometer**
   - Bruk en potentiometer til å kontrollere lysstyrken på en LED
   - Introduserer analogRead() og analogWrite()
   - [Eksempel Kode](https://www.arduino.cc/en/Tutorial/BuiltInExamples/AnalogReadSerial)

4. **Tone Generator**
   - Bruk en buzzer for å spille ulike toner
   - Kan utvides med knapper for forskjellige toner
   - [Eksempel Kode](https://www.arduino.cc/en/Tutorial/BuiltInExamples/toneMelody)

### Nybegynnernivå (30-60 minutter)

1. **LED Trafikklys**
   - Bruk røde, gule og grønne LED-er for å simulere et trafikklys
   - Enkel sekvens med timere
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/techno_z/arduino-traffic-light-simulator-2ec9ae)

2. **Termometer**
   - Koble til en temperatursensor og vis temperaturen
   - Kan legge til LED-er for å indikere når det er for varmt/kaldt
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/pibots/how-to-make-arduino-thermometer-d9ee65)

3. **Lysavhengig Nattlys**
   - Bruk fotoresistor for å detektere mørke
   - Skru på LED-en automatisk når det blir mørkt
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/SBR/automatic-night-lamp-using-ldr-and-arduino-uno-799eb4)

4. **Enkel Alarm med Bevegelsessensor**
   - Bruk PIR-sensor for å oppdage bevegelse
   - Utløs en buzzer eller LED når bevegelse oppdages
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/electronicsfan123/pir-motion-sensor-with-arduino-fd540a)

### Mellomnivå (1-2 timer)

1. **Distansemåler med Ultralyd**
   - Bruk ultralydsensor for å måle avstand
   - LED eller summer som reagerer på avstandsendringer
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/abdularbi17/ultrasonic-sensor-hc-sr04-with-arduino-tutorial-327ff6)

2. **RGB LED-styring**
   - Bruk potentiometere eller knapper til å styre fargene på en RGB LED
   - Lær om fargeblanding og PWM
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/muhammad-aqib/arduino-rgb-led-tutorial-fc003e)

3. **Musikk med Passive Buzzer**
   - Spill enkle melodier med en buzzer
   - Legg til knapper for å velge ulike melodier
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/jrance/super-mario-theme-song-w-piezo-buzzer-and-arduino-1cc2e4)

4. **Digital Terning**
   - Lag en digital terning med 7-segment display eller LED-er
   - Kast terningen ved å trykke på en knapp
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/Arnov_Sharma_makes/led-dice-using-arduino-26b779)

### Litt mer utfordrende (for de raske)

1. **Tilt-aktivert LED-matrise**
   - Bruk en tilt-sensor til å kontrollere et mønster av LED-er
   - Bra for å lære grunnleggende om sensorinput
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/building-arduino-robots/tilt-sensor-project-073c9d)

2. **Servo Motor Styring**
   - Bruk potentiometer eller knapper for å kontrollere en servo
   - Kan brukes til å lage en enkel robotarm
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/instructables/sweeping-a-servo-motor-using-an-arduino-36d61a)

3. **Lys og Lyd Show**
   - Kombiner LED-er og buzzer for å lage et synkronisert lys- og lydshow
   - Legg til knapper for å velge ulike mønstre/melodier
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/techmirtz/arduino-led-and-music-show-6d7c13)

4. **Enkel Værmelding**
   - Bruk temperatur-, fuktighets- og trykkmoduler
   - Vis informasjon på en LCD-skjerm eller med LED-indikatorer
   - [Eksempel Prosjekt](https://create.arduino.cc/projecthub/techno_z/diy-arduino-weather-station-d32f2e)

## 📹 Videoveiledninger

- [Arduino Crashkurs for Nybegynnere (Engelsk)](https://www.youtube.com/watch?v=1R3fqSFCAjM)
- [Hvordan bruke Vanlige Sensorer med Arduino (Engelsk)](https://www.youtube.com/watch?v=SHkFzXOpvT8)
- [Arduino Prosjekt Beste Praksis (Engelsk)](https://www.youtube.com/watch?v=P768C2d8C4I)
- [Paul McWhorter's Arduino Tutorials (Engelsk)](https://www.youtube.com/playlist?list=PLGs0VKk2DiYw-L-RibttcvK-WBZm8WLEP)

## 📘 Online Fellesskap og Forumer

- [Arduino Forum](https://forum.arduino.cc/)
- [Arduino Stack Exchange](https://arduino.stackexchange.com/)
- [r/arduino på Reddit](https://www.reddit.com/r/arduino/)

## 💡 Tips for vellykkede prosjekter på kort tid

1. **Start enkelt og bygg videre**
   - Få en enkeltstående funksjon til å virke før du legger til flere
   - For eksempel, få én LED til å lyse før du prøver å kontrollere flere

2. **Test underveis**
   - Test koden din ofte, etter hver lille endring
   - Dette gjør det lettere å finne eventuelle feil

3. **Bruk biblioteker**
   - Arduino-biblioteker kan spare mye tid og kode
   - Sjekk hvilke biblioteker som finnes for modulene du bruker

4. **Prioriter funksjonalitet over estetikk**
   - Få prosjektet til å fungere først, gjør det pent senere hvis det er tid

5. **Be om hjelp tidlig**
   - Ikke sitt fast for lenge med samme problem
   - Spør mentorer om hjelp hvis du er usikker

Husk at dette er en hackathon for å lære og ha det gøy. Det viktigste er ikke å lage det mest avanserte prosjektet, men å fullføre noe du er stolt av!
