
# Notes


# Previous work for another hackathon

* [devpost proj entry](https://devpost.com/software/virtual-sensors-for-water-level-prediction)
* [previous git repo](https://github.com/gdg-cloud-rtp-devpost-tf-2019/tf-hackathon)

## Hi-lites on orig repo

| code                 | Notes                                                                                             |
| -------------------- | ------------------------------------------------------------------------------------------------- |
| src/ML-try-007.ipynb | Was the final submission code                                                                     |
|                      | Sets up the notebook to use tensorboard.                                                          |
|                      | I doubt tensorboard works in watsonx - remove it                                                  |
|                      | Uses ./csv/usgs_gsvb_v2.csv for data                                                              |
|                      | The input has 9K rows and 8 columns                                                               |
|                      | Should break this up into a single file to generate the clean data including a yaml data contract |
|                      | adds new columns, normalizes the data                                                             |
|                      | -- cut off for cleaning data --                                                                   |
|                      |  The rest of the code has:                                                                        |
|                      |     * Defining model                                                                              |
|                      |     * training model                                                                              |
|                      |     * testing model                                                                               |
| csv/usgs_gsvb_v2     | Initial set of *raw* data                                                                         |
|                      | Originally this data came from two sources USGS and Greenstream sensor data                       |
|                      | This dataset has been massaged and combined previously to make the current file.                  |



# other urls

* [the guy who did demo code](https://github.com/nicknochnack)
* [signup to use watson x](https://dataplatform.cloud.ibm.com/wx)
* [hackathong url](https://developer.ibm.com/callforcode/events-register?slug=techxchange)
* [other url](https://compete.cfc-prod.skillsnetwork.site/competitions/call-for-code-at-ibm-techxchange)
* [hackathon resources](https://compete.cfc-prod.skillsnetwork.site/competitions/2023-call-for-code-global-challenge)

# Hackathon Objective

Water is listed as one of the objectives.  The specific water entry is "Address issues of water scarcity and quality".  
In this case, the project measures water level (scarcity) at a postion based upon nearby sensors.


