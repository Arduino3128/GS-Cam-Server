# GS Cam Server  

Repository for Raspberry Pi GS Cam Server  
  
## Instructions  

### Run the following commands in the Raspberry Pi Terminal  

1. Update and Upgrade any packages in the Raspberry Pi OS:  
`sudo apt update`  
`sudo apt upgrade`

2. Clone the repository:  
`git clone https://github.com/Arduino3128/GS-Cam-Server.git`  
  
3. Navigate in to the folder:
`cd GS-Cam-Server`
  
4. Run the Python script:
`python main.py`

If the scripts ends with "PiCamera2 Module not Found":
`sudo apt install -y python3-picamera2`
and run the script again.

### Server can be accessed on

`http://IP_ADDRESS:8000/`

If the Raspberry Pi is connected with a hotspot from a Windows Computer:
`http://raspberrypi.mshome.net/8000/`
