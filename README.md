# Drivetrain Calculation for Formula SAE
This MATLAB script calculates the torque on the wheels and vehicle speed for each gear in a Formula SAE vehicle. Additionally, it generates various performance plots such as torque vs speed, and RPM vs speed for each gear.

## Features
- **Torque Calculation:** Calculates the torque on the wheels for each gear.
- **Speed Calculation:** Determines the vehicle's speed for each gear.
- **Resistive Torque and Traction Limit:** Compares the resistive torque to the traction limit of the vehicle.
- **Shift Points:** Displays the RPM shift points for optimal gear usage.
- **Graphs:** Generates key performance graphs to visualize drivetrain behavior.
  
## Installation
To run this code, you will need to have MATLAB installed on your machine. Once MATLAB is set up, follow these steps:  

1. Clone this repository  
2. Navigate to the directory where the code is stored and open MATLAB.  
3. Run the script drivetrain_apuama.m in MATLAB:  
```run('drivetrain_apuama.m')```  
## Usage
After running the script, the following graphs will be generated:

1. Torque vs Speed (All Gears):  
  - Shows the torque output at the wheels and the resistive torque over different vehicle speeds.
    
2. RPM vs Speed Shift Points:  
  - Shows the engine RPM for each speed and the shift points for gear changes.  
  
3. Torque and Power vs RPM:  
  - Plots both torque and power curves against engine RPM.  

## Contributing 
Contributions to improve the code or add new features are welcome. Please follow these steps:  

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push the branch (`git push origin feature/new-feature`).
5. Open a pull request.

## License
This project is licensed under the MIT License.
