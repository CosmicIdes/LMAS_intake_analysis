# LMAS INTAKE ANALYSIS PROJECT



## Instructions to run

The data is included in the project.

### Setup python environment

```python
bash
git clone https://github.com/CosmicIdes/LMAS_intake_analysis.git
cd LMAS_intake_analysis
```

Python environment:
```python
bash
python-m venv venv
```

Activate environment:
mac/linux
```python
bash
source venv/bin/active
```

windows/cmd
```python
cmd
venv/Scripts/Activate
```

Run [notebook](main.ipynb)



### Install modules/libraries 

```python
bash
python -m pip install -r requirements.txt
```

## Background info
This project is an exploration of the intake data that Louisville Metro Animal Services (LMAS) offers as of December 3, 2025. To retrieve more up-to-date data, visit Louisville Metro's Open Data Portal [here](https://data.louisvilleky.gov/datasets/733145c30ad94d43bdc6aba7fd0fdb09_0/explore).


## Summary
In this project, I did some cleanup and EDA, before diving in and creating a few charts:

* Return and Adoption Rates at LMAS
    * This series of charts explores what the return and adoption rates are, and how they relate to each other.

* Return Reasons
    * A sunburst chart that displays the various reasons an animal was returned to LMAS. I ran this only on animals that had more than one entry.

* Intake According to Season
    * This heatmap displays what seasons animals are more likely to be taken into LMAS. It does not explore reasons, but seems like a good diving-off point for future analysis.


## Future Charts
In the future I'd like to explore the following, some of which would require additional data sources to be brought in:
* Black cats/Friday the 13th
* Policy changes that influenced the rate of pickups/adoptions happened
* Impact on spay/neuter programs
* Holidays
* Which breed is returned more/adopted
* What is the average income in neighborhoods that intakes are occurring at?