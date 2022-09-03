![](.github/banner.png)
# *Structured Prompt Generator*
### with OpenAI GPT-3 Creations & Enhanced Prompt Writer
Made to construct well formed complex text prompts for Disco Diffusion and other text-to-image AI art platforms.  This is a helper tool to create unique interesting descriptions in less time and visual surprises. 😎

<p align=center>
<a href="https://github.com/Skquark/structured-prompt-generator/blob/main/Structured_Prompt_Generator.ipynb"><img src="https://badgen.net/badge/icon/github?icon=github&label" alt="Github"></a> <a href="https://github.com/Skquark/structured-prompt-generator"><img src="https://badgen.net/github/release/Skquark/structured-prompt-generator/stable" alt="Release version"></a>
<a href="https://colab.research.google.com/github/Skquark/structured-prompt-generator/blob/main/Structured_Prompt_Generator.ipynb"><img src="https://img.shields.io/badge/Open-in%20Colab-brightgreen?logo=google-colab&style=flat-square" alt="Open in Google Colab"/></a>
</p>

*   Includes a comprehensive list of supported Artists and Styles
*   Start the sentence with a subject and let AI complete the scene with interesting details
*   Select which modifiers to apply to improve results, with list of positive and negative attributes
*   Use variables for random nouns, adjectives, colors, styles, and other useful terms in your creations
*   Generate prompt lists that can be used for batch image creations, animation timelines or other art making tools
*   Runs on Colab with CPU instead of GPU runtime, so you can play with it while you're Diffusing in other window

---
***Credits:***
* Enhancements and refinements by [**Skquark** (Alan Bedian)](https://skquark.com)
* OpenAI GPT-3 Integration by [**Martin Kallstrom**](https://colab.research.google.com/drive/1qgO774Ue1UW_j4vmrmvBty6wPh6cDgZc?usp=sharing)
* *Noodle Soup Prompts* & Terminology Database by [**WAS**asquatch](https://github.com/WASasquatch/noodle-soup-prompts/blob/main/nsp_pantry.py)
* Artist names gathered by **[MisterRuffian](https://docs.google.com/spreadsheets/d/1_jgQ9SyvUaBNP1mHHEzZ6HhL_Es1KwBKQtnpnmWW82I/edit)**
* Prompt modifiers & suggestions by [**Disco Diffusion** Discord community](https://discord.gg/Cajx9rku)

https://colab.research.google.com/github/Skquark/structured-prompt-generator/blob/main/Structured_Prompt_Generator.ipynb

---

# **Enhanced Stable Diffusion** 🎨 
*...using `🧨diffusers`* and practical bonus features...
*   Run a batch list of prompts at once, so queue many and walk away
*   Option to override any parameter per prompt in queue
*   Option to use Stability-API tokens for more samplers, bigger size & CPU runtime
*   Supports image2image use an init_image
*   Experimental prompt tweening to combine 2 prompts in a series
*   Can save all images to your Google Drive
*   Can Upscale automatically with Real-ESRGAN enlarging
*   Embeds exif metadata directly into png files
*   Disabled NSFW filtering and added custom sampler options
*   Renames image filenames to the prompt text, with options
*   Simple forms to set parameters, as easy as interactive python gets
*   OpenAI Prompt Generator and Noodle Soup Prompt Writer included
*   Standalone ESRGAN Upscaler for batch uploads and image splitting
*   Additional features added regularly...

https://colab.research.google.com/github/Skquark/structured-prompt-generator/blob/main/Enhanced_Stable_Diffusion_with_diffusers.ipynb

---

# **Enhanced DiscoArt** 🎨 
*...Disco Diffusion* /w Batch Prompts, Prompt Generators & SD init...
*   Easier Settings with GUI forms to give Parameters to DiscoArt creations
*   Saves image named with prompt, copies to GDrive, adds metadata, can save configs
*   Create Batch Prompts, listing as many complex prompts to process in queue
*   Override any of your default settings for any image in the batch list to allow experimentations
*   Integrated Stable Diffusion to Generate base init_image to Centipede to Disco pipeline
*   Can also generate higher quality init with Stability-API to use cheap tokens to save precious VRAM
*   Use OpenAI GPT-3 to Generate Prompts, give phase to start sentance, subject, AI adjustments, then generate away
*   Add random Artist & Styles, select +/- modifiers, custom weights, then generate lists in handy formats
*   Structured Prompt Writer to create your perfect prompts, supports Noodle Soup variables, custom modifiers and more
*   Convert standard prompt lists to new Json style, then add custom Prompt Schedualing and Clip Model Scheduler with helpers
*   Integrated Real-ESRGAN image upscaling with batch uploads or path, enlarge size scale, and GDrive upload option
*   and other extra touches you'll discover, with more Disco helpers to come... 

https://colab.research.google.com/github/Skquark/structured-prompt-generator/blob/main/DiscoArt_%5B_w_Batch_Prompts_%26_GPT_3_Generator%5D.ipynb
