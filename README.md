# NSS_Mirai_Dataset
This dataset is captured from a Mirai type botnet attack on an emulated IoT network in OpenStack. Experimental setup can be found in setup.pdf.

- NSS_Mirai_Dataset/dataset_1/for_fim/ : alerts coded into a FIM ready format (for both with subnet and without subnet cases)

- NSS_Mirai_Dataset/dataset_1/gateways/ : alerts captured at the individual gateways in the FIM ready format (for both with subnet and without subnet cases)

- NSS_Mirai_Dataset/dataset_1/raw_entries/ : raw alerts aggregated at the security manager

- NSS_Mirai_Dataset/dataset_1/sampled_alerts/

    final_sampled_inputs.csv : all the alerts aggregated at the security manager in a single file
    
    labeled_final_sampled_inputs.csv : all the alerts aggregated at the security manager in a single file with corresponding class labels
    
- There is another dataset (dataset_2) in raw alert format captured using the same emulated IoT network, but with a different time duration.

Detailed information on the dataset is depicted in the following work. 
Please cite it when you use this dataset for your research.

* Kalupahana Liyanage Kushan Sudheera, Dinil Mon Divakaran, Rhishi Pratap Singh, and Mohan Gurusamy, "ADEPT: Detection and Identification of Correlated Attack-Stages in IoT Networks," in IEEE Internet of Things Journal (Accepted), URL: 10.1109/JIOT.2021.3055937

---------------------------------------------------------------------------------------------------------------
Class | Description

Port Scan | Bots scan for open ports of IoT devices

Scan In | Bots scan for specific vulnerabilities, e.g., status of telnet, ssh ports

Login Attempts | Bots execute dictionary attack on vulnerable IoT devices

Malware Loader| Upload/Download of malware from an external source

C&C Communication (success) | Successful communication sessions with the C&C server

C&C Communication (failure) | Failed communication sessions with the C&C server

Scan Out (ports) | Compromised IoT devices scan for open ports on other IoT devices

Scan Out (login) | Compromised IoT devices carry out dictionary attack on other vulnerable IoT devices

Attack (DDoS-Volumetric) | All compromised IoT devices execute DDoS attack on a victim server

Attack (DDoS-Reflective) | All compromised IoT devices execute reflective DNS DDoS attack on a victim server

Noise | False alerts due to firmware updates, setup changes, etc.

---------------------------------------------------------------------------------------------------------------
