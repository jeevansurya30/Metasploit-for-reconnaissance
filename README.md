# EX 5: METASPLOIT FOR RECONNAISSANCE
## Metasploit
Metasploit for reconnaissance in pentesting
```
Register Number: 212222040061
Name: JEEVANSURYA K
```

## AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

### EXECUTION STEPS AND ITS OUTPUT:
### Step 1: Identify the Attacker’s IP Address
Determine the IP address of the attacker's system.

![Screenshot 2025-04-22 203511](https://github.com/user-attachments/assets/32bb5b09-fb06-4802-a41d-495646ee9d48)




### Step 2: Launch the Metasploit Console
Invoke the msfconsole.

![2](https://github.com/user-attachments/assets/49777379-4743-4ee3-92c7-fb021211b755)



To view available commands, enter "?".

![3](https://github.com/user-attachments/assets/56213509-8935-45da-9e1e-9e9354edffaa)



### Step 3: Generate Payload Using msfvenom
Execute the following command to generate a Windows Meterpreter reverse shell payload.

![Screenshot 2025-04-22 203717](https://github.com/user-attachments/assets/fb61ed63-28a7-4010-b67d-7bcf6310d36d)



### Step 4: Set Up an HTTP Server
Once the payload file is created, navigate to the home directory. Right-click and select "Open Terminal Here."

![5](https://github.com/user-attachments/assets/32d8ce58-cc40-4f64-92c9-6eb13eb9a3d6)



Run the Python command to establish an HTTP server for file distribution.

![Screenshot 2025-04-22 203709](https://github.com/user-attachments/assets/869e4796-d0e7-402e-8cf3-c0eaa1013b6f)


### Step 5: Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server.
Once the victim downloads and executes the file, the exploit is triggered.
#### VICTIM DEVICE:





### Step 6: Establish a Connection
On Kali Linux, reopen the terminal and invoke msfconsole.
Follow the necessary steps to establish a connection with the victim’s device.

![Screenshot 2025-04-22 205422](https://github.com/user-attachments/assets/4217b8dd-dc89-4bb4-a788-11a846cd212d)



Once exploited, a session is created, allowing remote access without the victim’s awareness.

### Step 7: Execute Commands on the Victim’s Device
Use the help command to list available operations.

![Screenshot 2025-04-22 205701](https://github.com/user-attachments/assets/844b16a1-4a98-4110-9588-4c977eb45a48)



### Step 8: Terminate the Connection
For example, the screenshot command captures the victim’s screen and saves it in the attacker's home directory.

![last](https://github.com/user-attachments/assets/c025ebcc-046d-4b23-bf2d-24f38e99917a)



### Step 9: Terminate the connection
After completing intended operations, close the session securely.



## RESULT:
The Metasploit framework for reconnaissance is  examined successfully.
