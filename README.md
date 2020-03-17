# CoronavirusDoorbell
Arduino Doorbell with hidden IR temperature sensor to detect high fever

Using airports method, scan your home visitors body temperature as soon as they ring the bell using IR remote temperature. If body temperature is normal ring the bell, otherwise an alarm will appear.

Circuit at https://www.hackster.io/roni-bandini/coronavirus-doorbell-114b3f

3d Printed Case at https://www.thingiverse.com/thing:4224148

*** Sounds
You need to place 2 sounds 01.mp3 and 02.mp3 into /00 folder in the microSD card
01.mp3 should be the doorbell and 02.mp3 should be the alarm.

*** IR thermometer theory
Everything that has mass emits energy in the form of heat. Since there is heat being emitted by any object or person, an infrared thermometer can use the difference between the IR rays coming off of the person and the surrounding environment to determine temperature of the person itself.

The IR thermometer works by focusing light that is coming from the object in the form of IR rays and funneling that light into a thermopile. In the thermopile IR radiation is turned into heat, which is then turned to electricity, which is then measured.

The entire process starts with a doorbell button pressed. At that point, a hidden IR thermometer measures body temperature, the temperature is displayed in the 7 segment display screen and compared with standard fever temperatures. If visitor body has no temperature, the doorbell will ring, otherwise an alarm will alert you about a potentially infected visitor.

*** Important
High fever may have lots of causes. Consider also that there are asymptomatic infected people and incubation periods.

https://www.instagram.com/ronibandini/ 
https://twitter.com/RoniBandini
