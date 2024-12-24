# STM32CubeIDE Project Instructions

Thank you for downloading this STM32CubeIDE project! Before you proceed, please ensure you adjust the project settings as per your specific STM32 IC. The project is primarily configured for the following development boards:

- **Nucleo-F334R8**
- **Nucleo-F103R6**

## Steps to Update the Project Settings
1. **Open the Project in STM32CubeIDE**:
   - Launch STM32CubeIDE and open the project folder.

2. **Check and Update the MCU/Board Settings**:
   - Navigate to **Project > Properties > C/C++ Build > MCU Settings** (or similar, depending on your version).
   - Update the target MCU/board to match your STM32 device.

3. **Verify Peripheral Configurations**:
   - Open the **.ioc** file in STM32CubeIDE.
   - Ensure that the pinout and peripheral settings are configured correctly for your specific STM32 IC.
   - If needed, regenerate the code using STM32CubeMX (inside the IDE).

4. **Rebuild the Project**:
   - Clean and rebuild the project to ensure compatibility with your MCU.

## Notes
- Most of the project files, including initialization code and configurations, are designed for **Nucleo-F334R8** and **Nucleo-F103R6** boards. Adjustments may be required for other boards or custom hardware.
- For assistance with specific settings, refer to the [STM32CubeIDE documentation](https://www.st.com/en/development-tools/stm32cubeide.html) or the user manual for your STM32 board.

## Contributions
Feel free to contribute improvements or adaptations for other STM32 ICs by submitting a pull request. We appreciate your collaboration!

---

If you encounter issues or need help, please open an issue in this repository.

Happy coding with STM32!
