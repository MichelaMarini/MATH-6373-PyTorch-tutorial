### PyTorch Tutorial


### Instructions for installing Anaconda
If you do not have anaconda installed on your computer, the first step is to install anaconda3 as follows:  
  1.	Download Anaconda: Go to the Anaconda website [Anaconda](https://www.anaconda.com/download) and download the Anaconda3 installer for your operating system (Windows, macOS, or Linux).
  2.	Run Installer: Once the installer is downloaded, run it and follow the installation instructions.
  3.	Agree to Terms: Read and agree to the license agreement.
  4.	Choose Install Location: Choose a directory where Anaconda will be installed. The default location is usually fine.
  5.	Select Installation Type: Choose whether to install Anaconda just for you or for all users on the system.
  6.	Advanced Options (Optional): You may have the option to add Anaconda to your system PATH environment variable, which can make it easier to use from the command line. This is typically recommended.
  7.	Install: Click the "Install" button to begin the installation process.
  8.	Complete Installation: Once the installation is complete, you may be prompted to install Visual Studio Code (VS Code) or PyCharm. You can choose to install them or skip this step if you prefer.
  9.	Verify Installation: Open a terminal or command prompt and type ```conda --version``` to verify that Anaconda has been installed correctly. You should see the version number of Anaconda displayed.


### Setting Up Conda Virtual Environment

Follow the steps below to create a Conda virtual environment named `MATH6373` and install Python packages.

## 1. Open Anaconda Prompt

Once Anaconda is installed, open the Anaconda Prompt (search for "Anaconda Prompt" in the desktop search bar on Windows or use the terminal on macOS/Linux).

## 2. Create the Virtual Environment

Run the following command to create a new virtual environment named `MATH637` with Python 3.10:

```bash
conda create --name MATH637 python=3.10 --no-default-packages
```
## 3. Activate the Virtual Environment
To activate the newly created environment, run the following command:

```bash
conda activate MATH6373
```
Make sure you are inside the virtual environment folder before proceeding with any installations. 

## 4. Install pip
If pip is not already installed in your virtual environment, install it by running the following command:

```bash
conda install pip
```
## 5.  Install Libraries
You can now install the libraries you need in your environment. For example, to install numpy, run:

```bash
pip install numpy
```

