# NSS_Mirai_Dataset
This dataset is captured from a Mirai type botnet attack on an emulated IoT network in OpenStack.

- NSS_Mirai_Dataset/dataset_1/for_fim/ : alerts coded into a FIM ready format (for both with subnet and without subnet cases)

- NSS_Mirai_Dataset/dataset_1/gateways/ : alerts captured at the individual gateways in the FIM ready format (for both with subnet and without subnet cases)

- NSS_Mirai_Dataset/dataset_1/raw_entries/ : raw alerts aggregated at the security manager

- NSS_Mirai_Dataset/dataset_1/sampled_alerts/

    final_sampled_inputs.csv : all the alerts aggregated at the security manager in a single file
    
    labeled_final_sampled_inputs.csv : all the alerts aggregated at the security manager in a single file with corresponding class labels

Detailed information on the dataset is depicted in the following work. 
Please cite it when you use this dataset for your research.

* Kalupahana Liyanage Kushan Sudheera, Dinil Mon Divakaran, Rhishi Pratap Singh, and Mohan Gurusamy, "ADEPT: Detection and Identification of Correlated Attack-Stages in IoT Networks," in IEEE Internet of Things Journal (Accepted), URL: 10.1109/JIOT.2021.3055937

- There is another dataset (dataset_2) in raw alert format captured using the same emulated IoT network, but with a different time duration.
