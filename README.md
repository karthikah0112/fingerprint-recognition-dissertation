# Impact of Image Compression and Format Conversion on Fingerprint Recognition

Author: Karthik Ashok Honguntikar  
Institution: University of Plymouth  
Degree: MSc in Cybersecurity  
Date: June 2025  

📄 Project Overview

This repository supports the MSc dissertation titled:

"Impact of Image Compression and Format Conversion on Fingerprint Recognition: Exploring Security and Performance Trade-Offs"

The research explores how different image compression formats (**JPEG, PNG, BMP, WebP**) and compression levels (**20% and 60%**) impact the performance of fingerprint recognition systems. The study evaluates biometric accuracy using the following metrics:

- False Acceptance Rate (FAR)
- False Rejection Rate (FRR)
- Equal Error Rate (EER)

Experiments were conducted using the Neurotechnology VeriFinger SDK, assessing how quality degradation through compression affects recognition performance across both high- and low-quality fingerprint images.

⚙️ Tools & Technologies

- Neurotechnology VeriFinger SDK: Used for fingerprint matching and biometric performance analysis. ( https://www.neurotechnology.com/verifinger.html )
- Microsoft Visual Studio: Used to manage preprocessing workflows and SDK integration.(https://visualstudio.microsoft.com)
- Image Editors (e.g., Photoshop, GIMP, IrfanView): Used for format conversion and image compression.
- Microsoft Excel: Used to record and analyze experiment results.


 📁 Repository Contents

- `dissertation.pdf` – Full MSc dissertation.
- `experiment-data.xlsx` – Spreadsheet containing detailed experiment results and biometric performance metrics.
- `fingerprint-samples/` – Directory containing both high-quality and simulated low-quality fingerprint images used in the experiments.
- `screenshots/` – Visuals of matching scores, SDK interface, and minutiae comparisons used for analysis and in the dissertation.

📊 Datasets

- High-Quality Fingerprint Images**:  
  Obtained from the Contactless Fingerprint Dataset provided by  
  [The Hong Kong Polytechnic University](https://www4.comp.polyu.edu.hk/~csajaykr/myhome/database_request/ContactlessFP/)

- Low-Quality / Noisy Fingerprint Images:  
  Sourced from the FVC2004 Database, available at  
  [http://bias.csr.unibo.it/fvc2004/default.asp](http://bias.csr.unibo.it/fvc2004/default.asp)

These datasets simulate real-world conditions, helping evaluate the effect of compression on varying fingerprint qualities.

🎥 Experiment Video

A full walkthrough of the fingerprint recognition experiments is available on YouTube:  
👉 [Watch the experiment video here](#) https://youtu.be/M3e6xR3-ai4

📘 Dissertation Access

A full copy of the dissertation is available in this IMPACT OF IMAGE COMPRESSION AND FORMAT CONVERSION ON
FINGERPRINT RECOGNITION: EXPLORING SECURITY AND PERFORMANCE TRADE-OFFS.pdf
 
Alternatively, you can request access through the University of Plymouth Learning & Teaching repository.

❗ Note

This project does not include custom source code. All analyses were performed using third-party tools and SDKs on pre-existing fingerprint datasets.

📬 Contact

For questions or academic collaboration, feel free to reach out:

Karthik Ashok Honguntikar  
📧 Email: karthikah0112@gmail.com 


🛡️ This work contributes to biometric security research, highlighting how image fidelity directly impacts the reliability of authentication systems.




