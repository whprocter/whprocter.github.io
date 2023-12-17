Back in 2020, Kang et al. (2020) measured spatial accessibility to COVID-19 healthcare resources in Chicago, looking at how COVID-19 patients and the at-risk population's access to hospital resources such as ventilators and ICU beds varied across space.  It served as a proxy for the resilience and capacity of the healthcare system, and identified regions that were underserved.  The original study employed a network analysis of Chicago's road network to calculate service regions and catchment areas for hospitals, based on the time it takes to drive to the hospital from different points in the city.  They then calculated service ratios for hospital catchment areas (based on ICU beds/ventilators and COVID-19 patients/at-risk population) and presented these in accessibility maps using a grid of hexagonal as a spatial unit.

I reproduced the Kang et al. study, and built on a prior reproduction conducted by Joe Holler, Derrick Burt, and Kufre Udoh, with contributions from Peter Kedron and Drew An-Pham.  Most notably, I improved how travel times to the hospitals were calculated by imputing missing speed limit data for the road network.  I used the newly-available OSMNX speed and time functions to impute speed limits for roads that were missing speed limits, based on the mean speed limit of roads with similar features (the old approach simply assigned a speed limit of 35mph to roads missing speed limit data).  I found that generating hospital catchments using more accurate speed limits increased accessibility, although this is not what I would have expected given that the majority of roads in Chicago have speed limits of 25mph (less than the 35mph speed limit imputed in the original study).  I would expect lower average speed limits to decrease hospital catchments and thus also decrease accessibility.  I will continue to troubleshoot my code to see if I made an error somewhere that led to this result.

In the report, I comment on sources of geographic uncertainty pertaining to the Kang et al. study.  My contributions helped to reduce space-time interaction threats and slightly tackle the issue of partition distortion.  However, geographic uncertainty is stll present in the study, even after my methodological improvements.

The accessibility maps produced from this study shed valuable light on how spatial accessibility to healthcare resources is far from consistent in Chicago.  While central Chicago has fairly high accessibility rates, the southeastern corner of the city is significantly lacking in healthcare resources.  These maps would be highly useful for policymakers looking to expand health equity in Chicago.

You can find the my reproduction report [HERE](https://whprocter.github.io/RPr-Kang-2020/)

You can find the repository for my reproduction [HERE](https://github.com/whprocter/RPr-Kang-2020)


**REFERENCES:**

Kang, J. Y., A. Michels, F. Lyu, Shaohua Wang, N. Agbodo, V. L. Freeman, and Shaowen Wang. 2020. Rapidly measuring spatial accessibility of COVID-19 healthcare resources: a case study of Illinois, USA. International Journal of Health Geographics 19 (1):1–17. DOI:10.1186/s12942-020-00229-x.
