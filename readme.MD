## Mapping with R - NICAR 2019

These files and folders are meant to accompany the hands-on [Mapping with R hands-on session](https://www.ire.org/events-and-training/event/3433/4207/) at 2019 NICAR.

* [Mapping slides](https://andrewbtran.github.io/NICAR/2019/mapping/01_maps_slides.html)
* [Case study slides](https://andrewbtran.github.io/NICAR/2019/mapping/02_case_study_slides.html)

### Downloading this Repo via R

The quickest way to access the data for this session is to first make sure your current project directory is logically organized. 

Hopefully, you've created folder on your computer in your `Documents` folder called `Projects` or something like that.

Once you've set your working directory (with maybe `setwd()`) then you can run these commands in your console to download the correct folders and data:

```
install.packages("usethis")
```

and then

```
usethis::use_course("https://github.com/andrewbtran/NICAR-2019-mapping/archive/master.zip")
```

----

Otherwise:

### Downloading this Repo by hand

Clone or download and unzip this repo. Make sure the folder is **not** in a temporary unzipped folder.

To ensure these files work as expected, please make sure the project directory is set up correctly: 

When you type `getwd()` it should look something like `your_file_path/NICAR-2019-mapping`

You can manually set this up by:

*Session > Set Working Directory > To Project Directory*

Alternatively, you can double click the **NICAR-2019-mapping.Rproj** file from your finder/file browser.

----

### Working with the files

Navigate to the `01_maps_code.Rmd` and `02_case_study_code.Rmd` to open and follow along with each section.

Additionally, the raw code is saved as similar naming above but ending with the .R file extension.

Or you can execute the following commands in the console to bring up the files.

* `file.edit("01_maps_code.Rmd")`
* `file.edit("02_case_study_code.Rmd")`

To view the local html version of the .rmd files, you can try the following commands in your console to see rendered version of the sub-chapter:

* `browseURL("01_maps_code.html")`
* `browseURL("02_case_study_code.html")`

To view the slideshow version:
* `browseURL("01_maps_slides.html")`
* `browseURL("02_case_study_slides.html")`

----


## License

The online version of this course is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

---

### [NICAR 2018 sessions](https://andrewbtran.github.io/NICAR/2018/)
### [NICAR 2017 sessions](https://andrewbtran.github.io/NICAR/2017/)