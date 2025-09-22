# isc-proposal for birdnetTools expansion with occupancy modelling


## Useful links
- [Proposal file folder](https://github.com/SunnyTseng/R-consortium-ISC-Grant-application/tree/main/proposal_birdnetTools): edit and render the quarto file, then the .pdf and .html will be generated automatically.
- [R Consortium](https://www.r-consortium.org).
- [ISC Grant Program](https://r-consortium.org/all-projects/callforproposals.html)


## Background
BirdNET is the most widely used algorithm for automated bird species identification from audio recordings, which can identify more than 6,000 bird species from audio data, making it a powerful tool for large-scale avian monitoring. R packages such as `birdnetR` (to run BirdNET) and `birdnetTools` (for post-processing BirdNET output) allow users to streamline acoustic data analysis. One of the most fundamental applications of BirdNET detections is generating species presence/absence data across sites and time periods for occupancy modeling, which provides essential information on species distribution, detectability, and probability of occurrence. However, preparing BirdNET data for occupancy analyses is often challenging, particularly for ecologists without extensive programming experience. Existing R tools for occupancy modelling, like `unmarked` and `spOccupancy`, require data in very specific formats and involve complex, multi-step workflows, creating barriers to efficient and reproducible analysis.

This project aims to bridge this gap by improving and expanding the functionality of `birdnetTools`. While `birdnetTools` already offers generic tools for data wrangling, summarization, and validation, it does not yet provide streamlined workflows specifically tailored for occupancy modeling. By designing functions that automate the transformation of BirdNET outputs into formats compatible with occupancy modeling packages, we can significantly reduce the technical burden on users, enabling ecologists and conservation practitioners to more easily leverage passive acoustic monitoring data for occupancy analyses and generate reproducible ecological insights.
