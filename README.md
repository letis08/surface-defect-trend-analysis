# surface-defect-trend-analysis
Analysis of surface defect trends using image-based defect scores
# Surface Defect Trend Analysis

This project analyzes surface defect images from an industrial production line
to understand whether defect intensity increases over time.

## Project Goal
Rather than only detecting defective parts, the goal is to analyze
**process degradation trends** using image-based defect scores.

## Methodology
- Images are converted into numerical defect scores
- Scores are ordered in production sequence (time)
- Trend analysis and threshold-based alarms are applied

## Key Features
- Image processing–based defect scoring
- Time series analysis of defect intensity
- Threshold-based early warning mechanism

## Dataset
NEU Metal Surface Defects Dataset  
(Dataset is not included in the repository due to size constraints.)

## Tools
- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## Outcome
The system identifies whether defect behavior remains stable or shows
early signs of process degradation.
