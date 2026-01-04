# 🎭 Face Blur AI

Automatic face detection and blurring tool powered by YOLOv5-Face deep learning model.

## 🌟 Features

- ✅ Automatic face detection in images
- ✅ High accuracy even for distant/small faces
- ✅ Batch processing for multiple images
- ✅ Gaussian blur for natural-looking results
- ✅ Preserves image quality and aspect ratio
- ✅ CPU and GPU support

## 🛠️ Technologies Used

- **Python 3.11**
- **PyTorch** - Deep learning framework
- **YOLOv5-Face** - Face detection model
- **OpenCV** - Image processing
- **NumPy** - Numerical computations

## 📸 Demo

### Before
![Original Image](https://github.com/GBX012/face-blur-ai/blob/main/demo/before_1.jpg?raw=true)

### After
![Blurred Image](https://github.com/GBX012/face-blur-ai/blob/main/demo/after_1.jpg?raw=true)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/GBX012/face-blur-ai.git
cd face-blur-ai
```

2. Install dependencies:
```bash
pip install torch torchvision opencv-python numpy tqdm PyYAML Pillow
```

3. Download YOLOv5-Face model:
- Download `yolov5n-face.pt` from [here](https://drive.google.com/file/d/18oenL6tjFkdR1f5IgpYeQfDFqU4w3jEr/view)
- Place it in the project root directory

4. Download YOLOv5-Face repository files:
- Clone or download from [deepcam-cn/yolov5-face](https://github.com/deepcam-cn/yolov5-face)
- Copy `models/` and `utils/` folders to project directory

## 💻 Usage

1. Place your images in the `input/` folder
2. Run the script:
```bash
python face_blur.py
```
3. Find processed images in the `output/` folder

## 📊 Performance

- **Processing Speed:** 3-5 seconds per 1920x1080 image (CPU)
- **Detection Accuracy:** High precision with 0.25 confidence threshold
- **Supported Formats:** JPG, PNG, BMP, TIFF

## 🎯 Use Cases

- **Privacy Protection** - Anonymize people in photos
- **GDPR Compliance** - Automatic face redaction
- **Social Media** - Protect identity in public posts
- **Surveillance** - Privacy-aware video processing

## 📝 Configuration

You can customize the blur strength in `face_blur.py`:
```python
# Line 167
ai.proceseaza_imagine(cale_input, cale_output, putere_blur=99)
```

Options:
- `51` - Light blur
- `99` - Standard blur (default)
- `151` - Heavy blur

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Gabriel**
- GitHub: [@GBX012](https://github.com/GBX012)
- Email: gabrieltintar8@gmail.com

## 🙏 Acknowledgments

- [YOLOv5-Face](https://github.com/deepcam-cn/yolov5-face) for the face detection model
- OpenCV community for image processing tools
