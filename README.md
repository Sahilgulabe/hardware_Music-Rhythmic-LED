🎵 Music Rhythmic LED
A simple and fun analog circuit that makes 8 LEDs dance and blink in sync with music or sound! No microcontroller needed — pure analog electronics powered by a transistor-based amplifier and driver circuit.

📌 What It Does
This project uses an Electret Microphone to pick up ambient sound or music. The sound signal is amplified through a BC547 NPN transistor amplifier stage, which then drives 8 LEDs in rhythm with the beat. The louder the sound, the more LEDs light up — creating a cool visual equalizer-like effect, all without any code or programming!
Perfect for:

Music visualizers
Party decorations
Learning analog transistor circuits
Electronics beginners


🛠️ Components Used
Breadboard - x 1
Electret Microphone - x 1
Transistor - (BC547) x 9 NPN TYPE 
Resistor -  (1M) x 1 
                      (10k) x 2
                      (22Ω) x 8
LED (Light Emitting Diode) - (Any Colours) x 8
Ceramic Disc Capacitor - (100nF) x 1
DC Switch - x 1
Battery - (9v) (with battery clipper) x 1 
Connecting Wires

⚙️ How It Works (Circuit Overview)
[Microphone] → [Amplifier Stage (BC547 + 1MΩ + 10kΩ + 100nF)]
                          ↓
              [8x LED Driver Transistors (BC547)]
                          ↓
              [8x LEDs with 22Ω current-limiting resistors]
                          ↓
                    [9V Battery]

Microphone captures sound and converts it to a small electrical signal.
First BC547 transistor (with 1MΩ bias resistor and 100nF capacitor) amplifies the weak mic signal.
The amplified signal drives 8 BC547 transistors, each connected to one LED.
Each LED has a 22Ω resistor in series to limit current and protect the LED.
The DC switch allows you to turn the circuit on/off easily.
