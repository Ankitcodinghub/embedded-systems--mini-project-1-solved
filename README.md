# embedded-systems--mini-project-1-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/embedded-systems-c-programming-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128661&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Embedded-Systems -Mini-Project-1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Project

Implement the following Vehicle Control system with the specifications listed below.

1. Ask the user if he/she wants

a. Turn on the vehicle engine

b. Turn off the vehicle engine

c. Quit the system

2. If chose to “Quit the system”: Quit program

3. If chose to “Turn off the vehicle engine”: Ask him/her again what he/she wants to do (Requirement 1)

4. Once a choice has been chosen, print on screen the system state.

5. If chose to “Turn on the vehicle engine”, display “Sensors set menu”, menu that simulates the vehicle sensors readings.

a. Turn off the engine

b. Set the traffic light color.

c. Set the room temperature (Temperature Sensor)

d. Set the engine temperature (Engine Temperature Sensor)

6. While the engine is ON, menu in requirement 5 must be always displayed and waits for an answer.

7. Based on the answer of requirement 6.

a. Based on traffic light data (Take it as input from console, we will assume that this is the sensor read value)

i. If the traffic light is ‘G’ set vehicle speed to 100 km/hr

ii. If the traffic light is ‘O’ set vehicle speed to 30 km/hr iii. If the traffic light is ‘R’ set vehicle speed to 0 km /h

b. Based on room temperature data (Take it as input from console, we will assume that this is the sensor read value)

i. If temperature less than 10, Turn AC ON and set temperature to 20

ii. If temperature is greater than 30, Turn AC ON and set temperature to 20

iii. If temperature is otherwise, Turn AC OFF

c. Based on engine temperature data (Take it as input from console, we will assume that this is the sensor read value)

i. If temperature less than 100, Turn “Engine Temperature Controller”

ON and set temperature to 125 ii. If temperature is greater than 150, Turn “Engine Temperature

Controller” ON and set temperature to 125 iii. If temperature is otherwise, Turn “Engine Temperature Controller”

OFF

d. If vehicle speed is 30 km/hr

i. Turn ON AC if it was OFF and set room temperature to: current temperature * (5/4) + 1

ii. Turn ON “Engine Temperature Controller” if it was OFF and set engine temperature to: current temperature * (5/4) + 1

e. Display the current vehicle state after applying 7.a to 7.d

i. Engine state: ON/OFF

ii. AC: ON/OFF

iii. Vehicle Speed iv. Room Temperature

v. Engine Temperature Controller State.

vi. Engine Temperature

8. If chose in menu of requirement 5 to “Turn off the engine”, the menu of requirement 1 must be displayed.

9. Bonus Requirement: Create #define WITH_ENGINE_TEMP_CONTROLLER, if this

#define is 1 then compile/run the code lines that are related to the “Engine

Temperature Controller, else do not compile/run. (Code that implements5—d, 7-­­c, 7-­d-­­ii, 7-e-v and 7-e-vi)

Notes

• To get an character input use:

printf(“a. Turn on the vehicle engine “); printf(“b. Turn off the vehicle engine “); printf(“c. Quit the system “); scanf(“ %c”,&amp;input);

Make sure you left a space before %c to prevent scanf function from take new line or enter from the above printf functions as input.

• For the bonus requirement, search for how to use preprocessor directive like below in C Language.

#if (CONDITION)

…

#endif

This topic will be discussed later in C For Embedded Systems (Embedded C) Course.

&nbsp;
