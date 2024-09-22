# Spider-Solitaire-SFML

A **Spider Solitaire** game developed using **SFML** in C++.

## Prerequisites

To run this project, you will need the following:

- **SFML** (Simple and Fast Multimedia Library) for C++.
- Download the latest **x64 SFML** version for Windows from the official SFML website: [SFML Download](https://www.sfml-dev.org/download/sfml/2.5.1/).

## Setup Instructions

Follow these steps to set up and run the Spider Solitaire game:

### 1. Download SFML

1. Visit the SFML website and download the latest **x64 version** for Windows.
2. Unzip the downloaded SFML file.

### 2. Set Up SFML in the Project

1. **Copy the `lib` and `include` folders** from the downloaded SFML directory.
   - Navigate to the extracted SFML folder, find the `lib` and `include` folders.
2. **Paste the `lib` and `include` folders** into the **`SFML`** folder inside this project's root directory.

### 3. Build and Run the Project in Debug Mode

1. Open the project in your C++ IDE (such as Visual Studio).
2. Set the project configuration to **Debug Mode**.
3. Build the project once, which will generate an **x64/Debug** directory in your project.

### 4. Copy SFML DLLs to the Project's x64/Debug Directory

1. Go to the **`bin` folder** in your downloaded SFML directory.
   - Example path: `C:/path-to-sfml/SFML-2.5.1/bin/`
2. Copy all the DLL files in the `bin` folder.
3. Paste the copied DLL files into your project’s **x64/Debug** directory.
   - Example path: `YourProject/x64/Debug/`

### 5. Run the Game

After copying the necessary DLLs into the `x64/Debug` folder, the game is ready to run.

To play the Spider Solitaire game:

- Open your project in the IDE.
- Press **Run** to launch the game and start playing!

---

## Troubleshooting

- Make sure you are using the **x64** version of SFML for compatibility with your project.
- Verify that both the `lib` and `include` folders are correctly copied to the project’s `SFML` folder.
- Ensure all DLLs from the `bin` folder of SFML are in the **x64/Debug** folder of your project.

## License

This project is licensed under the MIT License. Refer to the `LICENSE` file for more details.

---

## Acknowledgements

- Developed using the **SFML (Simple and Fast Multimedia Library)**.
- Special thanks to the open-source community for their contributions and support.

Have fun playing **Spider Solitaire**!
