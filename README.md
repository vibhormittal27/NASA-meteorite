# NASA Meteorite Landings Analysis

## Overview
Analysis of 45,000+ meteorite landings recorded by NASA
spanning centuries of space rock discoveries on Earth.
Combines exploratory analysis, trend detection and 
Prophet time series forecasting.

## Dataset
NASA Meteorite Landings dataset from NASA Open Data Portal
45,716 meteorites recorded with location, mass and year data.
Source: data.nasa.gov

## What I Analyzed

### 1. Yearly Discovery Trends
- Plotted meteorite discoveries per year from 1800 to 2013
- Identified massive spike around year 2000
- Explained by Antarctic expeditions and database digitization

### 2. Mass Distribution
- Most meteorites are under 100kg
- Few extremely large meteorites skew the distribution
- Log scale required to visualize properly

### 3. Fell vs Found
- Most meteorites are Found — discovered long after landing
- Only small percentage observed Fell — seen falling in real time
- Shows how rarely meteorite landings are witnessed

### 4. Top 10 Heaviest Meteorites
- Identified heaviest meteorites ever recorded
- Largest meteorites found in specific geographic locations

### 5. Prophet Forecast
- Predicted meteorite discovery trend for next 10 years
- Upward trend confirmed — improving technology increases discoveries
- Uncertainty bands widen appropriately for long term predictions

## Key Findings
- Discovery spike around 2000 caused by Antarctic expeditions
  and mass digitization of historical paper records
- 99% of meteorites are under 100kg
- Most meteorites are Found not Fell — discovered long after landing
- Discovery rate increasing as technology and expeditions improve
- Prophet predicts continued upward trend in discoveries

## Why The 2000 Spike
The Antarctic Search for Meteorites program (ANSMET) launched
systematic expeditions finding thousands of meteorites on ice.
Dark rocks on white ice are easy to spot from aircraft.
Simultaneously historical paper records were digitized into
the NASA database — inflating counts for that period.

## Technical Stack
- Python
- Pandas
- Matplotlib
- Prophet — Facebook time series forecasting
- NumPy

## What I Learned
- Time series data requires understanding of trends and seasonality
- Domain knowledge explains what data alone cannot
- Prophet handles trend detection automatically
- Anomalous spikes always have real world explanations
- Space data is genuinely fascinating and tells stories about Earth

## Data Source
NASA Open Data Portal
data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh
