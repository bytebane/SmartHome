# SmartHome

## SmartHome Starter-Kit

This is a Hobby Project, actively used(personally) in my home every day since past 2 years (and it works like a charm NGL. Does exactly what its supposed to 😊). And is bug free mostly🫠  

- [Android App/Kotlin]()
- [ESP32/Arduino-C++]()


### Components Used: 
- 1x ESP32 DevKitC V4
- 2x 4 Channel Relay active-low i.e., input LOW=Relay_ON & HIGH=Relay_OFF
- 2x HiLink (HLK-PM01)
- Fan Speed Control Circuit
  - Capacitors
    - 1 uF
    - 2.2 uF
    - 3.3 uF
  - Resistors
    - 1 M Ohm
    - 330 Ohm 

Add Manual Switch -- With normal 5v Relay, the simplest way to add manual switch would be to add a three-way switch, connect one end to NO and the other end to NC terminal of the relay. This way all the appliances can be manually controlled even in case of any errors, short-circuits or power failures in the Microcontroller or relay.
