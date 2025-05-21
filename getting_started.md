# Installing Miniconda on Windows, Linux, and macOS

**Miniconda** is a lightweight version of Anaconda that installs only the minimum required packages. It's a popular choice for managing Python environments, especially for data science and machine learning projects.

### Windows Installation

1. **Download the Installer:**
   - Go to the official Miniconda website: https://conda.io/miniconda.html
   - Download the appropriate installer for your Windows version (32-bit or 64-bit).

2. **Run the Installer:**
   - Double-click the downloaded installer.
   - Follow the on-screen instructions.
   - **Important:** During installation, choose the option to add Miniconda to your system's PATH. This will allow you to use conda commands from the command prompt.

### Linux Installation (Bash Shell)

1. **Download the Installer:**
   - Go to the official Miniconda website: https://conda.io/miniconda.html
   - Download the appropriate installer for your Linux distribution.

2. **Open a Terminal:**
   - Open a terminal window.

3. **Run the Installer:**
   - In the terminal, navigate to the directory where you downloaded the installer.
   - Use the following command to run the installer:
     ```bash
     bash Miniconda3-latest-Linux-x86_64.sh
     ```
     Replace the filename with the actual filename you downloaded.
   - Follow the on-screen instructions.
   - **Important:** During installation, you'll be asked if you want to initialize Miniconda by running conda init. Answer **yes**. This will add conda commands to your shell's configuration.

### macOS Installation

1. **Download the Installer:**
   - Go to the official Miniconda website: https://conda.io/miniconda.html
   - Download the appropriate installer for your macOS version.

2. **Run the Installer:**
   - Double-click the downloaded installer.
   - Follow the on-screen instructions.
   - **Important:** During installation, choose the option to add Miniconda to your system's PATH. This will allow you to use conda commands from the terminal.

### Post Installation

1. **Open a Terminal or Command Prompt:**
2. **Verify Installation:**
   ```bash
   conda --version
   ```


### Environment Setup

1. **Open a Terminal or Command Prompt:**
2. **Create environment:**
    ```bash
    conda create -n NN_SS2025 python=3.12
   ```


3. **Activate environment:**
   ```bash
   conda activate NN_SS2025
   ```


4. **Install relavant packages:**
    ```bash
      pip install torch==2.2.1 torchvision==0.17.1 torchaudio==2.2.1 torchdata --index-url https://download.pytorch.org/whl/cu121
      pip install "numpy<2" scipy pandas urllib3 fastprogress matplotlib ipython jupyterlab
   ```