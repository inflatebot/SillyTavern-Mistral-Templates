# SillyTavern-Nemo-Templates
Corrected Context Template and Instruct Mode settings for SillyTavern.

Pandora from MistralAI [has opened a PR for SillyTavern](https://github.com/SillyTavern/SillyTavern/pull/2883) to add corrected templates that properly accommodate all of Mistral's models (as their tokenizer behavior is slightly different) but for Nemo in particular, these should be functional.

Pandora's templates are going to look different to the ones in this repo. If you want to use them, the equivalent files in Pandora's repo are [here (Context)](https://github.com/pandora-s-git/SillyTavern/blob/patch-2/default/content/presets/context/Mistral%20V3-Tekken.json) and [here (Insruct)](https://github.com/pandora-s-git/SillyTavern/blob/patch-2/default/content/presets/instruct/Mistral%20V3-Tekken.json)
Until the PR is merged, though, they're likely to change.
