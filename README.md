# Stable Diffusion for Interior Design

## Problem Statement
An interior design company based in Edmonton aimed to empower clients to visualize their design ideas, regardless of their skill level. Additionally, they aimed to improve efficiency by reducing the time designers spent on creating mockups. Given the creative nature of interior design they explored the use of generative AI. However, it was crucial to ensure that the AI-generated designs could be practically implemented and that the necessary items could be sourced effectively.

## Solution
The solution involved fine-tuning a text-to-image [Stable Diffusion v1-5](https://huggingface.co/runwayml/stable-diffusion-v1-5) model using [DreamBooth](https://huggingface.co/docs/diffusers/en/training/dreambooth) and a dataset of previously created mockups labeled with styles and colors for both the room and furnishings. This approach enables both clients and designers to generate new feasible mockups quickly, improving efficiency and client satisfaction.

### [Fine-Tuning Notebook](https://colab.research.google.com/drive/16If7HPJn5D6lS9LVhgPmsDAY0nOm0xn9?usp=sharing)
