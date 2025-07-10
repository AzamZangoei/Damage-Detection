Karaj-Highway Pavement Dataset

This dataset contains accelerometer signals and GoPro images for detecting surface cracks in road pavements.
It is designed for machine learning, signal processing, and computer vision research.

📌 Dataset Overview

Data Sources:

📱 Smartphone accelerometer

📊 MEMS accelerometer sensors

📷 GoPro camera images

Purpose: Crack detection using S-transform spectrograms and image analysis.

Applications:

Structural health monitoring

Road condition assessment

Machine learning (classification, object detection)

🔗 Download KHPD

| Dataset     | Size   | Format     | Download Link          |
|----------------|--------|-----------|------------------|
| Acceleration_Signals   |  404 MB  | Excel     | https://drive.google.com/drive/folders/1fii_RHSOM6R5h0bAxC_AdjBtGycMqmV4?usp=sharing  |
| ST_Spectrogram_Accelometor   |  112 MB  | PNG        | https://drive.google.com/drive/folders/1Ve2fMpN5PFYn49mNLUTxLTyNpBdt8CBe?usp=sharing     |
| ST_Spectrogram_Smartphone |  623 MB  | PNG       | اسپکتروگرام‌ها    |
| camera images_part1 |  934 MB  | ZIP       | https://drive.google.com/file/d/1bSkSW04dNdF0HQUITcadxNXLIetRIw5L/view?usp=sharing    |
| camera images_part2 |  1.26 GB  | ZIP       | https://drive.google.com/file/d/1OPNfdCiaA95y5gDoN8AOPbLJbo-CDv_5/view?usp=sharing   |

📂 Dataset Structure

1. acceleration_signals/
   
📄 Acceleration_Signals.xlsx (Excel file with multiple sheets):

Sheet1: Raw acceleration signals

sig1_new → Smartphone accelerometer

sig2_shifted, sig3_shifted, sig4_shifted → MEMS accelerometers

Sheet2: Denoised smartphone signals (Wavelet Denoising)

Sheets 3-5: Denoised MEMS accelerometer signals

2. ST_Spectrogram_Smartphone/
   
📊 S-transform spectrograms (from smartphone signals):

Labeled as:

✅ Healthy pavement

❌ Damaged pavement

Spectrograms are cropped at 0.1s intervals

ST-sig1_new_coif55_Crop → Full spectrograms (pre-cropping)

3. ST_Spectrogram_Accelerometer/
   
📈 S-transform spectrograms (from Sensor 3 accelerometer).

5. camera_images_part1/
   
📸 GoPro images of cracked pavement surfaces.

7. camera_images_part2/
   
🛣️ GoPro images of intact (healthy) pavement surfaces.

🛠️ Usage Suggestions

Train CNN models on spectrograms for crack detection.

Apply signal processing techniques (Wavelet, S-transform).

Use YOLO for crack detection in images.

Combine sensor + image data for multimodal learning.

📬 Contact

For questions, email: a.zangoei1376@gmail.com


