# Forest Response Pathways in Blackwater National Wildlife Refuge

<img src="https://science.nasa.gov/wp-content/uploads/2023/11/sarp-patch.jpeg?w=1280&format=webp" alt="drawing" width="200" style="float: left; margin-right: 20px;" />

**Student Airborne Research Program (SARP) 2025**  
**Terrestrial Flux Group**  
**Graduate Mentor**: Kayla Preisler  
**Faculty Mentors**: Dr. Brandon Alveshere, Dr. Lisa Haber, and Dr. Chris Gough  

I conducted an independent research project on forest response pathways in the Blackwater National Wildlife Refuge, a region undergoing drastic forest loss due to saltwater intrusion. Using Landsat 8 to extract vegetation indices, I calculated time series metrics that allowed me to identify which forested areas are undergoing transformations, and which areas are stable or in recovery. I compared forest response pathways geographically and by elevation. This work will help inform adaptation strategies and land management techniques.


## Abstract
Coastal forests along the Chesapeake Bay are rapidly becoming marshes due to sea level rise and an increased frequency of extreme weather events. Predicting these ecosystem shifts is essential for climate adaptation responses. Previous studies have employed Normalized Difference Vegetation Index (NDVI) time series to characterize the resilience of coastal ecosystems; however, few have applied this method within the Chesapeake Bay coastal region. In particular, the Blackwater National Wildlife Refuge located along Maryland’s Eastern Shore offers various ecosystem services to waterfowl and tourists, making it a desirable subregion for study. This work aims to characterize ecosystem shift trajectories of upland forests in the Blackwater National Wildlife Refuge. We used the Landsat 8 record (2014-2024) to extract NDVI values for areas classified as upland forest. We calculated trends in NDVI and NDVI variation using Kendall’s τ (rank correlation) to characterize an area in one of four ecosystem shift trajectories: abrupt transition, gradual transition, recovery, or stability. We found that 14.7% is abrupt transition, 27.4% gradual transition, 17.3%% is recovery, and 40.6%% is stable. Mapping these regions qualitatively shows found areas closer to the coast are experiencing abrupt and gradual transitions, and areas farther from the coast are stable or in recovery. Comparing elevation and forest response pathways, we found that locations with abrupt pathways have lower elevations more than gradual, and gradual has lower elevations than recovery and stable pathways. We found no statistically significant difference between abrupt and recovery elevations.

## About this template

This template was generated as an example for how to format and upload project code to github. Remember that uploading your code can be an interative process - it doesn't have to be perfect the first time! First focus on getting your code online, then move onto progressively organizing the code. Once you reach the cleaning stage some things to look for include:

- Make sure each chunk of code has a comment or markdown explanation of what is happening in the code
- Delete code that isn't ever used. It can be hard (emotionally), but it helps the code you are using be more useful.
- Break your project code into a few different notebooks by analysis step and name them starting with a number. For example: `01_preprocessing.ipynb`, `02_timeseries_analysis.ipynb` and `03_visualization.ipynb`.
- Keep seperate folders for code and figures

To get even deeper into code cleaning, check out the [Good Research Code Handbook](https://goodresearch.dev/index.html).

Some notes:
- If you are using satellite images as part of your analysis they may be too large to upload to github. In that case simply upload your code.