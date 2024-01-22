# artificialguybr/Nebul.Redmond Cog model

This is an implementation of [artificialguybr/Nebul.Redmond](https://huggingface.co/artificialguybr/NebulRedmond) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i prompt="masterpiece, high quality, ultra good, this is the good stuff, best prompt ever, portrait of a woman, freckles, ginger"

## Example Output

Example output for prompt: "masterpiece, high quality, ultra good, this is the good stuff, best prompt ever, portrait of a woman, freckles, ginger"

![alt text](output.0.png)
