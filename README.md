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

📥 Download Link :

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


