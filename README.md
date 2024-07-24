ECCV2024 Workshop paper

Title: CQS: CBAM and Query-Selection Diffusion Model for text-driven Content-aware Image Style Transfer

Abstract:Abstract Despite the advancements made in image generation and editing using diffusion models, there remains a significant challenge in preserving content effectively during pixel deformation throughout style transfer. Content preservation is crucial for improving the usability of image editing tools.
One strategy to address this challenge involves determining areas of high content within an image using a text prompt and preserving them while stylizing the 
image during diffusion’s reverse process. Our proposed method tackles this by refining features through Convolution Block Attention Module, and then, anchoring representative points in these content-rich areas for both the source and generated images through our query selection module. We selectively focus on these 
anchor points to maintain more important features by those modules. Additionally, we utilize contrastive learning in a self-supervised manner to enhance content preservation while transferring style.
By integrating these techniques into a conventional diffusion model, our method eliminates the need for fine-tuning or auxiliary networks, speeding up 
the inference process compared to other diffusion methods. Our experiments demonstrate the superiority of our approach, particularly in preserving content of 
the image during editing, surpassing both other diffusion models and GAN-based approaches.

