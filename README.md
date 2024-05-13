# Real-time Intrusion Detection Web App
<b>Major Project</b><br>
<b>Rajya Vardhan & Rohan Kumar</b><br>
## About
* Real-time Intrusion Detection System implementing Machine Learning. 

* We combine Supervised learning (RF) for detecting known attacks from CICIDS 2018 & SCVIC-APT datasets, and Unsupervised Learning (AE) for anomaly detection.

* System descriptive diagram:
![image]()

## Requirements:
1. Windows OS.

2. Python 3.9:
    * link 64-bit: https://www.python.org/ftp/python/3.9.13/python-3.9.13-amd64.exe 
    * link 32-bit: https://www.python.org/ftp/python/3.9.13/python-3.9.13.exe

     <b> Note: select "Add Python 3.9 to PATH" in installation procedure.</b>

3. Npcap 1.71:
    https://npcap.com/dist/npcap-1.71.exe

## Download project folder & environment setups:
<code>git clone https://github.com/vardhanrajya08/project
    cd APT_Detection
    # Create a virtual environment
    python3.9 -m venv venv
    # Activate that virtual environment
    source venv/bin/activate
    # Activate that virtual environment
    Set-ExecutionPolicy RemoteSigned -Scope Process
    .\venv\Scripts\Activate
    # Install the project requirements.
    python -m pip install -r requirements.txt
    # or: pip install -r requirements.txt</code>

Run program:

<code>python application.py</code>

Web app address: [http://localhost:5000](http://localhost:5000)

## Demo GUI
* Main page, overview of real-time captured flows:

![image]()

* Flow detail page:

![image]()

