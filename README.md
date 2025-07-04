# Gradio-text-to-image-generator
This project implements a Gradio-based for text-to-image generation using the Hugging Face diffusers library. It offers users enhanced control over the image generation process through a simple, interactive interface.

Key features include:

Multi-Model Selection: Users can choose between different Stable Diffusion models, specifically SDXL (Stable Diffusion XL) and Stable Diffusion 1.5, allowing for varied aesthetic and quality outputs.

Implementation Detail: To ensure efficiency and a smooth user experience, both model pipelines are pre-loaded into memory when the application starts. This avoids slow re-downloads and re-initializations during runtime, enabling rapid model switching based on user preferences.

Configurable Image Dimensions: Users can precisely control the output image width and height via dedicated sliders, enabling custom aspect ratios and resolutions.

Adjustable CFG Scale: A slider is provided to modify the Classifier-Free Guidance (CFG) scale. This parameter allows users to control how strongly the generated image adheres to the provided text prompt (higher values lead to closer adherence).

The application leverages Python and PyTorch for the backend image generation. After successful generation, the resultant image is displayed directly within the Gradio interface for immediate review, as shown below.![Alt text for the image](C:\Users\asus\Desktop)
