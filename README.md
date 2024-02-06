# Password-door-lock-circuit-using-4017

## Story
In today’s article, we're diving into the realm of DIY electronics with a guide on crafting a password lock circuit. But here's the kicker – no Arduino required! Sounds intriguing, doesn't it? Let's delve into the specifics and explore the practical applications of this nifty circuit

## Components Required for the Circuit
Before we embark on our electronic escapade, let's gather our tools. For this project, we'll need the following components:

- CD 4017 IC
- 5V Relay
- Resistors: 1K * 2, 100K * 2, 470 Ohm's
- LEDs: 5mm * 2
- PCB Connector (Optional)
- 1N4007 Diode * 5
- Push Switch * 10
- BC547 Transistor

These components are readily available at your local electronics store or online. Now that we have our arsenal ready, let's dive into the workings of the circuit.

# Explanation of the Circuit
At the heart of our [circuit](https://www.diyelectronic.in/2024/02/blog-post_05.html) lies the CD4017 IC, orchestrating the sequence of events. The resistors and LEDs form a series, with the LED acting as an indicator. Upon power supply, the first LED illuminates, signifying the circuit's activation. Subsequently, the second LED lights up when the circuit is in the closed (ON) position, indicating successful unlocking.

The integration of diodes is crucial for circuit functionality. Four diodes are connected in series with push switches, while one diode runs parallel to the relay. Each push switch corresponds to a digit in the password.

# Setting the Password
Here's where the magic happens. By manipulating the diodes connected to the push switches, you can set your desired password. For instance, I've set mine to '3621'. Remember, each push switch corresponds to a single digit, and you cannot select two digits simultaneously.

# Warning and Safety Precautions
A word of caution: Safety first! When tinkering with electronics, always prioritize safety to prevent any mishaps.

# Applications of the Password-Based Lock
The versatility of this circuit is astounding. You can employ it as a password-based door lock or integrate it into a safe box. However, it's essential to acknowledge its limitations; this circuit is not foolproof for safeguarding valuables.

# PCB Design for Compact Elegance
For those seeking efficiency and elegance, customized PCB design is the way to go. [JLCPCB](https://jlcpcb.com/IUP) offers a seamless ordering experience, coupled with a $30 new user coupon code. Elevate your electronics project with precision and finesse.

# Conclusion
In conclusion, crafting a password lock circuit sans Arduino is a rewarding venture. Whether for showcasing at exhibitions or personal use, this circuit offers a glimpse into the realm of DIY electronics. Remember to exercise caution and unleash your creativity!

Checkout The [Video](https://www.youtube.com/watch?v=tg6mzerJnjA)
