# EAGLE
Eagle is a popular electronic design automation (EDA) software that is widely used in the industry for designing printed circuit boards (PCBs). Follow the steps instructions to get started with Eagle software.
## Step 1: Download and Install Eagle Software.
- [Go to the Eagle website](https://www.autodesk.com/products/eagle/free-download) and click on the **Download Now** button.
- Create an account or sign into your existing account.
- Select the appropriate version of Eagle for your os (Windows, Mac, or Linux).
- Follow the on-screen instructions to complete the installation.
## Step 2: Creating a New Project
- Open the Eagle software.
- Click on **File** and then **New** to create a new project.
- Enter a name for your project and choose a location to save it.
- Its a good practice to add description to your project do that by Right Click > Edit descripton
- Select a schematic template for your project.
## Step 3: Drawing Schematic
A PCB design schematic can be described as a circuit diagram or the functional diagram of electronic circuits. Symbols are used to represent components and show how they are connected electrically.
- Open the schematic editor by clicking on **File** and then **New Schematic**
- Use the tools on the left-hand side of the screen to draw the components of your circuit. You can also use the search function to find specific components.
- Eagle comes with a built-in library of components that you can use in your designs but you can also create your own components or import them from other sources.
- Download [Adafruit & SparkFun](https://www.autodesk.com/products/fusion-360/blog/library-basics-install-use-sparkfun-adafruit-libraries-autodesk-eagle) library to get all the components.
- After downloading click on **Library** then select **Open library manager** Browse to the downloaded library and then hit **update all** in Library Menu.
- Use **Add Part** tool to get the components or just do `ctrl+L` to activate the command line mode and type **add** then a pop window will appear showing the components list.
- The most used tools include **Add**, **Move**, **Rotate**, and **Delete**.
- To do the above operations, Click on the red colour plus(+) sign which is present either near the specific component or in the center of the component.
- Use the **Net** tool or type **net** to draw wires between the pins of each component. Make sure to label each net with a unique name to avoid confusion.
- Value and labels provide information about the components in your circuit. To add value and labels to your schematic, use the **Value** and **Label** tools.
- Save your schematic by clicking on **File** and then **Save**.
- After completing all, click Tools and do Electric Rule Check(ERC). 
- After completing the schematic, if you want to generate a netlist. A netlist is a list of all the components and their connections in the circuit. Click on **File > Export > Netlist** and save the file.
- **Some hotkeys for drawing schematic are as follows:**
  - Add Part: `ctrl+shift+A`
  - Copy a component: `ctrl+shift+C`
  - Delete a component: `ctrl+D`
  - Move: `ctrl+M`
  - Rename a component: `ctrl+shift+N`
  - Change value of component: `ctrl+shift+v`
  - To run ERC: `ctrl+shift+E`
  - To see the error: `ctrl+E`
- **To transfer the schematic into layout in the schematic editor go the *File* and then *Switch to board***
## Step 4: Designing the PCB
Once you have created a schematic, the next step is to design the PCB board or layout.
- Open the PCB editor by clicking on **File** and then **Switch to Board**
- Click on **File** and then **Import** to import your schematic.
- Use the tools on the left-hand side of the screen to place the components on the PCB.
- Plan a floor plan to place the components in their suitable places to use more effective area.
- Use the **Route** tool to connect the components with copper traces.
- Add vias and through-holes as needed.
- Save your PCB design by clicking on **File** and then **Save**
- Before finalizing the design, check the design rules. Design rules ensure that the board meets the manufacturer's specifications. Click on **DRC** and run the check.
## Step 5: Exporting the Design
After completing the design, export it in the required format. Gerber files are the standard file format used by manufacturers. Click on **File > Cam processor** and save the files.
