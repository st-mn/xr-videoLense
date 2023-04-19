# XR Video Lens

This project provides a mixed reality playground using GANgealing for video processing, enabling dense tracking and object lens creation on videos.

## Features

- Dense tracking on videos
- Object lens propagation (e.g., adding cartoon faces, moustaches, reindeer horns)
- Support for various pre-trained models (human, dog, cat, bird, bicycle, TV monitor)
- Custom video upload capability
- Mixed reality video generation

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/st-mn/xr-videoLense.git
   cd xr-videoLense
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Follow the setup instructions in the notebook for additional dependencies like GANgealing.

## Usage

1. Open the `GANgealingMixedReality.ipynb` notebook in Jupyter or VS Code.
2. Run the cells to set up the environment and download models.
3. Select a model and video from the provided options or upload your own.
4. Choose an object lens or dense tracking.
5. Run the mixed reality generation to produce the output video.

## Requirements

- Python 3.7+
- GPU recommended for faster processing
- Pre-trained GANgealing models
- FFmpeg for video processing

## Contributing

Contributions are welcome. Please submit pull requests or open issues for bugs and feature requests.

## License

This project is licensed under the MIT License.