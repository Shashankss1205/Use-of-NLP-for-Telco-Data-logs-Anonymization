# Use-of-NLP-for-Telco-Data-logs-Anonymization
This work is a solution to the Coding Challenge for LFN (Thoth) Mentorship project. It aims to provide a robust and scalable solution for anonymizing web server access logs while maintaining data integrity and privacy compliance. **The answers to the questions asked in the coding challenge can be found at the last of the .IPYNB file provided.**

## Overview
This project repo provides a Python script for anonymizing web server access logs to protect personally identifiable information (PII) while preserving the log's structure and content for analysis. The script utilizes various techniques such as regex pattern matching, named entity recognition (NER), language model-based anonymization, and many more totallin to **11 distinct methods**.

## Features
- Parsing and processing of web server access logs
- Anonymization of IP addresses, URLs, user agents, and other sensitive information
- Detection and anonymization of named entities using NER
- Anonymization using language model-based approaches
- Visualization of log data trends
- Handling missing values, duplicates, and unnecessary data.
- Encoding and one-hot encoding of categorical variables
- Data masking and hashing for additional privacy protection
- Integration with external libraries such as Presidio, gnupg, Hugging Face Transformers, and more.

## Dependencies
- Python 3
- Pandas
- Numpy
- TQDM
- Matplotlib
- Re
- Scikit-learn
- SpaCy
- GnuPG
- Hugging Face Transformers
- OpenAI (for language model-based anonymization)

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests for any improvements or bug fixes.

## Acknowledgments
- Special thanks to the contributor for designing this coding challenge and the open-source libraries used in this project.

## Contact
For any inquiries or support, please contact shashankshekharsingh1205@gmail.com.
