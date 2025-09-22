# tech-repairs
Notes and documentation of hardware and troubleshooting projects: iPhone screen replacements, drone repairs and laptop upgrades.

## Projects

### iPhone XR & iPhone 13 Screen Replacements

**Devices**: iPhone XR, iPhone 13  
**Tools Used**: iFixit toolkit (spudger, screwdrivers, tweezers), suction cup, heat gun, magnetic screw mat, replacement adhesive

**Process Overview**:
1. Removed the two pentalobe screws at the bottom of the device.  
2. Applied heat to loosen the adhesive and used a suction cup to lift the screen.  
   - XR: original factory seals made removal smoother.  
   - 13: refurbished device had stronger adhesive, requiring careful prying and gradual removal to avoid internal damage.  
3. Opened the phone like a book and removed the small metal plates covering the connectors 
4. Disconnected the battery first, then disconnected screen ribbon cables, noting differences:  
   - XR ribbon cable located on the **right**.  
   - 13 ribbon cable located on the **left**.  
5. Carefully, disconnected and transferred the Face ID and earpiece speaker module from the old screen to the new one.  
6. Used a magnetic mat to keep screws organised in removal order, ensuring correct placement during reassembly.  
7. Cleaned off old adhesive from the phone frame and applied new adhesive.

**Reassembly steps**:
1. Reconnected the Face ID and earpiece speaker ribbon cables.  
2. Reconnected the screen ribbon cables.  
3. Secured the metal plates over both the Face ID module and the screen ribbons.  
4. Reconnected the battery.  
5. Secured the final metal plate over the battery connector.  
6. Carefully snapped the new screen into place, ensuring it was fully seated.
7. Screwed the pentalobe screws at the bottom of the phone back in

**Outcome**:
- Both devices fully functional after repair.  
- Face ID, display, and touchscreen tested successfully.  

**Key Takeaways**:
- Careful handling of ribbon cables is critical to avoid damage.  
- Adhesive strength varies between devices; patience and steady pressure are essential.  
- Organising screws with a magnetic mat speeds up reassembly and reduces error risk.

### Potensic Atom SE Drone Arm Replacement

**Device**: Potensic Atom SE drone  
**Tools Used**: iFixit toolkit (screwdrivers, spudger, tweezers), soldering iron, magnetic screw mat  

**Process Overview**:
1. Followed a YouTube guide specific to the Potensic Atom SE arm replacement.  
2. Opened the drone carefully by removing the outer frame screws, using a spudger to separate plastic panels without snapping clips.  
3. Disconnected the antenna cable and three small copper wires leading to the mainboard.  
4. Heated the solder joints with a soldering iron to detach the old arm wires.  
  - *Note for future*: to ensure the best quality joints, I will use flux. For this repair, I successfully achieved solid connections by carefully tinning the tip of the soldering iron and reusing the existing solder.  
5. Removed the damaged front arm and replaced it with the new arm, carefully routing the wires through the frame.  
6. Resoldered the wires back onto the board, ensuring strong joints.  
7. Reconnected the antenna cable.  
8. Reassembled the drone using the magnetic mat to track screws and components.  

**Outcome**:
- Drone successfully repaired and fully functional.  
- Flight-tested: hover stability, GPS lock, and return-to-home features all confirmed working.  

**Key Takeaways**:
- Gained practical soldering experience, including tinning and resoldering delicate wires.  
- Learned the importance of cable routing and organisation in compact electronics.  
- Validated the repair through functional testing, not just visual inspection.  

### Laptop Upgrades & Optimisation

**Devices**: Family laptops (one full upgrade, one partial upgrade)  
**Tools Used**: Screwdrivers, spudger, USB stick with Windows installation media  

**Process Overview**:
1. Opened the laptops by unscrewing the bottom panel screws and carefully prying off the casing with a spudger.  
2. Disconnected the battery before working on internal components to avoid short circuits.  
3. **Sister’s laptop**:  
   - Replaced the existing SSD with a larger/faster one.  
   - Installed additional RAM to improve performance.  
   - Prepared a bootable USB stick with Windows installation media.  
   - Troubleshot an issue where the new SSD was not detected during installation.  
     - Solved by copying the correct storage drivers onto the USB stick alongside the installer.  
   - Successfully reinstalled a clean copy of Windows, removing all bloatware.  
4. **Mum’s laptop**:  
   - Upgraded RAM.  
   - Wiped the device and reinstalled a fresh copy of Windows to optimise performance.  

**Outcome**:
- Both laptops ran significantly faster after upgrades.  
- Reduced boot times and improved multitasking performance.  
- Restored laptops to a “like-new” state with clean, stable Windows installations.  

**Key Takeaways**:
- Learned correct procedure for handling and upgrading laptop internals (SSD, RAM).  
- Developed troubleshooting skills by identifying and fixing SSD driver recognition issues during Windows installation.  
- Reinforced safe practices (disconnecting battery before hardware work).  
