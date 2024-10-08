# AUTALIC: A Dataset for Anti-AUTistic Ableist Language In Context
## Encrypted Dataset

The dataset in this repository is encrypted for security reasons. 
<strong>BOTH the .gpg and .enc files contain the SAME data so you only need to download/decrypt one of them.</strong>

To decrypt the dataset, use the following command:

### MAC OS and Linux
1) .gpg file:
``gpg -d AUTALIC_all_labels.csv.gpg > AUTALIC_all_labels.csv``
2) .enc file: ``openssl enc -aes-256-cbc -d -in AUTALIC_all_labels.enc -out AUTALIC_all_labels.csv``

### Windows 
#### Command Prompt/PowerShell
1) .gpg file: ``gpg -d AUTALIC_all_labels.csv.gpg -o AUTALIC_all_labels.csv``
2) .enc file: ``openssl enc -aes-256-cbc -d -in AUTALIC_all_labels.enc -out AUTALIC_all_labels.csv``
#### Git Bash
1) .gpg file: ``gpg -d AUTALIC_all_labels.csv.gpg > AUTALIC_all_labels.csv``
2) .enc file using OpenSSL in Git Bash: ``openssl enc -aes-256-cbc -d -in AUTALIC_all_labels.enc -out AUTALIC_all_labels.csv``
