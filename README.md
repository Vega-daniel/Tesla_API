# Tesla_API
by Daniel Vega


 The original guide can be found [here](https://tesla-api.timdorr.com/).


# Introduction

It tends to be difficult to track the changes in all Tesla Vehicles since the company adds and removes features on a monthly basis as opposed to a yearly basis (what most auto manufacturers do). Therefore, we can use this API to find out exactly what options, hardware, and firmware the vehicle is equiped with.

In addition, this API provides the user information on Charge State, Drive State and vehicle Climate State.

<!-- #region -->
# Strategy and Process

- rauth was used to make the connection, you can find that [here](https://rauth.readthedocs.io/en/latest/api/#oauth-2-0-sessions).
- In addition to rauth, we used the json library:
```python
import json
```
- You can find the project [here](https://github.com/Vega-daniel/Tesla_API/blob/master/TeslaAPI.ipynb).
<!-- #endregion -->

# Next Steps

- Create a database of the charge state, drive state and climate state in order to perform time-series analysis

```python

```
