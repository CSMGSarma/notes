Here is the spell-checked version of your text:

# Wireless Power Transfer

## What's this?
> When current flows through a wire, a magnetic field is induced around it.

[Oersted's Law](https://www.scienceworld.ca/resource/oersteds-experiment/#:~:text=The%20magnetic%20field%20created%20by,in%20circles%20around%20the%20wire.)

> When a conductor enters a magnetic field, current flows through the conductor.

[Faraday's Law of Electromagnetic Induction](https://www.khanacademy.org/science/ap-physics-2/ap-magnetic-forces-and-magnetic-fields/ap-magnetic-flux-faradays-law/v/lenzs-law#:~:text=Lenz's%20law%20tells%20us%20that,the%20change%20in%20magnetic%20flux.)

These are the principles of inductive power transfer, or famously known as *wireless power transfer*. For Wireless Power Transfer (`WPT`), all you have to do is control the current running in one coil (also called *transmitter coil* or **Tx Coil**), which controls the magnetic field around it, which in turn controls the induced current in the second coil (also called *receiver coil* or **Rx Coil**).

Is it really this simple? YES! It is! The real-world use case scenarios of WPT are simple and yet very effective and scalable. This is the reason for the growth of WPT devices and applications.

Imagine the use case where a wireless charger has the Tx Coil and the mobile phone has the receiver coil. [This is one of the most common applications of WPT]. When the Rx comes into the field of influence (the region where the induced magnetic field from the Tx coil can influence a magnetic material), the Rx gets a current induced, and this current can be used to charge the mobile battery.

There are many mobile phone vendors in the world. Each has a different battery type and different charging properties. Hence, the Tx should be capable of knowing the mobile battery's power requirements. This is possible if the Rx and Tx communicate. The WPT (also called `Qi`) protocol defines the communication between Tx and Rx. The transmitter uses ASK (Amplitude Shift Keying) for transmitting its data at a bit rate of 4 milliseconds. The receiver uses FSK (Frequency Shift Keying) at a bit rate of 4 microseconds.

Now imagine that if an unintended metal object with magnetic properties (say a hair clip, a coin, or a paper clip) comes into the region of Tx influence, these objects experience a rise in temperature as a means to dissipate the electrical energy (loss of energy). Such unintended objects are called foreign objects [FO]. FO detection or `FOD` is a very interesting component of WPT.
