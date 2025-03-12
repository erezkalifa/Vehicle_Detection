Vehicle Detection Project Guide

1. Prerequisites**
Before running the project, ensure that your system meets the following requirements:
- Operating System: Windows / macOS / Linux
- Installed Python (recommended version 3.8 or higher)
- Installed PyCharm (or another development environment)
- Internet connection to download required libraries

2. Downloading the Project and Installing Dependencies**
	2.1 Downloading the Project**
1. Open `cmd` (Windows) or `Terminal` (Mac/Linux).
2. Navigate to the directory where you want to store the project:

   cd path/to/your/directory
   
3. Clone the repository from GitHub:

   git clone https://github.com/erezkalifa/Vehicle_Detection.git

4. Enter the project directory:
 
   cd Vehicle_Detection
   

2.2 Installing Required Libraries
In the terminal or CMD, install the required libraries:

pip install -r requirements.txt

If `pip` is not recognized, try:

python -m pip install -r requirements.txt

or

py -m pip install -r requirements.txt


3. Running the Program
3.1 Running via PyCharm
1. Open PyCharm.
2. Click File→ Openand select the `Vehicle_Detection` folder.
3. Click Run → Edit Configurations**.
4. Click ➕ (Add Configuration) → Select Python.
5. Under Script Path select the `vehicle_detection.py` file.
6. Click OK.
7. Click Run ▶️to start the program.

3.2 Running via Terminal
If you are not using PyCharm, you can run the project via the terminal:

python vehicle_detection.py

or

py vehicle_detection.py


4. Using the Program After Launch
1. After launching, a browser link will be displayed (e.g., `http://127.0.0.1:7860`).
2. Open the link to access the GUI interface.
3. Choose one of the options:
   - **Upload an image/video for detection**.
   - **Select from existing dataset images/videos**.
4. Click **Confirm Selection**.
5. The result will be displayed with bounding boxes marking the detected vehicles.

5. Troubleshooting Common Issues**
5.1 Pip Not Recognized**
Try running:

python -m ensurepip --default-pip

or

python -m pip install --upgrade pip


5.2 Dataset Folder Not Found**
If the `dataset/` folder is missing, create it:

mkdir dataset


5.3 GitHub Access Error During `git push`**
If authentication is required, ensure you are logged into GitHub via SSH or PAT.

The project is now ready to run.