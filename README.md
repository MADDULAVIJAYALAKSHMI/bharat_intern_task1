# bharat_intern_task1
In these modern days finding car parking is a big issue in congested cities. There are too many vehicles on the road but not enough parking spaces. One of the biggest problems is when we enter a parking area then we realize that there are no empty parking slots to park our cars. Important time. Another biggest problem is after entering in a big parking area we confused to find the empty parking slot to park our car. Sometimes maybe we all have been facing these two problems that wasted our important time. That’s why we need efficient parking management systems in all parking areas that will provide confusion-free and easy parking.After assembling all components according to the circuit diagram and uploading the code to the Arduino board. Now place the sensors and servo motor at accurate positions.

There are four parking slots in this project, IR sensor-3, 4, 5, and 6 are placed at slot-1, 2, 3, and 4 respectively. IR sensor-1 and 2 are placed at the entry and exit gate respectively and a servo motor is used to operate the common single entry and exit gate. The LCD display is placed near the entry gate.

The system used IR sensor-3, 4, 5, and 6 to detect whether the parking slot is empty or not and IR sensor-1, and 2 for detecting vehicles arriving or not at the gate.

In the beginning, when all parking slots are empty, then the LCD display shows all slots are empty.

When a vehicle arrives at the gate of the parking area then the IR sensor-1 detects the vehicle and the system allowed to enter that vehicle by opening the servo barrier. After entering into the parking area when that vehicle occupies a slot then the LED display shows that the slot is full. In this way, this system automatically allows 4 vehicles.

In case the parking is full, the system blocked the entrance gate by closing the servo barrier. And the LED display shows that slot-1, 2, 3, and 4 all are full.

When a vehicle leaves a slot and arrives at the gate of the parking area then the IR sensor-2 detects that vehicle and the system open the servo barrier. Then the LED display shows that the slot is empty. Again the system will allow entering a new vehicle.
