# Receipts OCR and Information Extraction

This project studies receipt understanding on the [SROIE] (https://rrc.cvc.uab.es/?ch=13) task, aiming to extract four key fields from receipt images: **company, date, address, and total**.

## Overview
We explore three approaches for extracting information from receipts:

- **Rule-based baseline**  
  A simple approach applied directly at test time for key-field extraction.

- **Layout-aware extraction (LayoutLMv3)**  
  Utilizes layout and textual features to improve extraction accuracy.

- **End-to-end document understanding (DONUT)**  
  A full end-to-end model for document understanding and key-field extraction.

## Evaluation
Model performance is evaluated using metrics such as:

- Field-level **accuracy**  
- Comparison across **different extraction pipelines**  

### Key Findings
- **LayoutLMv3** improves accuracy by leveraging document layout information.  
- **DONUT** shows strong end-to-end performance with minimal preprocessing.  
- The **rule-based approach** serves as a fast and interpretable baseline.

## Deployment
The models can be deployed for **automated receipt processing**, allowing:

- Extraction of structured information from receipt images.  
- Comparison of multiple extraction strategies.  

## Features
- Multiple extraction approaches for comparison  
- End-to-end document understanding  
- Rule-based baseline for fast implementation  
- Layout-aware modeling for structured documents  

## Tech Stack
- PyTorch  
- Transformers (Hugging Face)  
- Optical Character Recognition (OCR)  
- LayoutLMv3  
- DONUT  
- Rule-based information extraction  
- Document Understanding  

## Team Members
**- Le Sy Han – hanls.23bi14150@usth.edu.vn**
- Nguyen Quang Minh - minhnq.22ba13221@usth.edu.vn
- Nguyen Cao Manh Thang - thangncm.23bi14403@usth.edu.vn
- Nguyen Trong Bach - bachnt.23bi14057@usth.edu.vn
