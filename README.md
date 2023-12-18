# YOLO to COCO Segmentation Converter

This script converts a YOLO dataset for segmentation into a COCO dataset for segmentation.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   
2. Navigate to the project directory:
    ```bash
   cd your-repository
   
3. Install dependencies:
    ```bash
   pip install -r requirements.txt

### Usage

Run the script with the following command:

   ```bash
   python yolo2coco_segmentation.py --yolo_image_path=/path/to/yolo_images --yolo_label_path=/path/to/yolo_labels --classes=class1,class2,... --coco_output_dir=/path/to/coco_output
   ```
### Help Information

   ```bash
   python yolo2coco_segmentation.py --help
   ```

Replace the following parameters:
```bash
/path/to/yolo_images: Path to the folder containing images from the YOLO dataset.
/path/to/yolo_labels: Path to the folder containing labels from the YOLO dataset.
class1,class2,...: List of classes separated by commas.
/path/to/coco_output (optional): Output directory name for the COCO dataset. Default is 'coco_segmentation_dataset'.
```

### Result

After running the script, you will find the COCO segmentation dataset in the specified output directory.


Feel free to customize the parameters according to your dataset and project requirements. Contributions and feedback are welcome!