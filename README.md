# Accessing Canadian weather data in R - Introduction to weathercan

*Québec Océan - Comité étudiant - 2025*

**Monday October 27th, 2025 2pm-4pm Eastern**

Welcome! 

Interested in exploring Canadian weather data in a simple and reproducible manner? Tired of downloading ECCC historical weather data by hand? Come learn about the weathercan R package!

In this workshop we'll have a brief overview of the basics in R and will then spend our time working with the weathercan package for downloading historical ECCC weather data as well as climate normals. We'll explore different ways to find weather stations, how to download data in bulk, and what to do with all that data once you have it. You'll have the opportunity to practice, ask questions, and work with data relevant to your own research. Examples will be available, but best is to have an idea of locations (lat/lon) and dates relevant to your own research.

Participants do not need to be R experts but should be somewhat familiar with R and RStudio and will be expected to have both installed prior to the workshop (instructions will be provided the week before).

This GitHub repository holds all the information relating to our workshop.

> **Important!**
>
> Make sure you're ready for the workshop by following the **Before the workshop** instructions. Please [email me](mailto:sel@steffilazerte.ca) if you run into any problems.
>
> Take care to update RStudio, in particular, as we need some of the newest features.

## Workshop resources

- Slides
  - [html](https://steffilazerte.ca/workshop-intro-to-weathercan/index.html) (best)
  - [pdf](https://steffilazerte.ca/workshop-intro-to-weathercan/intro_to_weathercan_sm.pdf)


## Before the workshop

-   [Install R](https://muug.ca/mirror/cran/)

-   [Install RStudio](https://www.rstudio.com/products/rstudio/download/)

    -   (**update RStudio** to the newest version, if it's already installed)

-   Install R packages for following along

    -   `weathercan` -> Note this needs to be installed from a specific source (see below)
    -   `skimr`
    -   `dplyr`
    -   `tidyr`
    -   `ggplot2`

    To install via R:  
    (This installs weathercan from the Community R-Multiverse)

    ```
    install.packages(c("skimr", "dplyr", "tidyr", "ggplot2", "weathercan"),
                     repos = c("https://community.r-multiverse.org", getOption("repos")))
    ```

-   Have available a location (latitude and longitude) of an area you'd like to get weather data for

# Use of this material for teaching

Are you an R educator? Do you want to give this workshop?

Go for it! I would love for you to adapt this material for your own use. It's licensed as GPLv3 which means you can free to copy, adapt, and use this material, but any modifications you make must also be shared under the GPLv3 licence.

Essentially if you use/adapt this material, I hope that you'll pay it forward and share with others.

I'd love to hear if you use this, how the workshop when (what worked, what didn't, and how you made changes), but that's not a requirement.

Have fun!