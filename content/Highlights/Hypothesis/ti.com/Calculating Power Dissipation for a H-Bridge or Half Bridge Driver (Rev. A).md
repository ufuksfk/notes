---
doc_type: hypothesis-highlights
url: 'https://www.ti.com/lit/an/slva504a/slva504a.pdf'
---

# Calculating Power Dissipation for a H-Bridge or Half Bridge Driver (Rev. A)

## Metadata
- Author: [ti.com]()
- Title: Calculating Power Dissipation for a H-Bridge or Half Bridge Driver (Rev. A)
- Reference: https://www.ti.com/lit/an/slva504a/slva504a.pdf
- Category: #article

## Page Notes
## Highlights
- [[2023-10-10]] 13:15 Power dissipation due to output slewing during rising and falling edges is given by:PSW1 [W] = (0.5 x VM x IL x VM / SRrise x fPWM) + (0.5 x VM x IL x VM / SRfall x fPWM), where, (2)i. fPWM = PWM switching frequency [Hz]ii. VM = Supply voltage to the driver [V]iii. IL = Load current [A]iv. SRrise = Output voltage slew rate during rise [V/sec]v. SRfall = Output voltage slew rate during fall [V/sec]Output slewing rate is a balance between EM (Electro magnetic) performance and device powerdissipation. — [original](https://hyp.is/VvUNKGdeEe681XN4TuuBUQ/www.ti.com/lit/an/slva504a/slva504a.pdf)
    -   #electronics/power-dissipation 
    - power dissipation due to output slewing

- [[2023-10-10]] 13:15 Power dissipation from conduction loss of each FET due to its on-resistance is given by:PRON [W] = RON × IL2, where, (1)a. RON = FET on-resistance [ohm]b. IL = Load current [A] — [original](https://hyp.is/IyBp1GdeEe6pIhfVY5XXow/www.ti.com/lit/an/slva504a/slva504a.pdf)
    -   #electronics/power-dissipation 
    - power dissipation from conduction loss

- [[2023-10-10]] 13:16 Power dissipation due to the dead times between switching FETs is given by:PSW2 [W] = (VD x IL x tDEADrisex fPWM) + (VD x IL x tDEADfallx fPWM), where, (3)i. fPWM = PWM switching frequency [Hz]ii. VD = FET body diode forward bias voltage [V]iii. IL = Load current [A]iv. tDEADrise = dead time during rise [sec]v. tDEADfall = dead time during fall [sec]Dead times are necessary to mitigate any risk of current shoot through between the switching powerFETs. Integrated FET drivers often have a feedback based self timed FET switching sequence to ensurethe smallest possible dead times while avoiding any shoot through current. — [original](https://hyp.is/Y6WKIGdeEe6gmoebH3JW0w/www.ti.com/lit/an/slva504a/slva504a.pdf)
    -   #electronics/power-dissipation 


- [[2023-10-10]] 13:17 Power dissipation due to OUTPUT slewing during FET turn ON in the recirculation path is given by:PSW3 [W] = (0.5 x VD x IL x VD / SRrise x fPWM) + (0.5 x VD x IL x VD / SRfall x fPWM), where, (4)i. fPWM = PWM switching frequency [Hz]ii. VD = FET body diode forward bias voltage [V]iii. IL = Load current [A]iv. SRrise = Output voltage slew rate during rise [V/sec]v. SRfall = Output voltage slew rate during fall [V/sec]This dissipation is typically not considered as it is quite insignificant. — [original](https://hyp.is/nV8W3GdeEe69XZsWV0pECA/www.ti.com/lit/an/slva504a/slva504a.pdf)
    -   #electronics/power-dissipation 




