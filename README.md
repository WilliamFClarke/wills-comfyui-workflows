#

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images\wills-comfyui-logo-circle.png" alt="Logo" width="200" height="200">
  </a>

  <h1 align="center">Wills ComfyUI Workflows</h1>

  <p align="center">
    ComfyUI Workflows for AI Image Generation
    <br />
</div>

## About The Project

Stable Diffusion is a new generative model that uses a diffusion process to generate images. This repository stores the workflow for generating images in the ComfyUI project.

This workflow included supportfor:

- SDXL base and Refiner models
- LoRA
- VAE
- Face Detailer

### Rquiremnets

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
- [Stable Diffusion XL](https://huggingface.co/docs/diffusers/api/pipelines/stable_diffusion/stable_diffusion_xl)
- [ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager)
- [ComfyUI-Impact-Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack)

### Models

- [SAM Model](https://huggingface.co/spaces/jbrinkma/segment-anything/blob/main/sam_vit_b_01ec64.pth) must be added to the `\ComfyUI\models\sams` folder
- [BBOX Model](https://huggingface.co/Bingsu/adetailer/blob/main/face_yolov8m.pt) must be added to the `ComfyUI\models\ultralytics\bbox` folder

### Getting started

Run ComfyUI and Load the `will_diffusion_worfklow.json` workflow from the UI.

if you dont want to use a LoRA you can simply bypass the `Load LoRA` node.

<img src="images\wills-comfyui-workflow-image.jpg" alt="Workflow">

<p align="right">(<a href="#readme-top">back to top</a>)</p>
