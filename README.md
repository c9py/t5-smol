# t5-smol

## Clone this model repo

### Using git-xet (macOS)

```bash
# Make sure git-xet is installed (https://hf.co/docs/hub/git-xet)
brew install git-xet
git xet install

git clone https://huggingface.co/google-t5/t5-small

# If you want to clone without large files - just their pointers
# (useful for quick inspection of model metadata without downloading weights)
GIT_LFS_SKIP_SMUDGE=1 git clone https://huggingface.co/google-t5/t5-small
```

### Using HuggingFace CLI

#### Windows (PowerShell)

```powershell
# Make sure the hf CLI is installed
powershell -ExecutionPolicy ByPass -c "irm https://hf.co/cli/install.ps1 | iex"

# Download the model
hf download google-t5/t5-small
```

#### Other platforms

```bash
# Install the HuggingFace CLI (if not already installed)
# See https://huggingface.co/docs/huggingface_hub/guides/cli for installation instructions

# Download the model
hf download google-t5/t5-small
```