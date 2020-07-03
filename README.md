
# DataFactory
## Current contents
### Refresh PBI Dataset.json 
Refresh PBI Dataset is a standalone pipeline (no linked services or datasets needed) that allows you to refresh a Power BI dataset using the Power BI REST API. This pipeline was adapted from [Dave Ruijter's blog post](https://www.moderndata.ai/2019/05/powerbi-dataset-refresh-using-adf/) and code in [gist](https://gist.github.com/DaveRuijter/df7f7df5df6422a37f6bb03cc6e2c6b9). The original pipeline successfully refreshes a Power BI dataset. I added activities onto the end to poll for the refresh status and fail the pipeline if the dataset refresh fails. 
