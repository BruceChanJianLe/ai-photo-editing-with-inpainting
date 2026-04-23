> This project is a tool that lets you isolate any object in a photo by clicking on it. The Segment Anything Model (SAM) generates a mask around the selected object, which you can refine with additional points until the selection is just right. From there, you describe a new background via text prompt, and an inpainting model fills it in seamlessly. You can also invert the mask to do the opposite to keep the background and replace the subject instead.

## Dependencies

### Using pixi

Install pixi:  
```bash
curl -fsSL https://pixi.sh/install.sh | bash
```

Start with pixi:  
```bash
pixi install
pixi shell
```

### Using Micromamba
```bash
micromamba create -n jupyterlab3 python=3.10.11 jupyterlab -c pytorch -c conda-forge -c nvidia -y
micromamba run -n jupyterlab3 pip install -r requirements.txt
```
