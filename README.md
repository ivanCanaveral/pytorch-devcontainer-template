# pytorch-devcontainer-template
Pytorch devcontainer template, for the development of models and experimentation.

## Pytorch installation commands

With pip

```bash
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cpu
```

With poetry 
```bash
poetry source add -p explicit pytorch https://download.pytorch.org/whl/cpu
poetry add --source pytorch torch torchvision
```

At this point, I've decided to use pip instead of poetry, to avoid some issues.