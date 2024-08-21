# medical-imaging-metrics

**Project Overview**

![thumbnail-image](https://github.com/user-attachments/assets/8b856272-2931-4b96-93f4-0f55a9762ad1)
Dicom image for Pancreas-CT TCIA collection (publicly accessible)

This project includes Python scripts that enhance the capability to view and analyze medical imaging data stored in Amazon S3, specifically focusing on DICOM files. It provides:

Interactive Visualization: 
    This Jupyter Notebook provides an interactive visualization tool for DICOM images stored in an Amazon S3 bucket. Utilizing ipywidgets for a user-friendly interface, the notebook allows users to select an S3 bucket and view the corresponding DICOM images. It’s intended for those wanting a preliminary quick visualization without downloading them locally.

DICOM Intensity Statistics: 
    This Jupyter Notebook provides an interactive visualization tool for DICOM images stored in an Amazon S3 bucket. Utilizing ipywidgets for a user-friendly interface, the notebook allows users to select an S3 bucket and view the corresponding DICOM images. It’s intended for those wanting a preliminary quick visualization without downloading them locally.

## Installation and Usage

**Clone the repository:**

```bash
git clone https://github.com/OpenBioResearch/medical-imaging-metrics.git
cd medical-imaging-metrics
```

**Create a virtual environment (optional but recommended):**

```bash 
python -m venv .venv
source .venv/bin/activate  # git bash
```

**Install the Python dependencies:**

```bash
pip install -r requirements.txt
```

**Run the python scripts:**

```bash
python vscode_intensity_dicom_stats.py <S3_BUCKET_NAME>
 ```

To run the dicom_s3_visualizer.ipynb script, launch the jupyter notebook and it will request your S3 bucket name.

**License:** 

TCIA Pancreas-CT collection images are licensed under a Creative Commons Attribution 3.0 Unported License (https://creativecommons.org/licenses/by/3.0/).

**Video**

https://github.com/user-attachments/assets/e7bb944f-c744-4979-ab13-d099e7e03c5f
