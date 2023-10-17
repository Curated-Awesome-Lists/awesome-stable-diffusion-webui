# Awesome sd-webui

Automatic1111 (a1111) Stable Diffusion WebUI serves as an interactive browser interface for Stable Diffusion, a generative model designed to create realistic images from textual or visual inputs. The interface, built on Gradio, simplifies the creation of web-based interaction for machine learning models.

With Stable Diffusion WebUI, users can explore a plethora of features such as:

- Traditional text-to-image and image-to-image modes
- Easy installation and execution with a single-click script (requires python and git installation)
- Outpainting for extending the content of an image outward
- Inpainting for filling in gaps or missing parts within an image
- Color Sketch for creating color-filled drafts
- Prompt Matrix to facilitate efficient image generation
- Stable Diffusion Upscale for enhancing image resolution
- Attention feature to emphasize specific parts of the text that the model should prioritize

## Table of Contents

- [GitHub projects](#github-projects)
- [Articles & Blogs](#articles-&-blogs)
- [Online Courses](#online-courses)
- [Books](#books)
- [Research Papers](#research-papers)
- [Videos](#videos)
- [Tools & Software](#tools-&-software)

## GitHub projects

- [WebUI extension for ControlNet](https://github.com/Mikubill/sd-webui-controlnet) :star: 13371
- [📷 EasyPhoto | Your Smart AI Photo Generator.](https://github.com/aigc-apps/sd-webui-EasyPhoto) :star: 2873
- [Segment Anything for Stable Diffusion WebUI](https://github.com/continue-revolution/sd-webui-segment-anything) :star: 2657
- [Roop extension for StableDiffusion web-ui](https://github.com/s0md3v/sd-webui-roop) :star: 2609
- [Deforum extension for AUTOMATIC1111's Stable Diffusion webui](https://github.com/deforum-art/sd-webui-deforum) :star: 2180
- [Booru style tag autocompletion for AUTOMATIC1111's Stable Diffusion web UI](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete) :star: 2081
- [Extension for improving the user experience of prompt/negative prompt input box](https://github.com/Physton/sd-webui-prompt-all-in-one) :star: 1754
- [Mov2mov plugin for Automatic1111/stable-diffusion-webui](https://github.com/Scholar01/sd-webui-mov2mov) :star: 1648
- [Additional Networks for Stable Diffusion WebUI](https://github.com/kohya-ss/sd-webui-additional-networks) :star: 1518
- [Lobe theme - The modern theme for stable diffusion webui](https://github.com/lobehub/sd-webui-lobe-theme) :star: 1417
- [Depth map library for use with the Control Net extension](https://github.com/jexom/sd-webui-depth-lib) :star: 1279
- [Auto1111 extension implementing text2video diffusion models](https://github.com/kabachuha/sd-webui-text2video) :star: 1122
- [AnimateDiff for AUTOMATIC1111 Stable Diffusion WebUI](https://github.com/continue-revolution/sd-webui-animatediff) :star: 1068
- [Cutoff - Cutting Off Prompt Effect](https://github.com/hnmr293/sd-webui-cutoff) :star: 1002
- [Set prompt to divided region](https://github.com/hako-mikan/sd-webui-regional-prompter) :star: 971
- [Extension for stable-diffusion-webui to load lycoris models](https://github.com/KohakuBlueleaf/a1111-sd-webui-lycoris) :star: 775
- [StableSR for Stable Diffusion WebUI - Ultra High-quality Image Upscaler](https://github.com/pkuliyi2015/sd-webui-stablesr) :star: 755
- [Stable Diffusion web UI bilingual localization extensions](https://github.com/journey-ad/sd-webui-bilingual-localization) :star: 696

## Articles & Blogs

- [Cloud integration with sd-webui tutorial: Say goodbye to “CUDA out of memory” errors](https://medium.com/@anyisalin/cloud-integration-with-sd-webui-tutorial-say-goodbye-to-cuda-out-of-memory-errors-cd42a6722b76) : Discusses extensions for AUTOMATIC1111 webui that enable transfer of txt2img/img2img/controlnet requests load to the cloud.
- [Setting up Stable Diffusion on MacOS for generating QR codes and other experiments](https://plgah.medium.com/setting-up-stable-diffusion-on-macos-for-generating-qr-codes-and-other-experiments-66275818563) : An introduction and guide for creating artsy AI QR codes using Stable Diffusion and ControlNet on Mac.
- [Create Your Own Stable Diffusion UI on AWS in Minutes](https://towardsdatascience.com/create-your-own-stable-diffusion-ui-on-aws-in-minutes-35480dfcde6a) : Tutorial on deploying the Automatic1111 Web UI on an AWS EC2 instance equipped with a GPU for Stable Diffusion.
- [SDXL Refiner on AUTOMATIC1111](https://medium.com/@anyisalin/sdxl-refiner-on-automatic1111-56979b83ab8f) : Details the merged support for SDXL refiner in Stable Diffusion WebUI.
- [SDXL ControlNet on AUTOMATIC1111](https://medium.com/@anyisalin/sdxl-controlnet-on-automatic1111-50ff3b40fbf1) : Updates about the support for SDXL ControlNet published by sd-webui-controlnet.
- [How To Setup ControlNet For Stable Diffusion AI—Step-By-Step Guide](https://medium.com/generative-ai/how-to-setup-controlnet-for-stable-diffusion-ai-step-by-step-guide-aafff8996719) : Provides a step-by-step guide for setting up ControlNet model for Stable Diffusion AI.
- [Accelerating Image Generation and Utilizing ControlNet on AMD GPU, Nvidia, Cheap GPU, and macOS](https://medium.com/@anyisalin/accelerating-image-generation-and-utilizing-controlnet-on-amd-gpu-nvidia-cheap-gpu-and-macos-21abb1fef3d) : Explores the sd-webui-cloud-inference extension for forwarding generation requests of txt2img/img2img/controlnet/vae models.
- [How To Use SDXL in Automatic1111 Web UI — SD Web UI vs ComfyUI Easy Local Install Tutorial](https://medium.com/@furkangozukara/how-to-use-sdxl-in-automatic1111-web-ui-sd-web-ui-vs-comfyui-easy-local-install-tutorial-80891b2c5120) : Demonstrates how to install and use SDXL in the Automatic1111 Web UI.
- [Updating AUTOMATIC1111/stable-diffusion-webui to Torch 2 for amazing performance](https://medium.com/@inzaniak/updating-automatic1111-stable-diffusion-webui-to-torch-2-for-amazing-performance-50366dcc9bc1) : Provides instructions for updating AUTOMATIC1111/stable-diffusion-webui to Torch 2 for improved image generation speed.
- [How to install Stable Diffusion WebUI and ControlNet 1.1 on Ubuntu 22.04](https://dev.to/felipelujan/set-up-stable-difussion-webui-and-controlnet-on-ubuntu-2204-hbm) : Tutorial explaining the configuration of Ubuntu 22.04 with an Nvidia GPU to utilize Stable Diffusion WebUI and ControlNet.
- [sd-webui 教程：告别“CUDA内存不足”错误。](https://medium.com/@anyisalin/sd-webui%E6%95%99%E7%A8%8B-%E5%91%8A%E5%88%AB-cuda%E5%86%85%E5%AD%98%E4%B8%8D%E8%B6%B3-%E9%94%99%E8%AF%AF-c7def2ca3c05) : A Medium article that provides a tutorial on how to resolve "CUDA out-of-memory" errors for sd-webui and includes extensions for cloud inference.
- [ComfyUI and Automatic1111 SD WebUI Sharing Models](https://medium.com/mlearning-ai/comfyui-and-automatic1111-sd-webui-sharing-models-a2b69e0309d5) : Learn how to install, extend, and use prompts for Stable Diffusion using ComfyUI and Automatic1111 SD WebUI.
- [ControlNet and T2I-Adapter, the icebreaker solution for precise control of AI image generation](https://medium.com/@catmus2048/controlnet-and-t2i-adapter-the-icebreaker-solution-for-precise-control-of-ai-image-generation-ef61258139c3) : Explore the ControlNet feature of Stable Diffusion, which allows precise control of AI image generation.
- [Stable Diffusion Ultimate Guide pt. 5: ControlNet](https://medium.com/@inzaniak/stable-diffusion-ultimate-guide-pt-5-controlnet-6f45e9614119) : A comprehensive guide on how to use ControlNet to fine-tune image generation in Stable Diffusion.
- [Free run SDXL on https://nogpu-webui.com](https://medium.com/@anyisalin/free-run-sdxl-in-https-nogpu-webui-com-9de322f67f44) : An announcement of support for SDXL 0.9 on https://nogpu-webui.com, with instructions on how to use it.
- [How to Create QR Code Art using Stable Diffusion](https://ihsavru.medium.com/how-to-create-qr-code-art-using-stable-diffusion-58c5e7e55fcb) : A tutorial on using Stable Diffusion to generate QR code art.
- [How to create controlled poses and styles using Stable Diffusion and ControlNets](https://medium.com/mlearning-ai/how-to-create-controlled-poses-and-styles-using-stable-diffusion-and-controlnets-3cba36418401) : Learn how to use ControlNets with Stable Diffusion to have more control over the generated output images.
- [RunDiffusion free alternative: https://nogpu-webui.com](https://medium.com/@anyisalin/rundiffusion-free-alternative-https-nogpu-webui-com-cccebf3b0860) : An announcement of a free alternative website for Stable Diffusion Web UI, which doesn't require a GPU.
- [A Simple Way To Run Stable Diffusion 2.0 Locally On Your PC](https://medium.com/geekculture/a-simple-way-to-run-stable-diffusion-2-0-locally-on-your-pc-no-code-guide-3beb911e444c) : An easy-to-follow guide on running Stable Diffusion 2.0 on your local PC with Web UI, without any coding.
- [How to Run Stable Diffusion on EC2](https://medium.com/@meadowrun/how-to-run-stable-diffusion-on-ec2-e447333d820) : Learn how to run the latest text-to-image model of Stable Diffusion on EC2 using Meadowrun.

## Online Courses

- [Stable Diffusion Generative AI Art Generation Zero To Hero | Udemy](https://www.udemy.com/course/stable-diffusion-dreambooth-lora-zero-to-hero/)
- Become a Master of Stable Diffusion, SDXL, DreamBooth, LoRA, DeepFake Roop, Fine Tuning, Training, Video To Animation.
- [Beginner's Guide to Stable Diffusion with Automatic1111 | Udemy](https://www.udemy.com/course/beginners-guide-to-stable-diffusion/)
- Complete introduction to the magical art of designing images using generative AI. Learn Stable Diffusion and create stunning designs with A1111.
- [Cypress: Web Automation Testing from Zero to Hero | Udemy](https://www.udemy.com/course/cypress-web-automation-testing-from-zero-to-hero/)
- E2E Web UI Automation from scratch using Cypress v13.
- [Stable Diffusion 101: Create Custom Anime Art with AI | Udemy](https://www.udemy.com/course/stable-diffusion-101-create-custom-anime-art-with-ai/)
  Comprehensive training to fully master AI image generation with Stable Diffusion. Learn techniques and tricks for creating custom anime art.
- [StableDiffusionを無料で動かせる神サービス"SageMaker"を使って ...](https://www.udemy.com/course/stablediffusion_sagemaker/): Learn how to implement Stable Diffusion WebUI using SageMaker, a free GPU development environment for image generation.

## Books

- [AWS Marketplace: imAgine-eCloudrover AIGC text to image solution](https://aws.amazon.com/marketplace/pp/prodview-f22o5uwhgudk6): This solution offers Stable Diffusion Webui pre-installed with the AWS SageMaker Extension, allowing for easy text-to-image and image-to-image generation.
- [AWS Marketplace: imAgine-eCloudrover AIGC text to image solution](https://aws.amazon.com/marketplace/pp/prodview-ohjyijddo2gka): This solution provides an AMI based on Deep Learning AMI GPU PyTorch, with Stable Diffusion WebUI integrated for high-quality text-to-image and image-to-image generation.
- [Amazon.com: List of over 1000 prompts for NovelAI and local use](https://www.amazon.com/List-over-prompts-NovelAI-local-ebook/dp/B0BS8PVVCF): This book provides a collection of prompts for use with AUTOMATIC1111/Stable Diffusion web UI, covering various aspects of image generation.


## Research Papers

- [arXiv:2310.04672v1 [cs.CV] 7 Oct 2023](https://arxiv.org/pdf/2310.04672) 📄: This paper proposes a WebUI plugin called EasyPhoto for generating AI portraits using a novel approach.
- [FABRIC: Personalizing Diffusion Models with Iterative Feedback](https://arxiv.org/pdf/2307.10159) 📄: This study explores strategies for incorporating iterative human feedback into diffusion-based text-to-image models.
- [(PDF) Designing interfaces for text-to-image prompt engineering using stable diffusion models: A human-AI interaction approach](https://www.researchgate.net/publication/374675790_Designing_interfaces_for_text-to-image_prompt_engineering_using_stable_diffusion_models_a_human-AI_interaction_approach/download) 📄: This paper investigates user behavior patterns in finding prompts and interacting with text-to-image generative AI services.
- [A Creative Industry Image Generation Dataset Based on Captions](https://arxiv.org/pdf/2211.09035) 📄: This paper utilizes state-of-the-art image generation models to generate candidate reference images based on prompts and sketches.
- [ModelScope Text-to-Video Technical Report](https://arxiv.org/pdf/2308.06571) 📄: Introducing ModelScopeT2V, a text-to-video synthesis model evolved from a text-to-image synthesis model.
- [A Comprehensive Survey on Segment Anything Model for Vision](https://arxiv.org/pdf/2305.08196) : This paper discusses the challenges and opportunities in computer vision and multimodal learning research.
- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752) : This paper presents a novel approach to image synthesis using diffusion models, achieving state-of-the-art results in image generation.


## Videos

- [Deforum Video Input Tutorial using SD WebuI - YouTube](https://www.youtube.com/watch?v=EM1yoVh_q00): Feb 10, 2023 - In this video, I give a quick demo of how to use Deforum's video input option using Stable Diffusion WebUI.
- [Installing ControlNet when using the Stable Diffusion Web UI - YouTube](https://www.youtube.com/watch?v=uUizoFA7OYY): Mar 8, 2023 - Learn how to install the sd-webui-controlnet extension for Automatic1111 to use ControlNet with Stable Diffusion.
- [How To Use SDXL in Automatic1111 Web UI - SD Web UI vs ...](https://www.youtube.com/watch?v=eY_v5IR4dUQ): Jul 20, 2023 - Updated for SDXL 1.0. Our beloved #Automatic1111 Web UI now supports Stable Diffusion X-Large (#SDXL). See how to use it in this video.
- [How to Install ControlNet for Stable Diffusion's Automatic1111 Webui](https://www.youtube.com/watch?v=LnqNyd21x9U): Feb 20, 2023 - In this video, I'll show you how to install ControlNet, a group of additional models that allow better control in Stable Diffusion.
- [sd webui one click install bat - YouTube](https://www.youtube.com/watch?v=_bxa8T_dur0): Apr 20, 2023 - Quick guide on how to install stable-diffusion-webui using a single-click script.
- [Strategy of generating stunning images easy and efficient using SD - YouTube](https://www.youtube.com/watch?v=6t26MFKzEbo): Jun 1, 2023 - Learn the strategy and workings of Stable Diffusion WebUI Automatic1111 for generating impressive images easily and efficiently.
- [Create Animations using Img2Img- Stable Diffusion WebUI Tutorial](https://www.youtube.com/watch?v=sEaR9xZEF6E): Learn how to use Stable Diffusion's Img2Img translation model to create amazing animation results.
- [EASY Text to Video in Stable Diffusion with Automatic1111 WebUI](https://www.youtube.com/watch?v=lxm8lYXKle4): Explore how to generate video output within the Automatic1111 webUI using the sd-webui-modelscope-text2video models.
- [Inpaint Anything in Stable Diffusion WebUI - Just 3 clicks!](https://www.youtube.com/watch?v=yDYhIuS8hJ4): Discover how to use Automatic1111 Web UI and the sd-webui-inpaint-anything extension to easily inpaint any content.
- [AI Images | Installing Stable Diffusion and the Automatic1111 WebUI](https://www.youtube.com/watch?v=m_Bx1tTC8eE): Get step-by-step instructions for installing Stable Diffusion and the Automatic1111 WebUI for creating AI-generated images.
- [SD Web UI Becomes Easier! Quick custom UI layout stable diffusion](https://www.youtube.com/watch?v=ceNJjNn1zKU): Learn how to customize the user interface appearance of Stable Diffusion for a personalized experience.
- [Stable Diffusion 2.0 Quickstart (webUI, local installation etc)](https://www.youtube.com/watch?v=cL_ZYdkIqBU): Follow along with this tutorial to quickly start using Stable Diffusion 2.0, covering webUI usage, prompting, and image generation.

## Tools & Software

- [Stable Diffusion Web UI Cloud Inference](https://alternativeto.net/software/sd-webui-cloud-inference/about/): This extension allows offloading of stable diffusion web UI image generation requests to the cloud, making it easier to generate images without worrying about computer configuration.
- [Stable Diffusion v 2.1 web UI download | SourceForge.net](https://sourceforge.net/projects/stable-diffusion-web-ui.mirror/): Lightweight Stable Diffusion v 2.1 web UI with features like text-to-image, image-to-image, depth2image, inpainting, and upscaling. Built using Gradio app.
- [Stable Diffusion WebUI](some_link) 🌐: An interactive browser interface for Stable Diffusion, facilitating the generation of realistic images from textual or visual inputs. Features include text-to-image and image-to-image modes, outpainting, inpainting, color sketch, prompt matrix, upscale, and attention feature. (Add appropriate link)
- [A111 Stable Diffusion WEB UI](some_link) 🖼️: An alternative to NMKD Stable Diffusion GUI, this tool serves as an interface for creating AI-generated art with Stable Diffusion. (Add appropriate link)
- [Gradio](some_link) 🚀: A library used to build user interfaces for machine learning models. It simplifies the creation of web-based interactions and can be used as a foundation for building Stable Diffusion's web interface. (Add appropriate link)



---

This initial version of the Awesome List was generated with the help of the [Awesome List Generator](https://github.com/alialsaeedi19/GPT-Awesome-List-Maker). It's an open-source Python package that uses the power of GPT models to automatically curate and generate starting points for resource lists related to a specific topic. 
