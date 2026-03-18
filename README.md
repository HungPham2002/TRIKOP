# [IJCAI 2025 - Demo Track] TRIKOP: Exploring Visual Prompting Paradigms for Multi-Grade Knee Osteoarthritis Classification on MRI Images

Welcome to the GitHub repository for our web demo showcasing a diagnostic tool for knee osteoarthritis using MRI images with visual prompting.

## About TRIKOP
This web application is designed to assist in diagnosing knee osteoarthritis by analyzing MRI images with the help of visual prompting techniques. Our tool aims to provide accurate and efficient diagnosis for healthcare professionals and patients.
<p align="center">
   <img src="https://github.com/GlobalAILab/TRIKOP/blob/main/images/login_page.png" alt="Login page" width="700">
</p>

## Getting Started
To start using the diagnostic tool, follow these steps:
1. Access the [TRIKOP web application](https://gmedai.com/app/main/mri-diagnosis).
2. Log in with the following credentials:
   - **User name:** userdemo
   - **Password:** demoTRIKOP
3. Upload a compressed 3D DESS MRI knee image in **.zip format** or select any image in the box below. We have also prepared some other images for you to demo, you can access them [here](https://drive.google.com/drive/folders/1D4e7I7IyGfB4q5mg-vrc0lrMWac6UH8H?usp=drive_link). A slider has been provided for viewing different MRI image slices.
<p align="center">
<img src="https://github.com/GlobalAILab/TRIKOP/blob/main/images/upload_image.png" alt="Upload image function" width="400">
</p>

4. Once an image is selected, the system will generate various prompting methods along with illustrative images for each method.
<p align="center">
<img src="https://github.com/GlobalAILab/TRIKOP/blob/main/images/Choose_prompt_method.png" alt="Upload image function" width="400">
</p>

5. Press the "Diagnose" button with the selected prompting method, allowing the model to conduct a diagnosis and return results, including:
   - Diagnostic probabilities corresponding to each KL disease severity level.
   - An attention map displaying the baseline and visual prompting methods, enabling observation of image regions the model focuses on for decision-making (increasing redness indicates greater model attention in that region).
<p align="center">
<img src="https://github.com/GlobalAILab/TRIKOP/blob/main/images/result.png" alt="Diagnostic results" width="400">
</p>

## Support
If you have any questions, feedback, or issues related to the web demo, please feel free to contact us at gmedaiteam@gmail.com
Thank you for visiting our GitHub repository and exploring our diagnostic tool for knee osteoarthritis using MRI images with visual prompting.
