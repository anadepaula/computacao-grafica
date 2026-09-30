# computação gráfica course notes and exercises


## setting up the uv environment

```bash
uv venv -p 3.11
uv sync
```

## adding OS dependenciese 
the following dependencies are needed. their versions are degined in pyproject.yaml 

```bash
glcontext
glfw
moderngl
numpy
pillow
pyglm
```

besides the python packages, i had to install some OS dependencies. beware that my install is kinda weird (i'm running a debian in a 2015 macbook air) so idk if it  is necessary for other OSs.

```bash 
sudo apt update
sudo apt install libgl1 libegl1
sudo apt install libgl1-mesa-dev libegl1-mesa-dev
```