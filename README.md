SmartLaundry is an advanced software system designed to intelligently coordinate four appliances—washer, dryer, dehumidifier, and heater—in a domestic environment. The project was developed as part of a Software Engineering course at the University of Naples and focuses on energy efficiency, usability, and adaptive automation.

The system allows both manual and automatic management of each appliance. Through its Smart Controller, it ensures input consistency, suggests corrected parameters, and calculates estimated energy consumption based on environmental and geographic data provided during setup.

Key features:
• 	⚙️ Command Pattern: For encapsulating and managing operations such as DryCommand and WashCommand.
• 	📡 Strategy Pattern: Implements different strategies based on laundry type and material to calculate weight and energy (e.g., CottonEnergyCalculationStrategy, SyntheticsWeightCalculationStrategy).
• 	🛰️ Observer Pattern: Used to track changes in environmental parameters, notifying relevant components like Environment class for behavioral adjustments.
• 	🧠 Smart Scheduling: Parallel execution of multiple operations while keeping energy usage under a defined threshold (e.g., 2300 watt/hour).
• 	🕹️ Dynamic Use Case Mapping: Real user scenarios like checking weather conditions, starting a cycle, or cancelling a program.
• 	🖥️ Graphical User Interface (GUI): Built with usability in mind, users can set parameters intuitively and receive real-time feedback.

Technologies & Design:
• 	💻 Java, Object-Oriented Programming, SOLID principles
• 	🏗️ UML Models including Class Diagrams, Activity Diagrams, Sequence Diagrams
• 	🔐 Secure role-based access with administrator vs standard user profiles
• 	📱 Responsive GUI built in Figma, emphasizing accessibility and ease of use
• 	📊 Testing and validation based on ISO 9241-110 usability guidelines

The system even learns user habits (like daily laundry routines or room humidity patterns) using situation tracking, offering an optimized and adaptive experience for every household.
