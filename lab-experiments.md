# Hardware Hacking Lab – Experiment Log 

## Objective
To understand how insecure hardware access control logic can allow unauthorized access, using a virtual Arduino simulation.

$python
## Experiment 1: Basic Access Control (Insecure Design)

### Setup
- Arduino Uno (Simulated)
- Push button connected to digital pin 2
- LED connected to digital pin 13
- Simple Logic: The button controls access directly

### Procedure
1. Start Arduino simulation.
2. Observe the state of the LED without pressing the button.
3. Press and hold the button.
4. Monitor LED and Serial Monitor outputs.
5. Release the button and observe.

### Observation
- Once pressed, the LED connected to the button will turn ON.

The text on the Serial Monitor display reads: **Access Granted** 
- When the button is released, the LED will turn OFF. - Serial monitor display: **Access Denied** 

### Result
 Anyone can access the room just by pressing the button.

 **BAL
 ## Experiment 2: Analysis of Vulnerability The codeIn this

### Observation
An authentication system does not exist for the system. All the user needs to get access to the physical button hardware is physical access to the button.

### Identified Vulnerability
- No User Verification - No Password and OTP Required - Direct hardware control leads to unsafe access*

## Learning Outcome
- Understood basic hardware access control
- Learned how insecure logic creates vulnerabilities
- Gained awareness of secure hardware design
- Practiced ethical hardware security testing in a simulated environment

