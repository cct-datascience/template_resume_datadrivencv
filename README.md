
## Purpose

To be able to generate a resume using the `datadrivencv` approach without needing to install the [`datadrivencv` R package](https://github.com/cct-datascience/datadrivencv). 

## Instructions

1. Download [this repo](https://github.com/cct-datascience/template_resume_datadrivencv)
2. Unzip the downloaded file and rename the folder
3. Create an R project for the new folder
4. Run `render_cv.R`to generate `cv.pdf`
5. Customize by changing `cv.rmd`, `dd_cv.css`, and the files in `data/`

This uses the local files option by default. You can switch to using a Google Sheet as the input by changing the `data_location` argument in `create_CV_object` in `cv.rmd` to a Google Sheet URL. Make sure to set the sheet sharing options to "Anyone with the link can view."
