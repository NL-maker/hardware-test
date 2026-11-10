**Meeting Summary - How to put together and test an Upduino FPGA board**

*Quick recap*
This meeting was a hands-on workshop led by Bill Sievert from Washington University in St. Louis, where he guided students through assembling and testing Upduino boards with breadboards, LED modules, and wires. Bill explained the electrical connections in breadboards, demonstrating how to properly insert the Upduino into the breadboard's first column and connect wires from the Arduino pins to the LED module in the correct order starting with 3V3 to VCC. The students successfully assembled their boards and verified the connections, then used a cloud-based development environment called Codespaces to test their hardware by uploading and running test programs including an AND gate simulation written in System Verilog. The workshop successfully demonstrated the complete setup process from hardware assembly to software programming, with Bill providing additional instructions for Windows users regarding driver installation and troubleshooting tips for future work with the boards.

*Next steps*

Professor Thomas Schmidt Notes
- Upload the Zoom recording of the session for students to refer back to.
- Send out the driver installation instructions to students, especially those using Windows computers.
- Coordinate with Bill if students have further questions about the hardware or software setup.

*Collaboration*
Students: If using a Windows computer, download and use the Zadig program to install/update the driver for the Arduino.
Students: Reinstall the driver if the device does not show up or if they plug the Arduino into a different USB port.
Students: When working in Codespaces, push changes back to their own GitHub repository to ensure work is saved outside the virtual machine.

*Summary*
Upduino Board Setup Demonstration
Bill demonstrated how to properly connect an Upduino board to a breadboard, explaining the electrical connections and showing where to position the board and insert wires. Students practiced the setup, with Bill and Thomas providing guidance on ensuring correct placement of the board in the first column and proper wire insertion starting at the 3V3 marked position. The session focused on getting four students with complete components up and running, while noting that only six students had breadboards and Upduinos but only four had all necessary components including LEDs.

LED Module Arduino Connection Guidance
Bill guided the team on connecting LED modules to Arduino boards, explaining the correct wire order starting with 3V3 to VCC, followed by ground and then strobe, clock, and IO connections. Thomas confirmed that most participants had successfully assembled their LED connections and discussed using rubber bands to secure the LEDs on the breadboard. The team discussed ensuring proper wire ordering to avoid connection issues, with Bill noting that incorrect wiring typically causes the circuit to not work rather than damaging components.

GitHub Repository Setup Demonstration
Bill shared a GitHub repository for hardware testing and demonstrated the process of forking it. He explained that students would need to set up the development environment using Codespaces, which is based on Visual Studio Code. Thomas confirmed that students should all fork the repository and discussed the setup process, noting that most students at Pace University already have GitHub accounts.

FPGA Development Environment Setup Demo
Bill demonstrated how to set up and use a cloud-hosted development environment called Codespaces to work with a field programmable gate array (FPGA) board. The session covered creating a code space, testing digital logic gates through simulation, and uploading programs to the Arduino-connected FPGA board. Bill successfully guided participants through loading test programs and an AND gate circuit, with participants successfully getting their LED boards working and running the AND gate program. The session concluded with instructions for Windows users to update their drivers and plans to continue similar sessions throughout the semester.

Attendees: Thomas Schmidt (Organizer), TC38147P (External), **Natasha Larencule (External)**, Daniel Ingunxa (External), Nicola Francavilla (External), alexandralivadhi (External), Melani (External), Kymani Grant (External), Brandon Gomez (External), Tyler (External), Lloyd Boadi-Amoah (External), Bill Siever (External)

Please note: The following items were sent in the chat and might be needed to work with the Upduino boards
2026-10-26 13:11:54 From Bill Siever to Everyone:
    https://washu-cse2600-fl26.github.io/fpga/
    
2026-10-26 13:26:02 From Bill Siever to Everyone:
    https://github.com/digital-logic-and-computer-design/hardware-test
    
2026-10-26 13:28:15 From Thomas Schmidt to Everyone:
    https://github.com/digital-logic-and-computer-design/hardware-test
    
2026-10-26 13:32:55 From Melani  to Everyone:
    https://github.com/digital-logic-and-computer-design/hardware-test
    
2026-10-26 13:45:48 From Kymani Grant to Everyone:
    https://github.com/digital-logic-and-computer-design/hardware-test
    
2026-10-26 13:46:48 From Bill Siever to Everyone:
    https://washu-cse2600-fl26.github.io/fpga/
    
2026-10-26 13:46:58 From Bill Siever to Everyone:
    Windows driver change/update: https://washu-cse2600-fl26.github.io/fpga/
    
2026-10-26 13:48:03 From Bill Siever to Everyone:
    Windows driver: https://washu-cse2600-fl26.github.io/fpga/
