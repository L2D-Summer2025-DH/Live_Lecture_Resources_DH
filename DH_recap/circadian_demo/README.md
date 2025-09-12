## 📈 Data Handling Recap 🕐

### 🔬 Circadian Rhythm Analysis Demonstration:

Using time series data from Drosophila movement tracking experiments, this demonstration analyses circadian rhythm patterns across different experimental groups. The dataset contains position tracking data for multiple fruit flies, with their x-axis positions recorded over time, along with metadata describing the experimental conditions and dates of data collection.

The aim of this notebook is to show how with time series analysis and data manipulation techniques, we can:

- Calculate velocity from position changes over time to identify movement patterns.
- Determine periods of activity versus inactivity using velocity thresholds.
- Group individual specimens by their experimental conditions for comparative analysis.
- Bin time series data into appropriate intervals for circadian analysis.
- Visualise circadian activity patterns with error bars showing variability between groups.

The data files included are:
- `circadian.pkl`: Contains time series x-axis position data for multiple Drosophila specimens
- `metadata.pkl`: Contains experimental group assignments and collection dates (both as pandas DataFrames)

All the files you will need are in this folder, and should you need extra information, please watch the recap lecture recording, [linked on this playlist.](https://www.youtube.com/playlist?list=PLTRx90_S7dFsE3y_e1nBCo2VDOshgbwcS)

Please replace all paths as relevant to whether you are uploading the files and coding from a Codespace, or whether you're downloading them to your local machine, and coding using an IDE of your choice.

We encourage you to play around with the code cells, adjust the time binning parameters, and explore different visualisation approaches. In this way, we hope you'll learn more about time series analysis techniques, and will hopefully be able to carry them over to your own datasets and work.

Happy coding!