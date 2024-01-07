# Pet Image Classifier

## Description

This Python program classifies pet images using a pretrained CNN model and compares these classifications to the true identity of the pets in the images. The program summarizes how well the CNN performed on the image classification task. Three different CNN model architectures can be used, and the program compares their performance to determine which provides the 'best' classification.

## Usage

### Prerequisites

- Python 3.x
- Additional Python libraries (specified in requirements.txt)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
Install required dependencies:

bash
Copy code
pip install -r requirements.txt
Running the Program
Execute the check_images.py script to run the program. Use the following command-line arguments:

bash
Copy code
python check_images.py --dir <directory with images> --arch <model> --dogfile <file that contains dognames>
Example:

bash
Copy code
python check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt
Command-line Arguments
--dir: Directory path containing the pet images.
--arch: Model architecture to use (e.g., vgg, alexnet).
--dogfile: File containing dog names for classification.
Files
check_images.py: Main program script.
get_input_args.py: Module to handle command-line arguments.
get_pet_labels.py: Module to extract pet labels from image file names.
classify_images.py: Module to classify pet images using a pretrained CNN model.
adjust_results4_isadog.py: Module to adjust results for whether the classifier correctly classified images as dogs.
calculates_results_stats.py: Module to calculate statistics based on the results.
print_results.py: Module to print summary results and statistics.
Author
Abiola Segun
License
This project is licensed under the MIT License - see the LICENSE file for details.

sql
Copy code

Replace placeholders such as `<directory with images>`, `<model>`, and `<file that contains dognames>` with actual values. Also, update the `Author` section with your name.

Make sure to update the `requirements.txt` file with the necessary Python libraries if you have any additional dependencies.

Feel free to customize the README according to your specific project details and preferences.
