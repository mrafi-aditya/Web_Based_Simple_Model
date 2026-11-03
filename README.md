# Basic 3D Model Viewer

An introductory computer-graphics coursework project using Babylon.js to load a glTF model and explore camera and lighting setup in the browser. Kept as an earlier stage of the graphics coursework series.

**Stack:** JavaScript · HTML · Babylon.js · glTF

## Run locally

```sh
git clone https://github.com/mrafi-aditya/Web_Based_Simple_Model.git
cd Web_Based_Simple_Model
python -m http.server 8000
```

Open `http://localhost:8000`. Use the camera's pointer controls to inspect the model. Babylon.js is loaded from its CDN, so an internet connection is required. No npm build step is needed.

## Files and progression

- [index.html](index.html): browser entry point and rendering canvas.
- [script.js](script.js): scene setup, camera, lighting, and model loading.
- `model.gltf`: model asset.

The repository preserves its existing commit and contribution history. The project demonstrates rendering integration; underlying 3D asset ownership is not claimed here.

Continue with [lighting and shadows](https://github.com/mrafi-aditya/Web-Based-Simple-Model-Shadow), then [Movase and click-to-move interaction](https://github.com/mrafi-aditya/Web-Based-Simple-Interactive).
