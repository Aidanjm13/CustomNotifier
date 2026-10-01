# CustomNotifier

A customizable notification system for Windows devices designed to deliver randomized desktop alerts. Developed to simulate digital distractions for a Master's Psychology Thesis research project, this application uses a PyQt-based interface to give researchers and users complete control over the notification experience.

## Features

* **Fully Customizable Popups:** Adjust the size, color, and text messages of the notifications.
* **Screen Positioning:** Choose exactly where the notifications will appear on the screen.
* **Frequency Control:** Customize how often the randomized notifications pop up.
* **Audio Toggles:** Enable or disable notification alert sounds.
* **Persistent Settings:** Automatically saves your configuration between sessions so you do not have to reconfigure the tool every time.
* **Export & Import:** Easily export and import settings profiles, allowing for consistent experimental setups across multiple devices or research participants.

## Tools and Technologies

* Python
* PyQt

## Installation and Usage

### Using Pre-compiled Binaries (Recommended for Users)

For standard users, you can run the application without installing Python.

1. Navigate to the [Releases](../../releases) page of this repository.
2. Download the latest `.zip` archive.
3. Extract the archive and execute the `CustomNotifier` binary.
4. The application will begin running in the background according to its configured parameters.

### Running from Source (For Researchers/Developers)

To run the application from source or to modify the experiment parameters:

1. Clone the repository:
   ```bash
   git clone [https://github.com/Aidanjm13/CustomNotifier.git](https://github.com/Aidanjm13/CustomNotifier.git)
   cd CustomNotifier
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```
   
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Start the application:
   ```bash
   python GUI.py
   ```
