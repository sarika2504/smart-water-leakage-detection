# Working Principle

The Smart Water Leakage Detection System continuously monitors the flow of water using two water flow sensors.

- Sensor 1 measures the incoming water flow.
- Sensor 2 measures the outgoing water flow.
- Arduino UNO compares both readings.
- If the difference exceeds the predefined threshold, the system identifies it as water leakage.
- The relay module immediately switches OFF the water pump.
- The LCD displays the leakage status and flow values.
- If no leakage is detected, the pump continues operating normally.
