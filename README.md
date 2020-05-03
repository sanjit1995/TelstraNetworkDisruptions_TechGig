# TelstraNetworkDisruptions_TechGig
Classification of severity types from TechGig Challenges

Problem Statement:

Telstra Network Disruptions
In their first recruiting competition, Telstra is challenging data scientists to predict the severity of service disruptions on their network. Using a dataset of features from their service logs, you're tasked with predicting if a disruption is a momentary glitch or a total interruption of connectivity.

Telstra is on a journey to enhance the customer experience - ensuring everyone in the company is putting customers first. In terms of its expansive network, this means continuously advancing how it predicts the scope and timing of service disruptions. Telstra wants to see how you would help it drive customer advocacy by developing a more advanced predictive model for service disruptions and to help it better serve its customers.

This challenge was crafted as a simulation of the type of problem you might tackle as a member of the team at Telstra.



The goal of the problem is to predict Telstra network's fault severity at a time at a particular location based on the log data available. Each row in the main dataset (train.csv, test.csv) represents a location and a time point. They are identified by the "id" column, which is the key "id" used in other data files. 

Fault severity has 3 categories: 0,1,2 (0 meaning no fault, 1 meaning only a few, and 2 meaning many). 

Different types of features are extracted from log files and other sources: event_type.csv, log_feature.csv, resource_type.csv, severity_type.csv. 

Note: “severity_type” is a feature extracted from the log files (in severity_type.csv). Often this is a severity type of a warning message coming from the log. "severity_type" is categorical. It does not have an ordering. “fault_severity” is a measurement of actual reported faults from users of the network and is the target variable (in train.csv).

File descriptions
-> train.csv - the training set for fault severity
-> test.csv - the test set for fault severity
-> sample_submission.csv - a sample submission file in the correct format
-> event_type.csv - event type related to the main dataset
-> log_feature.csv - features extracted from log files
-> resource_type.csv - type of resource related to the main dataset
-> severity_type.csv -  severity type of a warning message coming from the log
