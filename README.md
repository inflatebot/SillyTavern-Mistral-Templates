# New Mistral Templates for SillyTavern
~~Corrected Context Template and Instruct Mode settings for SillyTavern.~~

~~Pandora from MistralAI [has opened a PR for SillyTavern](https://github.com/SillyTavern/SillyTavern/pull/2883) to add corrected templates that properly accommodate all of Mistral's models (as their tokenizer behavior is slightly different) but for Nemo in particular, these should be functional.~~

~~Pandora's templates are going to look different to the ones in this repo. If you want to use them, the equivalent files in Pandora's repo are [here (Context)](https://github.com/pandora-s-git/SillyTavern/blob/patch-2/default/content/presets/context/Mistral%20V3-Tekken.json) and [here (Instruct)](https://github.com/pandora-s-git/SillyTavern/blob/patch-2/default/content/presets/instruct/Mistral%20V3-Tekken.json).~~

~~Until the PR is merged, though, they're likely to change.~~

**The new Context Template and Instruct Mode presets for all Mistral architectures have been merged to SillyTavern's Staging branch.** If you don't want to/can't update, you can get the new prompt template files [here](https://github.com/SillyTavern/SillyTavern/tree/staging/default/content/presets) (in the `context` and `instruct` folders.)

The new update to SillyTavern Staging introduced 3 new Mistral entries to both Context Template and Instruct Mode.

__***Use the following SillyTavern templates for the respective Mistral model architectures:***__

__Mistral V1:__
Mistral 7B v1
Mistral 7B v2
Mixtral 8x7B

__Mistral V2 & V3:__
Mistral 7B v3
Codestral
Mixtral 8x22B
Mistral Small
Mistral Medium (incl. Miqu, probably)
Mistral Large
Pixtral

__Mistral V3-Tekken:__
Mistral Nemo.

If you're using something based on Mistral 7B and you can't tell which version it is, then just use whichever one works better, I guess. Tell the maker of your model to add the `base_model` parameter in the YAML section of their model card, so that the HF model tree will work properly.
