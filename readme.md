# medical-imaging-metrics

**Project Overview**

![thumbnail-image](https://github.com/user-attachments/assets/8b856272-2931-4b96-93f4-0f55a9762ad1)

Dicom image for Pancreas-CT TCIA collection (publicly accessible)

Interactive DICOM S3 Visualizer: File: dicom_s3_visualizer.ipynb
    This Jupyter Notebook provides an interactive visualization tool for DICOM images stored in an Amazon S3 bucket. Utilizing ipywidgets for a user-friendly interface, the notebook allows users to select an S3 bucket and view the corresponding DICOM images. It’s intended for those wanting a preliminary quick visualization without downloading them locally.

DICOM Intensity Statistics: vscode_intensity_dicom_stats.py
    This python script calculates intensity statistics (mean, median, and standard deviation) across DICOM files in an S3 bucket by exracting pixel data to generate quantitative insights.

   

https://github.com/user-attachments/assets/e7bb944f-c744-4979-ab13-d099e7e03c5f

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

**Run the python scriptS:**
 To run the vscode_intensity_dicom_stats.py script, use the following command:

```bash
python vscode_intensity_dicom_stats.py <S3_BUCKET_NAME>

To run the dicom_s3_visualizer.ipynb script, launch the jupyter notebook and it will request your S3 bucket name.

**License:** 

TCIA Pancreas-CT collection images are licensed under a Creative Commons Attribution 3.0 Unported License (https://creativecommons.org/licenses/by/3.0/).
