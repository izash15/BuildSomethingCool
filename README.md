# A Story Worth A Thousand Words
A project for AI in software development where two AI models are combined to create something cool and fun.

This project has the user input an image for which a caption is generated. The caption is then used to create a story using a random sentiment added into the prompt. The user then guesses what sentiment was used in the generation of the story. 

This project was built using: 
1) Hugging face image to text caption generator from hysts/image-captioning-with-git (available at this link https://huggingface.co/spaces/hysts/image-captioning-with-git/tree/main)
2) Gemini for text generation

To run the demo, open the jupyter notebook file titled "BuildSomethingCool.ipynb". Run everything on GPU (if available but not necessary) then interact with the model in the gradio interface using the link following the text "Running on public URL: ...".

This demo is also made publically available on HuggingFace Spaces: https://huggingface.co/spaces/PranaviK/A-Story-Worth-A-Thousand-Words 
