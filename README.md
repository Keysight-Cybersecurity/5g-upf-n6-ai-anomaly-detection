# 5g-upf-n6-ai-anomaly-detection
AI-based detection of DoS and DDoS attacks on the 5G UPF N6 interface using PCAP data and CyPerf traffic. Focus on model training, evaluation, and deployment for telecom security use cases.

# Title
5G UPF N6 AI Anomaly Detection

# Goal
Build an AI-based system to detect DoS and DDoS traffic on the 5G UPF N6 interface using PCAP data and CyPerf traffic.

# Scope
• 5G core security
• UPF N6 interface
• DoS and DDoS detection
• PCAP processing
• AI model training and testing
• Metrics: precision, recall, F1, ROC-AUC

# Data
• PCAP files from CyPerf
• Labeled normal and attack traffic
• Flow features from PCAP

# Pipeline
• Capture traffic
• Parse PCAP
• Extract features
• Train model
• Test model
• Report results

# Tools
• Python 3.10+
• scikit-learn
• pandas
• numpy
• tshark
• Wireshark
• CyPerf

# Structure
• data/raw
• data/processed
• src/pcap
• src/features
• src/models
• src/eval
• reports

# Rules
• No sensitive data
• No Keysight internal files
• Commit clean code only
• Use small test PCAPs only

# Next step
• Add sample PCAP
• Build feature extractor
• Train baseline model
