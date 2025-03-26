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
- [Light Dependent Resistor](https://components101.com/sites/default/files/component_datasheet/LDR%20Datasheet.pdf)

##### Hard Mode moduler:

- [Sparkfun 16x2 LCD Screen](https://learn.sparkfun.com/tutorials/basic-character-lcd-hookup-guide)
- [4x4 Keypad](https://www.electronicwings.com/arduino/4x4-keypad-interfacing-with-arduino-uno)
- [7-Segment Display](https://projecthub.arduino.cc/SAnwandter1/programming-4-digit-7-segment-led-display-5c4617)
- [GY-346 Accelerometer](https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Datasheet1.pdf)
- [BME280 Environment Sensor](https://cdn-shop.adafruit.com/datasheets/BST-BME280_DS001-10.pdf)
- [MQ-2 Gas Sensor](https://projecthub.arduino.cc/m_karim02/arduino-and-mq2-gas-sensor-f3ae33)
- [UV Sensor Module](https://projecthub.arduino.cc/d4visl/portable-and-rechargeable-ultraviolet-uv-radiation-meter-8ca087)
- [Adafruit LCD Screen](https://randomnerdtutorials.com/guide-for-oled-display-with-arduino/)
- [Spectra Flex](https://www.spectrasymbol.com/resistive-flex-sensors/spectraflex-flex-sensors)

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

### Superenkle prosjekter

1. **Blinkende LED**

   - Få LED-en på arduino boardet til å blinke med ulike hastigheter
   - [Eksempel Kode](https://www.arduino.cc/en/Tutorial/BuiltInExamples/Blink)

2. **Knapp med LED**

   - En trykknapp som skrur LEDen på arduino boardet på eller av
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

### Nybegynnernivå

1. **LED Trafikklys**

   - Bruk røde, gule og grønne LED-er for å simulere et trafikklys
   - Enkel sekvens med timere
   - [Eksempel Prosjekt](https://projecthub.arduino.cc/krishna_agarwal/traffic-light-using-arduino-a-beginner-project-35f8c6)

2. **Termometer**

   - Koble til en temperatursensor og vis temperaturen
   - Kan legge til LED-er for å indikere når det er for varmt/kaldt
   - [Eksempel Prosjekt](https://projecthub.arduino.cc/microst/active-sensor-thermometer-73b283)

3. **Automatisk Nattlys**

   - Bruk fotoresistor for å detektere mørke
   - Skru på LED-en automatisk når det blir mørkt
   - [Eksempel Prosjekt](https://projecthub.arduino.cc/DCamino/ambient-light-sensor-using-photo-resistor-and-led-lights-79c2ed)

4. **Enkel Alarm med Bevegelsessensor**
   - Bruk PIR-sensor for å oppdage bevegelse
   - Kan alternativt også gjøres ved bruk av en [HC-SR04](https://projecthub.arduino.cc/Isaac100/getting-started-with-the-hc-sr04-ultrasonic-sensor-7cabe1)
   - Utløs en buzzer eller LED når bevegelse oppdages
   - [Eksempel Prosjekt](https://projecthub.arduino.cc/BEASTIDREES62/diy-homemade-pir-alarm-system-with-arduino-c553fa)

### Mellomnivå

1. **Distansemåler med Ultralyd**

   - Bruk ultralydsensor for å måle avstand
   - LED eller summer som reagerer på avstandsendringer
   - [Eksempel Prosjekt](https://projecthub.arduino.cc/sumanskd/measure-distance-and-more-with-hc-sr04-ultrasonic-sensor-c61b3e)

2. **RGB LED-styring**

   - Bruk potentiometere eller knapper til å styre fargene på en RGB LED
   - Lær om fargeblanding og PWM
   - [Eksempel Prosjekt](https://roboticsbackend.com/arduino-control-rgb-led-with-potentiometer/)

3. **Musikk med Passive Buzzer**

   - Spill enkle melodier med en buzzer
   - Legg til knapper for å velge ulike melodier
   - [Eksempel Prosjekt](https://projecthub.arduino.cc/tmekinyan/playing-popular-songs-with-arduino-and-a-buzzer-546f4a)

### Litt mer utfordrende

1. **Servo Motor Styring**

   - Bruk potentiometer eller knapper for å kontrollere en servo
   - Kan brukes til å lage en enkel robotarm (eller hvertfall simulere en)
   - [Eksempel Prosjekt](https://docs.arduino.cc/learn/electronics/servo-motors/)

2. **Lys og Lyd Show**

   - Kombiner LED-er og buzzer for å lage et synkronisert lys- og lydshow
   - Legg til knapper for å velge ulike mønstre/melodier
   - [Eksempel Prosjekt](https://projecthub.arduino.cc/samfrits11/led-lightshow-f9dd80)

3. **Enkel Værmelding**

   - Bruk temperatur-, fuktighets- og trykkmoduler
   - Vis informasjon på en LCD-skjerm eller med LED-indikatorer
   - [Eksempel Prosjekt](https://projecthub.arduino.cc/rajeshjiet/iot-based-weather-monitoring-system-using-arduino-a3334a)

   ## 💡 Tips for vellykkede prosjekter på kort tid

4. **Start enkelt og bygg videre**

   - Få en enkeltstående funksjon til å virke før du legger til flere
   - For eksempel, få én LED til å lyse før du prøver å kontrollere flere

5. **Test underveis**

   - Test koden din ofte, etter hver lille endring
   - Dette gjør det lettere å finne eventuelle feil

6. **Bruk biblioteker**

   - Arduino-biblioteker kan spare mye tid og kode
   - Sjekk hvilke biblioteker som finnes for modulene du bruker

7. **Prioriter funksjonalitet over estetikk**

   - Få prosjektet til å fungere først, gjør det pent senere hvis det er tid

8. **Be om hjelp tidlig**
   - Ikke sitt fast for lenge med samme problem
   - Spør mentorer om hjelp hvis du er usikker

Husk at dette er en kodekveld for å lære og ha det gøy. Det viktigste er ikke å lage det mest avanserte prosjektet, men å fullføre noe du er stolt av!

## 📹 Videoveiledninger

- [Arduino Crashkurs for Nybegynnere (Engelsk)](https://www.youtube.com/watch?v=1R3fqSFCAjM)
- [Hvordan bruke Vanlige Sensorer med Arduino (Engelsk)](https://www.youtube.com/watch?v=SHkFzXOpvT8)
- [Arduino Prosjekt Beste Praksis (Engelsk)](https://www.youtube.com/watch?v=P768C2d8C4I)
- [Paul McWhorter's Arduino Tutorials (Engelsk)](https://www.youtube.com/playlist?list=PLGs0VKk2DiYw-L-RibttcvK-WBZm8WLEP)

## 📘 Online Fellesskap og Forumer

- [Arduino Forum](https://forum.arduino.cc/)
- [Arduino Stack Exchange](https://arduino.stackexchange.com/)
- [r/arduino på Reddit](https://www.reddit.com/r/arduino/)
