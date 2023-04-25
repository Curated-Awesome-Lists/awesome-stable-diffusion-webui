# Awesome Stable Diffusion WebUI Resources

A curated list of awesome resources related to Stable Diffusion WebUI, a browser interface based on Gradio library for Stable Diffusion.

## Introduction

Stable Diffusion WebUI is a browser interface for Stable Diffusion, a generative model that can create realistic images from text or image inputs. It is based on Gradio, a library that allows you to create interactive web interfaces for your machine learning models.

Stable Diffusion WebUI has many features, such as:

- Original txt2img and img2img modes
- One click install and run script (but you still must install python and git)
- Outpainting
- Inpainting
- Color Sketch
- Prompt Matrix
- Stable Diffusion Upscale
- Attention, specify parts of text that the model should pay more attention to


## Content

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Popular Plugins](#popular-plugins)
- [Tools](#tools)
- [Tutorials and Articles](#tutorials-and-articles)
- [Videos](#videos)
- [Community](#community)
- [Contributing](#contributing)



## Installation

To install Stable Diffusion WebUI, you need to have Python 3.8 or higher and Git installed on your system. Then, you can follow these steps:

1. Clone the GitHub repository: `git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git`
2. Change directory to the cloned repository: `cd stable-diffusion-webui`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the web interface: `python webui.py`

Alternatively, you can use Docker to run Stable Diffusion WebUI without installing anything on your system. You can find the instructions on how to use Docker [here](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Installation-and-run-on-NVidia-GPUs#docker).

## Usage

To use Stable Diffusion WebUI, you need to open a web browser and go to the URL that is displayed in the terminal after running the web interface. You will see a dashboard with different tabs for different modes of generation.

You can choose between txt2img, img2img, outpainting, inpainting, color sketch, prompt matrix, and upscale modes. Each mode has different options and settings that you can adjust according to your preferences.

You can also use the attention feature to specify parts of text that the model should pay more attention to by using parentheses and optional weights. For example:

- `a man in a ((tuxedo))` - will pay more attention to tuxedo
- `a man in a (tuxedo:1.21)` - alternative syntax with weight
- select text and press Ctrl+Up or Ctrl+Down to automatically adjust attention to selected text

You can find more details and examples on how to use each mode [here](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki).

## Popular Plugins

## Popular Plugins

Stable Diffusion WebUI supports plugins that extend its functionality and add new features. Some of the popular plugins are:

- [Stable Diffusion Variations](https://github.com/AUTOMATIC1111/stable-diffusion-variations) - A plugin that adds new models and options for Stable Diffusion WebUI, such as UNCLIP-H and UNCLIP-L models, image quality settings, and more.
- [Stable Diffusion Extensions](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/master/extensions) - A plugin that adds new extensions for Stable Diffusion WebUI, such as image cropping, image rotation, image flipping, image resizing, image filters, and more.
- [Stable Diffusion Embeddings](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/master/embeddings) - A plugin that adds new embeddings for Stable Diffusion WebUI, such as CLIP-RN50x4 text encoder, CLIP-RN50x16 text encoder, CLIP-ViT-B/32 text encoder, CLIP-ViT-B/16 text encoder, and more.
- [Aesthetic Gradients](https://github.com/AUTOMATIC1111/stable-diffusion-webui-aesthetic-gradients) - A plugin that allows you to create an embedding from one or few pictures and use it to apply their style to generated images.
- [Wildcards](https://github.com/AUTOMATIC1111/stable-diffusion-webui-wildcards) - A plugin that allows you to use `__name__` syntax in your prompt to get a random line from a file named `name.txt` in the wildcards directory.
- [Dynamic Prompts](https://github.com/adieyal/sd-dynamic-prompts) - A plugin that implements an expressive template language for random or combinatorial prompt generation along with features to support deep wildcard directory structures.
- [Dreambooth](https://github.com/d8ahazard/sd_dreambooth_extension) - A plugin that adds a new mode for generating realistic portraits of people with various attributes and styles.
- [Smart Process](https://github.com/d8ahazard/sd_smartprocess) - A plugin that adds a new option for processing images with different algorithms and parameters based on their content and quality.
- [MultiDiffusion with Tiled VAE](https://github.com/pkuliyi2015/multidiffusion-upscaler-for-automatic1111) - A plugin that adds a new mode for generating panoramic images with control using MultiDiffusion and tiled VAE optimization.
- [Dump U-Net](https://github.com/hnmr293/stable-diffusion-webui-dumpunet) - A plugin that allows you to view different layers and feature maps of the U-Net model and generate images by giving different prompts for each block of the U-Net.
- [Posex](https://github.com/hnmr293/posex) - A plugin that allows you to generate images for pose2image by moving the openpose figure in 3D space.
- [LLuL](https://github.com/hnmr293/sd-webui-llul) - A plugin that allows you to target an area to selectively enhance details using local latent upscaling.
- [CFG-Schedule-for-Automatic1111-SD](https://github.com/guzuligo/CFG-Schedule-for-Automatic1111-SD) - A plugin that allows you to dynamically control the CFG parameter during generation steps.
- - [VRAM Estimator](https://github.com/space-nuko/a1111-stable-diffusion-webui-vram-estimator) - A plugin that runs txt2img, img2img, highres-fix at increasing dimensions and batch sizes until OOM, and outputs data to graph.
- [Batch Face Swap](https://github.com/kex0/batch-face-swap) - A plugin that allows you to swap faces between multiple images using img2img mode.

You can find more plugins and instructions on how to install and use them [here](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Plugins).



## Tools

Stable Diffusion WebUI also provides some tools that can help you with your image generation tasks. Some of the tools are:

- [Image Gallery](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Image-Gallery) - A tool that allows you to save and view your generated images in a gallery.
- [Image Editor](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Image-Editor) - A tool that allows you to edit your generated images with basic operations such as crop, rotate, flip, resize, filter, and more.
- [Image Viewer](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Image-Viewer) - A tool that allows you to view your generated images in full screen mode with zoom and pan options.
- [Image Downloader](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Image-Downloader) - A tool that allows you to download your generated images in different formats and sizes.

You can find more tools and instructions on how to use them [here](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Tools).

## Tutorials and Articles

Stable Diffusion WebUI is a powerful and versatile tool for generating images with Stable Diffusion. However, it can also be challenging to master and use effectively. Fortunately, there are many tutorials and articles that can help you learn how to use Stable Diffusion WebUI and improve your skills. Some of them are:

- [How to Run Stable Diffusion Locally With a GUI on Windows](https://www.howtogeek.com/832491/how-to-run-stable-diffusion-locally-with-a-gui-on-windows/) - A step-by-step guide on how to install and run Stable Diffusion WebUI on Windows using Python and Git.
- [Stable Diffusion Art - tutorials, prompts, resources](https://stable-diffusion-art.com/) - A website dedicated to helping you master Stable Diffusion WebUI, by providing easy-to-follow tutorials and useful resources.
- [Stable Diffusion: Tutorials, Resources, and Tools](https://stackdiary.com/stable-diffusion-resources/) - A comprehensive reference to everything related to Stable Diffusion, including tools, tutorials, and numerous resources for styles.
- [How to Write an Awesome Stable Diffusion Prompt](https://www.howtogeek.com/833169/how-to-write-an-awesome-stable-diffusion-prompt/) - A guide on how to craft effective text prompts for Stable Diffusion WebUI and get ideal results.

You can also find more tutorials and articles on the [wiki](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki) of Stable Diffusion WebUI.

## Videos

Stable Diffusion WebUI is a visual and interactive way to generate images with Stable Diffusion. However, sometimes it can be helpful to watch someone else use it and explain how it works. Fortunately, there are many videos that can show you how to use Stable Diffusion WebUI and demonstrate its capabilities. Some of them are:

- [How to Use Stable Diffusion to Make AI GIFs and Videos](https://www.howtogeek.com/872921/how-to-use-stable-diffusion-to-make-ai-gifs-and-videos/) - A video tutorial on how to use Inpaint and Deforum extensions to create animations with Stable Diffusion WebUI.
- [Guide to making Stable Diffusion Img2Img Videos](https://www.youtube.com/watch?v=PddIlnAdv68) - A video guide on how to use FFMPEG and batch processing to create stylized videos with Stable Diffusion WebUI.
- [How to run Stable Diffusion to make awesome AI-generated art](https://www.digitaltrends.com/computing/how-to-run-stable-diffusion/) - A video overview on how to install and run Stable Diffusion WebUI on Windows, Mac, or Google Colab.

You can also find more videos on the [wiki](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki) of Stable Diffusion WebUI.



## Community

Stable Diffusion WebUI has a vibrant and friendly community of users and developers who are passionate about image generation and Stable Diffusion. You can join the community and interact with them on various platforms, such as:

- [Discord](https://discord.gg/8QJ2qfZ) - A chat platform where you can ask questions, share your creations, get feedback, and chat with other users and developers of Stable Diffusion WebUI.
- [Reddit](https://www.reddit.com/r/StableDiffusion/) - A forum platform where you can post your creations, discuss topics, and vote on other posts related to Stable Diffusion WebUI.
- [Twitter](https://twitter.com/StableDiffusion) - A social media platform where you can follow the latest news, updates, and announcements about Stable Diffusion WebUI.

You can also find more community resources and links [here](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Community).


## Contributing

Our repo is a curated list of awesome resources related to Stable Diffusion WebUI. We welcome contributions from anyone who is interested in expanding and improving our list. You can contribute in various ways, such as:

- Adding new resources to the list
- Updating existing resources with new information
- Sorting and organizing the list by categories and popularity
- Writing summaries and reviews for the resources
- Checking the validity and quality of the resources

You can find more information on how to contribute and the guidelines to follow [here](https://replo.io/our-repo/CONTRIBUTING.md).

