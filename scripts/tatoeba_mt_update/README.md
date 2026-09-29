# Script for updating the tatoeba_mt dataset on Hugging Face

This script downloads a given version of the data from https://github.com/Helsinki-NLP/Tatoeba-Challenge/blob/master/data/Releases.md and uploads it to the Hugging Face data set at https://huggingface.co/datasets/Helsinki-NLP/tatoeba_mt. The uploaded data is tagged with the given version number on HuggingFace. The script also updates the language list in the README file using the `pycountry` package and generates the YAML block at the top of the README file.

## Usage

Install the required python packages:

```
pip install -r req.txt
```

Login to Hugging Face hub:

```
hf auth login
```

Run the script with a version number selected from https://github.com/Helsinki-NLP/Tatoeba-Challenge/blob/master/data/Releases.md, for example `v2023-09-26`:

```
./update_tatoeba_hf.sh v2023-09-26
```

This will delete existing files in Helsinki-NLP/tatoeba_mt and upload the new version of the dataset with the tag `v2023-09-26`.
