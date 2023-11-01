[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/effepivi/gvxr-tutorials/HEAD)

![gVXR](img/gvxr_logo.png)

# Installation


1. Get the code fromthe git repository with:
```bash
git clone https://github.com/effepivi/gvxr-tutorials.git
```
2. Install Mamba. Visit [https://mamba.readthedocs.io/en/latest/micromamba-installation.html](https://mamba.readthedocs.io/en/latest/micromamba-installation.html) for guidance.
3. Create the Conda environment with:
```bash
mamba env create -f environment.yml
```
4. Activate the environment using:
```bash
conda activate gvxr-tutorials
```
5. Launch Jupyter lab with:
```bash
jupyter lab
```














# Tutorials

Series of tutorials to show how to use gVXR

1. [Installation-and-test.ipynb](Installation-and-test.ipynb)
    - Content
        1. Install the Python packages needed for this course;
        2. Check that [gVirtualXray](https://gvirtualxray.sourceforge.io/) is working well;
        3. Verify which version of [gVirtualXray](https://gvirtualxray.sourceforge.io/) is installed (software and hardware); and
        4. How to get help.
    - [Watch the video](https://youtu.be/kZPNA4qha2s)

    [![Watch the recording](https://img.youtube.com/vi/kZPNA4qha2s/0.jpg)](https://youtu.be/kZPNA4qha2s "gVirtualXray (gVXR) Installation and test")
    - [Run on Google Collaborate](https://colab.research.google.com/github/effepivi/gvxr-tutorials/blob/main/Installation-and-test.ipynb)
2. [First_xray_simulation.ipynb](First_xray_simulation.ipynb)
    - Content
        1. Create our first X-ray simulation, step-by-step;
        1. Save our X-ray image in a file format that preserves the original dynamic range;
        1. Visualise the results with 3 different look-up tables;
        1. Visualise the 3D environment.
    <!-- - [Watch the video](https://youtu.be/kZPNA4qha2s) -->

    <!-- [![Watch the recording](https://img.youtube.com/vi/kZPNA4qha2s/0.jpg)](https://youtu.be/kZPNA4qha2s "gVirtualXray (gVXR) Installation and test") -->
    - [Run on Google Collaborate](https://colab.research.google.com/github/effepivi/gvxr-tutorials/blob/main/First_xray_simulation.ipynb)
3. [Multi_material_sample.ipynb](Multi_material_sample.ipynb)
    - Content
        1. Create X-ray simulations of samples involving multiple materials
            1. Multiple individual materials (e.g. a Copper pipe inside an Aluminium block)
            2. Metal Alloys and Mixtures
            3. Chemical Compounds
        2. Visualise the effects of different materials on the resulting X-ray images
    <!-- - [Watch the video](https://youtu.be/kZPNA4qha2s) -->

    <!-- [![Watch the recording](https://img.youtube.com/vi/kZPNA4qha2s/0.jpg)](https://youtu.be/kZPNA4qha2s "gVirtualXray (gVXR) Installation and test") -->
    - [Run on Google Collaborate](https://colab.research.google.com/github/effepivi/gvxr-tutorials/blob/main/Multi_material_sample.ipynb)
4. [Source_parameters.ipynb](Source_parameters.ipynb)
    - Content
        1. Create X-ray sources of different shapes:
            1. Parallel beam (e.g. synchrotron);
            2. Cone-beam (e.g. X-ray tube);
                1. Ideal case, i.e. infinitesimal point source;
                2. Focal spot, i.e. more realistic.
        2. Visualise the source shape;
        3. Set the beam spectrum:
            1. Monochromatic;
            2. Polychromatic:
                1. By hand;
                2. Using a text file;
                3. Using xpecgen (a python package to calculate x-ray spectra generated in tungsten anodes using the model of Med. Phys. 43, 4655.).
    <!-- - [Watch the video](https://youtu.be/kZPNA4qha2s) -->

    <!-- [![Watch the recording](https://img.youtube.com/vi/kZPNA4qha2s/0.jpg)](https://youtu.be/kZPNA4qha2s "gVirtualXray (gVXR) Installation and test") -->
    - [Run on Google Collaborate](https://colab.research.google.com/github/effepivi/gvxr-tutorials/blob/main/Source_parameters.ipynb)
5. [Detector_parameters.ipynb](Detector_parameters.ipynb)
    - Content
        1. Introduction to more advanced detector properties
        2. Learn the effect of magnification on tube-based scanners
        3. See how the detector's Line Spread Function dramatically change result quality (pixels are not everything!)
    <!-- - [Watch the video](https://youtu.be/kZPNA4qha2s) -->

    <!-- [![Watch the recording](https://img.youtube.com/vi/kZPNA4qha2s/0.jpg)](https://youtu.be/kZPNA4qha2s "gVirtualXray (gVXR) Installation and test") -->
    - [Run on Google Collaborate](https://colab.research.google.com/github/effepivi/gvxr-tutorials/blob/main/Detector_parameters.ipynb)
5. [CT_acquisition.ipynb](CT_acquisition.ipynb)
    - Content
        1. Learn how to perform a simulated CT Acquisition
        2. Use reconstructed data to see how simulation parameters affect quality
        3. Discover the effects of polychromatic beams on results
        4. Compare simulated samples to real data   
     <!-- - [Watch the video](https://youtu.be/kZPNA4qha2s) -->

    <!-- [![Watch the recording](https://img.youtube.com/vi/kZPNA4qha2s/0.jpg)](https://youtu.be/kZPNA4qha2s "gVirtualXray (gVXR) Installation and test") -->
    - [Run on Google Collaborate](https://colab.research.google.com/github/effepivi/gvxr-tutorials/blob/main/CT_acquisition.ipynb)
