<div style="display: flex; align-items: center;">
    <img src="https://opensarlab-docs.asf.alaska.edu/opensarlab-notebook-assets/logos/ASF_logo.svg" alt="ASF logo" style="width: 15%; margin-right: 10px;"/>
    <img src="https://asf.alaska.edu/wp-content/uploads/2023/10/OPERA-logo.png" alt="ASF logo" style="width: 15%;"/>
</div>

# Start Here

## opensarlab_OPERA-RTC-S1_Recipe_Book

A Jupyter Book of data recipes for use with Observational Products for End-Users from Remote Sensing Analysis (OPERA), Coregistered Single-look Complex Sentinel 1 (RTC-S1) data products

>"The Radiometric Terrain Corrected (RTC) SAR Backscatter product consists of radar backscatter normalized with respect to the topography. The RTC product is generated from Sentinel-1 as the input dataset and has the short name RTC-S1. The RTC-S1 product is a Level-2 product that is projected onto pre-defined UTM/Polar stereographic map projection systems. The Copernicus global 30 m (GLO-30) Digital Elevation Model (DEM) is the reference DEM used to correct for the impacts of topography and to geocode the product. The RTC product maps signals largely related to the physical properties of the ground scattering objects, such as surface roughness and soil moisture and/or vegetation. The RTC product also serves as the basis for the DSWx-S1 products. The product is provided in a GeoTIFF file format and has a posting of 30 m."
>
>[https://www.jpl.nasa.gov/go/opera/products/rtc-product](https://www.jpl.nasa.gov/go/opera/products/rtc-product)

<br>

<div class="alert alert-success" style="display: flex; align-items: center; font-family: 'Times New Roman', Times, serif; background-color: 'rgba(200,0,0,0.2)'">
  <div style="width: 95%;">
    <h2><b>Important Note About Your Jupyter Environment if not in OpenSARLab</b></h2>
    <b><i>Tip: Run the notebooks in this Jupyter Book from Jupyter Lab, launched from a conda environment containing the required Jupyter packages. 
        <br/>
        This can be accomplished with the following commands:</i></b>
    <pre style="background-color: #f5f5f5; padding: 10px; border-radius: 5px; border: 1px solid #ccc; overflow: auto;">
      <code>mamba create -n jbook -c conda-forge jupyterlab notebook ipywidgets ipympl nb_conda_kernels</code>
      <code>mamba activate jbook</code>
      <code>python -m pip install jupyterlab-jupyterbook-navigation</code>
      <code>jupyter lab</code>
    </pre>
    <ul>
        <li>Jupyter selection widgets used in the notebooks require the packages <code>ipywidgets</code> and <code>notebook</code>.</li>
        <li>In order to use multiple conda environments in Jupyter Lab at the same time, you must install <code>nb_conda_kernels</code>.</li>
        <li>Interactive matplotlib plots requires the package <code>ipympl</code> in the environment running Jupyter Lab</li>
    </ul>
  </div>
</div>

>1. ### Install the software environment needed to run the notebooks
>
>    - [Install Required Software with Conda](search_download_OPERA-RTC-S1.ipynb)
>    - Rerun this step periodically. Updates to environment config files will not take effect unless you update or recreate your environment.
>
>1. ### Explore data access notebooks
>    - [OPERA Burst IDs from Sentinel-1 SLC IDs](burst_ID_extractor.ipynb)
>    - [Direct S3 Access](OPERA_S3_Access.ipynb)
>    - [Download Data](search_download_OPERA-RTC-S1.ipynb)
>
>1. ### RTC-Based Analyses
>    - [RTC Time Series](OPERA-RTC-S1-time_series.ipynb)

## Contact Us

<div class="alert alert-info" style="display: flex; align-items: center; font-family: 'Times New Roman', Times, serif; background-color: #d1ecf1;">
  <div style="display: flex; align-items: center; width: 10%;">
    <a href="https://github.com/ASFOpenSARlab/opensarlab_OPERA-CSLC_Recipe_Book/issues">
      <img src="https://opensarlab-docs.asf.alaska.edu/opensarlab-notebook-assets/logos/github_issues.png" alt="GitHub logo over the word Issues" style="width: 100%;">
    </a>
  </div>
  <div style="width: 95%;">
    <b>Did you find a bug? Do you have a feature request?</b>
    <br/>
    Explore GitHub Issues on this Jupyter Book's GitHub repository. Find solutions, add to the discussion, or start a new bug report or feature request: <a href="https://github.com/ASFOpenSARlab/opensarlab_OPERA-CSLC_Recipe_Book/issues">opensarlab_OPERA-CSLC_Recipe_Book Issues</a>
  </div>
</div>

<div class="alert alert-info" style="display: flex; align-items: center; justify-content: space-between; font-family: 'Times New Roman', Times, serif; background-color: #d1ecf1;">
  <div style="display: flex; align-items: center; width: 10%; margin-right: 10px;">
    <a href="mailto:uso@asf.alaska.edu">
      <img src="https://opensarlab-docs.asf.alaska.edu/opensarlab-notebook-assets/logos/ASF_support_logo.png" alt="ASF logo" style="width: 100%">
    </a>
  </div>
  <div style="width: 95%;">
    <b>Have a question related to SAR, OPERA RTCs, or ASF data access?</b>
    <br/>
    Contact ASF User Support: <a href="mailto:uso@asf.alaska.edu">uso@asf.alaska.edu</a>
  </div>
</div>
