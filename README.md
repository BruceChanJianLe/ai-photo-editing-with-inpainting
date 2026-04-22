> This project is a tool that lets you isolate any object in a photo by clicking on it. The Segment Anything Model (SAM) generates a mask around the selected object, which you can refine with additional points until the selection is just right. From there, you describe a new background via text prompt, and an inpainting model fills it in seamlessly. You can also invert the mask to do the opposite to keep the background and replace the subject instead.

## Dependencies

```bash
micromamba create -n jupyterlab python pytorch torchvision torchaudio "cuda-version>=12.8,<13" datasets transformers peft evaluate accelerate jupyterlab -c pytorch -c conda-forge -c nvidia -y
```
