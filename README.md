# Diffusion based Image Synthesis: Human Faces

This repository presents a comprehensive demonstration of a Denoising Diffusion Probabilistic Model. The model is trained using a standard L1 loss metric between timesteps and exhibits the ability to generate high-resolution 256x256 images of human faces. Each image generation process requires an approximate duration of 4 seconds when utilizing the standard free Google Colaboratory hardware. The model execution is supported by a memory footprint of approximately 2 GB of VRAM.

<h2 align="center"></h1>

<p float="left" align="middle">
  <img src="https://media.discordapp.net/attachments/911296727103983678/1117571962160545863/d0857be2-9f10-419f-884e-f60aed8d8ae1.png" width="30%" hspace="10"/>
  <img src="https://media.discordapp.net/attachments/911296727103983678/1117571962798100631/TESTE_1.png" width="30%" hspace="10"/> 
  <img src="https://media.discordapp.net/attachments/911296727103983678/1117571963578241064/7_1.png" width="30%" hspace="10"/> 
</p>

The model underwent an extensive training process for a duration of 48 hours, leveraging the computational power of two Nvidia T4 GPUs. The training procedure utilized the [140k-real-fake-faces](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces). To enhance the model's performance, future enhancements could involve incorporating latent procedures through the utilization of models such as VQ-GAN or VQ-VAE. These models can encode the images into more compact representations, leading to improved efficiency and effectiveness. Additionally, the inclusion of Perceptual Losses during the training phase could further refine the model's output quality and visual fidelity.

<p float="left" align="middle">
  <img src="https://media.discordapp.net/attachments/911296727103983678/1117571963108458586/da6319e3-a314-4c84-91f9-dc940f8de485.png" width="30%" hspace="10"/>
  <img src="https://media.discordapp.net/attachments/911296727103983678/1117571966682013837/b468b357-0f2b-470f-a2e5-3ef0e7b02923.png" width="30%" hspace="10"/> 
  <img src="https://media.discordapp.net/attachments/911296727103983678/1117571963364319363/7c39058b-044a-4406-a448-b62df64b3a40.png" width="30%" hspace="10"/> 
</p>

<h2 align="center"></h1>

<p float="left" align="middle">
  <img src="https://cdn.discordapp.com/attachments/911296727103983678/1117573202458198087/Yxtz20oOAAAAABJRU5ErkJggg.png" width="100%" hspace="10"/>
</p>
<p float="left" align="middle">
  <img src="https://cdn.discordapp.com/attachments/911296727103983678/1117573776037650432/B1ZGJnpSYqHjAAAAAElFTkSuQmCC.png" width="100%" hspace="10"/>
</p>
