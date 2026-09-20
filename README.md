# SDP-2assignment-KenzhegaliAziza

Project Purpose
This project is a Java logistics application that demonstrates the integration of two creational design patterns. It uses the Factory Method pattern to manage road and sea delivery logistics,and the Abstract Factory pattern to render matching UI components (buttons and checkboxes) for Windows or macOS platforms.Both patterns run together in the same program without hardcoding concrete classes into the client logic.


Prerequisites:
Java Development Kit (JDK): Version 17   
IDE: IntelliJ IDEA, Eclipse, or any terminal supporting Java compilation


The project is organized into three distinct Java packages to enforce clean separation of concerns: 
~app/: Contains the client (DeliveryApplication) and the startup/validation logic (Main).   
~transport/: Contains the Factory Method implementation, including the Transport interface, concrete products (Truck, Ship), and creators (Logistics, RoadLogistics, SeaLogistics).   
~ui/: Contains the Abstract Factory implementation, including abstract products (Button, Checkbox), concrete platform products, and the factories (GUIFactory, WindowsFactory, MacOSFactory).


Supported Input Values
When prompted, you must enter valid options to configure the application:   
PDF
~Delivery mode: ROAD or SEA
~UI platform: WINDOWS or MACOS


Build and Run Instructions
Using an IDE (Recommended):
~Open the project folder in IntelliJ IDEA or another Java IDE.   
~Ensure the project SDK is set to JDK 17.   
~Locate src/app/Main.java.
~Right-click the file and select Run 'Main.main()'.

Sample Run 

Delivery mode (ROAD or SEA): ROAD
UI platform (WINDOWS or MACOS): WINDOWS
Delivery mode: ROAD
UI platform: WINDOWS
Rendering Windows button
Rendering Windows checkbox
Truck delivers laboratory equipment to Aktau warehouse by road.
