# Aim: 
Measurement of Displacement using LVDT
## Objective:-
Study the relation between core displacement and output of LVDT
Understand the effect of change in supply frequency on LVDT performance
Understand the effect of change in excitation (supply) voltage on LVDT performance.

## Procedure:
First you need to configure the LVDT. Click on ' Show panel' tab at the right bottom For making the circuit, drag and drop the primary coil, Armature and secondary coils at the loactions shown on left hand side.
Now select No of Turns, peak to peak supply volatge and frequency from the drag and drop menu, available below LVDT diagram. Click on configure block to configure LVDT.
Now click on the black rectangular core placed between primary and secondary windings.
Drag the core to left hand side and observe the effect on the output magnitude. This can be observed on the time vs output volatge waveform and on the Distance vs output voltage graph. The core displacement is indicated in the square box below the diagram
Drag the core to right hand side and observe the effect on the output magnitude. Also observe the change in the phase.
Repeat steps 2 to 4 by changing supply volatge keeping frequency and no of turns constant.
Study the effect on the output voltage. For this click on blue color 'Configure' tab in the right side panel. You need to select required parameter value from drop down menu. After selecting the values click on green ' Configure' tab to set the parameter values.
Repeat steps 2 to 4 by changing supply frequency keeping and no of turns constant. Study the effect on the output voltage. Now keep supply voltage and frequency constant. Change the no of turns and observe the effect on the output voltage by repeating steps 2 to 4.

## Circuit Diagram of LVDT
<img width="205" height="378" alt="image" src="https://github.com/user-attachments/assets/ecd1b859-98fc-4263-939c-f735761a2815" />

## NOTE
The Supply Voltage range is 5V to 15V
The Supply Frequency range is 1KHz to 10KHz
For simulation purpuse ,the Supply Voltage is restricted to 10V and Supply Frequency is restricted to 5 KHz

## Measuremnt:
Number of Turns : 
Supply Voltage :
Supply Frequency :


## Formula Used :
Vout=fIp(4πNpNsµ0bx/3mlog(ro/ri))(1-(x2/2b2))
Where,
f =supply frequency (user selectable)

Ip=primary current = Vin/R

Where Vin (Vrms) is user selectable and R is the coil resistance ( 10 K Ohm)

Np=number of primary turns (user selectable)

Ns=number of secondary turns ( half of primary turns)

ro/ri=Ratio of outer and inner radii of the coil system ( = 2)

x=displacement of the core form null (from actual core postion)

µ0=permeability of space (4π10^-7h/m)

b = length of primary winding (= 20mm)

m = length of secondary winding (= 10 mm)


## Output waveforms:

<img width="740" height="570" alt="lvdt" src="https://github.com/user-attachments/assets/862b3885-1817-4e09-b6d9-4374abb1b0fa" />

## Result: 
Thus the Measurement of Displacement using LVDT has been measured.










