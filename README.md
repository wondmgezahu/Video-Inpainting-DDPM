# Video Inpainting with Conditional DDPM

This project applies a conditional Denoising Diffusion Probabilistic Model (DDPM) to the video inpainting problem, aiming to fill in missing parts of a video with content that seamlessly integrates with the rest of the video. The model takes the masked frames as conditional input and generates frames that resemble the original. 

The project was tested on the CLEVRER dataset using two types of masking techniques: stationary and variable. A resampling technique was employed to improve the consistency and realism of the generated frames.
