## Speech Understanding Programming Assignment 2

This repository is dedicated to the Speech Understanding Assignment 2 from Spring 2024 at IIT-Jodhpur.

### Question-1 (VoxCeleb1-H Dataset)

| Models               | Equal Error Rate (EER) |
|----------------------|------------------------|
| Unispeech-sat        |       15.04%           |
| Wavlm-base-plus      |       13.30%           |
| Wavlm-base           |       14.85%           |

### Question-1 (Kathbath Dataset)

| Models               | Equal Error Rate (EER) |
|----------------------|------------------------|
| Unispeech-sat        |       49.97%           |
| Wavlm-base-plus      |       50.00%           |
| Wavlm-base           |       50.00%           |

### Question-1 (After finetuned)

| Models               | Equal Error Rate (EER) |
|----------------------|------------------------|
| Unispeech-sat        |       5.00%            |


### Question-2

| Mixture Type | Before Fine-tuning                  | After Fine-tuning                   |
|--------------|-------------------------------------|-------------------------------------|
| Mix Clean    | SISNRi: -22.52 dB, SDRi: 37.40 dB  | SISNRi: -27.94 dB, SDRi: 27.98 dB  |
| Mix Both     | SISNRi: -22.89 dB, SDRi: 36.90 dB  | SISNRi: -28.97 dB, SDRi: 23.80 dB  |
| Mix Single   | SISNRi: -14.85 dB, SDRi: 40.18 dB  | SISNRi: -24.04 dB, SDRi: 25.35 dB  |

