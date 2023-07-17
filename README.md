# org.Ylipolytica.W29.eg.db

This is a unofficial org.db for *Yarrowia lipolytica* W29. It has been used in our previous study: 

> Ran M, Zhao G, Jiao L, Gu Z, Yang K, Wang L, Cao X, Xu L, Yan J, Yan Y, et al. Copper Ion Mediates Yeast-to-Hypha Transition in *Yarrowia lipolytica*. **Journal of Fungi**. 2023; 9(2):249. <https://doi.org/10.3390/jof9020249>

The reason why we build this org.db is that Bioconductor doesn't has such a resources, and many of existing org.db, for instance, <https://www.bioconductor.org/packages/release/data/annotation/html/org.EcK12.eg.db.html> is outdated.

It is a R package. To reuse this package, just install it with **devtools**.

`devtools::install_github("gaospecial/org.Ylipolytica.W29.eg.db")`

then we can use it

`library(org.Ylipolytica.W29.eg.db)`

