<B># VescBot</B>
<img width="422" height="422" alt="083239c2-104b-4299-9195-f00c76143a7c (1)" src="https://github.com/user-attachments/assets/04fbe1b4-b95c-4452-85cb-a4d28399f9af" />

<CENTER><B>Ninebot &lt;> VESC Bridge without Lisp scripting</B></CENTER><BR>

<BR>
<BR>


What we´ve got:
<BR>

Ninebot G30: 
Dashboard: 100% (Throttle & Brake (Halls), Akku%, Speed km/h, Light On/Off, Button Logic)

                 (BB4T Safety 0.1b Brake before Throttle ,
                 if both pressed at the same time. 
                 Communication Error Safety Lockout)
                
                 (SoC BMS Readout or Fixed Cell # or Auto Ranging)
                 
BMS      : 100% SoC See Update: 05-Nov-2025-21:51h
Ported   : 100% Payload (incl. Hearbeat, ACK, Throttle, Brake, Speed, Akku, Light, Lock, Park)
Button P : 60% (1 Short Press Light on/off, 2 short Switch Eco,D,S, 1 Long Press ToDo: Cruise Mode or Backlight Bevaviour Always On or Brake Activated Dim/Full On )


Ninebot G2: 
Dashboard: 100%
BMS      : 100%
Ported   : 90% ToDo: P Mode and Lock


Ninebot G3: 
Dashboard: 40%
BMS      : 0%
Ported   : 40%

Vesc:

Protocol : 100% Thanx to: 


05-Nov-2025-21:51h.-----------------------------------------------------------------------<BR>

Added BMS Activator & Connector Reference: https://github.com/NormalHuman-Anything<BR>
19A only auf ECO <BR>
40A Max.(may dif. G2/G3 ) DRIVE und SPORT <BR>
