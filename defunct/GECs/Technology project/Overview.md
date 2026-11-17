## Research

### Figures, statistics, etc.
- Smoke is produced much earlier than other fire signals during fire growth and development stages so that smoke detectors can serve as appropriate fire safety devices. [https://www.sciencedirect.com/science/article/pii/S2214157X23012029#bib9]

- Smoke detectors use either photoelectric or ionization technology to detect fires. (or a combination of the two)
- [https://www.sciencedirect.com/science/article/pii/S2214157X23012029#bib9]

- In one test series, dual alarms activated 539 s faster than ionization alarms and 79 s faster than photoelectric alarms on average.[https://link.springer.com/article/10.1007/s10694-010-0147-z]

- In that test series, dual alarms, with individual sensor sensitivities equal to their counterpart alarm sensitivities, activated 261 s faster on average than ionization alarms, and 35 s faster on average than the photoelectric alarms. [https://link.springer.com/article/10.1007/s10694-010-0147-z]

- In cases where an ionization sensor was the first to reach the alarm threshold, the dual alarm activated 67 s faster on average than the photoelectric alarm. While in cases were a photoelectric sensor was the first to reach the alarm threshold, the dual alarm activated 523 s faster on average than the ionization alarm.[https://link.springer.com/article/10.1007/s10694-010-0147-z]

- While their basic response to different fires (selective detection) is well understood, (==ionization detectors being more responsive to flaming fires and photoelectrical detectors to smouldering fires==), a major issue remains as to the predictability of their response in real fire situations. [https://xtralis.com/file/582]

- <mark style="background: #FFB8EBA6;">ASD</mark> systems are increasingly being deployed in the protection of commercial and residential buildings. These systems actively draw samples from the protected area and, as such it is both logical and has been demonstrated that predictions of their response using CFD <mark style="background: #FFB8EBA6;">are significantly more accurate than with point type detectors.</mark> During the past 2 decades, ASD systems have been used in many challenging applications, such as large open spaces (LOS), high velocity environments (Cleanroom) and very early warning (VEW) detection required environment (IT&C).

- Smoke detectors: As smoke is normally present at an early stage in most fires, smoke detectors are considered the most useful type available for giving early warning. [https://www.thefpa.co.uk/resource-download/757]

- Smoke detectors provide a more rapid response to fires than heat detectors. Smoke detectors can detect the signs of fire before the development of deadly conditions.[https://nationaltrainingcenter.com/smoke-detectors/]


### Types of detector
Point detectors are the most common form of detector used for the protection of buildings and include:
• Smoke detectors
• Heat detectors
• Carbon monoxide detectors
• Flame detectors
• Combined multi-sensor detectors (combinations of the above in a single unit).
[https://www.thefpa.co.uk/resource-download/757]

#### Smoke detectors:
As smoke is normally present at an <mark style="background: #FFB8EBA6;">early stage in most fires</mark>, smoke detectors are considered the <mark style="background: #FFB8EBA6;">most useful</mark> type available for giving early warning. When smoke enters the chamber of the detector, the signal between an emitting source (radioactive or optical) and receiver, is reduced allowing detection

##### Types of smoke detectors: 
[https://nationaltrainingcenter.com/smoke-detectors/]
[https://firealarm.com/what-is-the-difference-between-line-type-and-spot-type-detectors/]
<mark style="background: #D2B3FFA6;">spot</mark>
- most common 
- all detections in a single location (single point in the room)
- suitable for most applications
- certain radius where it effectively detects fires

<mark style="background: #D2B3FFA6;">projected beam/linear</mark>
- detection over an area from point to point
- more suitable for large and open areas
- more expensive
- economically using linear detectors can save money, due to larger area.


<mark style="background: #D2B3FFA6;">air sampling</mark>
- uses tubing to pull air from detection areas and then to a sensing chamber
- suitable for high-sensitivity smoke detection
--------------
<mark style="background: #FF5582A6;">Ionization Smoke Detector</mark>
Ionization smoke detectors use a small amount of radioactive material (typically Americium-241), which emits alpha particles to ionize air in a sensing chamber. The ionized air allows current flow between two charged plates, and the detector monitors this current flow using a galvanometer. When smoke enters the chamber, it attaches to the ionized particles and reduces the current flow between the two plates. If the current flow drops low enough, the detector goes into alarm.

- not commonly used in fire alarm systems today
- false alarms
- can detect early
- like theyre kinda dangerous and please dont use them

<mark style="background: #FF5582A6;">Photoelectric Smoke Detectors</mark>
- most common type of smoke detection
- less false alarms
- spot-type and beam-type detection.


#### Heat detectors:
<mark style="background: #FFB8EBA6;">Most fires, in their later stages, emit detectable levels of heat</mark>. Therefore, in areas where rapid <mark style="background: #FFB8EBA6;">fire spread is unlikely</mark> and environmental conditions preclude the use of smoke detectors (such as kitchens), heat detectors are a common alternative.

#### Carbon monoxide detectors:
Fires tend to produce carbon monoxide in situations in which there is insufficient ventilation to enable fire to burn rapidly and as such the detector is well suited to provide <mark style="background: #FFB8EBA6;">early warning of slow smouldering fires</mark>. Slowly developing and smouldering fires produce large quantities of carbon monoxide before detectable smoke aerosols and particulates reach smoke detectors in sufficient quantities to detect the fire. <mark style="background: #FFB8EBA6;">These detectors can often be used in applications in which heat detectors are insufficiently sensitive</mark>, but smoke detectors may cause <mark style="background: #FFB8EBA6;">false alarms</mark> from sources such as steam from a shower or smoke from burnt toast.

#### Flame detectors: 
In situations where a <mark style="background: #FFB8EBA6;">burning liquid</mark>, for example alcohol, paint thinner etc. is likely to be the prime source of a fire, and <mark style="background: #FFB8EBA6;">flame is most likely to be the first indication a fire has started</mark>, then an infrared (IR) or ultra-violet (UV) flame detector could be incorporated into the system. IR is detected in a bandwidth appropriate to hot carbon dioxide molecules, a by-product of combustion.


# Project

### Prerequisites
- NTC Thermistor, as an increase in temperature decreases resistance, thus allowing the flow of electricity.
- 9V battery, possibly a way to connect it to main?
- Buzzer, preferably above 95dB
- Comparator IC: binary output if above the set temperature
- Potentiometer, pref 10k ohm: sets the temperature threshold
- Resistors, preferably 10k Ohm