# Distance-Finder

**Things Needed:**
<pre>
  You need the following software:
    Arduino IDE (for uploading code)
  --------------------------------------------------------------------------------------------------
  You need the following hardware:
    1x Arduino UNO / Nano
    1x LED bar-graph (10 LEDs)
    1x Ultrasonic distance sensor - HC-SR04
    1x I2C 16x02 LCD
    1x USB cable (for uploading code)
    1x 9V battery
    1x Switch
</pre>
__________________________________________________________________________________________________

**Hardware:**
<pre>
  LED bar-graph:
    LED1:
      Cathode: Arduino GND
      Anode: D2
    ----------------------------
    LED2:
      Cathode: Arduino GND
      Anode: D3
    ----------------------------
    LED3:
      Cathode: Arduino GND
      Anode: D4
    ----------------------------
    LED4:
      Cathode: Arduino GND
      Anode: D5
    ----------------------------
    LED5:
      Cathode: Arduino GND
      Anode: D6
    ----------------------------
    LED6:
      Cathode: Arduino GND
      Anode: D7
    ----------------------------
    LED7:
      Cathode: Arduino GND
      Anode: D8
    ----------------------------
    LED8:
      Cathode: Arduino GND
      Anode: D9
    ----------------------------
    LED9:
      Cathode: Arduino GND
      Anode: D12
    ----------------------------
    LED10:
      Cathode: Arduino GND
      Anode: D13
    ----------------------------
  --------------------------------------------------------------------------------------------------
  Ultrasonic Sensor:
    VCC: IOREF
    TRIG: D10
    ECHO: D11
    GND: GND
  --------------------------------------------------------------------------------------------------
  9V battery:
    Cathode: GND (arduino)
    Anode: T1 of switch
  ---------------------------------------------------------------------------------------------------
  Switch:
    T1: Battery Anode
    T2: Battery Cathode
    Wiper / Output: Arduino VIN
  ---------------------------------------------------------------------------------------------------
</pre>
__________________________________________________________________________________________________________________
