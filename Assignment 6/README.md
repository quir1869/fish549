# Package title
ggalt

# Location
It can be found on the CRAN (https://cran.r-project.org/web/packages/ggalt/index.html) and an be downloaded using:

> install.packages("ggalt")

OR...

> devtools::install_github("hrbrmstr/ggalt")

# Vignette
ggalt has one formal vignette called “ggalt::ggalt_examples” that shows sample visualizations that can be made with the functions in this package

# Application
This package offers additional functionality to ggplot2, adding extra visualizations (e.g., lollipop plots, dumbbell plots, extra ggplot geometries, 2d density/correlation plots)

# Review

The primary purpose of ggalt is data visualization, providing additional usage to the existing ggplot2 package. The ggalt functions can be added in the same syntax to ggplot objects (e.g., ggplot() + geom_lollipop - lollipop is a ggalt function) to create new plots. One thing I appreciate is that it can be nice to use dumbbell plots to visualize and compare means between two groups (e.g., create a graphic comparing the mean flipper length of Chinstrap and Gentoo penguins). While there are functions for density plots within ggplot, I don’t see how their 1D density plot differs from the base ggplot density() function, making the function seem redundant. The package is easy to learn to use due to the similar function integration on ggplot objects, otherwise learning a new syntax would become cumbersome when making graphics. I would recommend this package to people who are interested in new forms of data visualization as it is simple to pick up. My one critique is that lollipop charts can quite be replicated with bar plots with the only difference being that they look slightly different. It is, however, useful for 2d density / correlation plots.

I am OK with Mark posting my review to the course website and he can use my name (i.e., attribute the review to me).
