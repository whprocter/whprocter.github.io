**Navigating Uncertainty in Spatial and Geographic Research**

Uncertainty is an ever-present and complex challenge in the field of spatial and geographic research. As geographers, we often find ourselves at the crossroads of imprecision and ambiguity, grappling with the inherent limitations of representing the multifaceted real world in digital formats. It's a reminder that our digital representations of the world are incomplete, and the imperfections within them can arise from various sources, including measurement error, outdated data, and excessively generalized information.  

Longley et al (2008) specifically defines uncertainty as an umbrella term to describe the problems that arise from imperfectly being able to represent the world around us, since the complexity of the world makes it impossible to capture every facet and scale in a digital representation.

In practice, uncertainy stems from a multitude of sources, ranging from uncalibrated measurement equipment, to working with out-of-date data for a study, to employing an excessively generalized statistical model, to even human error.  With so many sources of error, it is challenging to visualize the general different **types** of uncertainty and how they relate to each other. In Chapter 6, Longley et al (2008) places different sources of uncertainty into different "buckets" along a progression from real world phenomena to representative geographic analysis.

The real world is ground zero with no inherent uncertainty.  However, as soon as we begin to conceive and define even the most basic units of geographic analysis (before we even get to collecting, recording, or analyzing data), there are sources of uncertainty.  For instance, there are rarely truly "natural units" in geography.  What we determine to be a "cluster" of disease cases or the "spatial extent" of the impacts of an oil spill are rather subjective, and these units can be vague.  Even the language we use to discuss these spatial units of natural phenomena can be ambiguous; across, over, in, on, etc all depend on one's perception, literary understanding, human behavior, language, and culture. Additionally, there are assumptions that we as scientists make to link indicators to phenomena, where subjectivity comes into play yet again.  For instance, we assume that size of a tree is implicative of the tree's value, but yet size is fundamentally not the same thing as value.

Next, once we have the linguistic and fundamental units established, we can perform measurement and create representations of data, which ushers in the more commonly acknowledged sources of uncertainty.  These can range from generalized statistical models, prediction of false positives and false negatives, trying to linearize raster data to create a border and vice versa, positional error of coordinates, etc.

Ultimately, once we reach the level of actual geographic analysis - which ushers in a whole other potential for increasing uncertainty, ranging from the MAUP to external validity concerns - error and uncertainty can propagate along the path from real world to geographic conceptions to measurement to analysis.  Moral of the story?  Minute differences between the real world and how we model it can compound/snowball to ultimately yield analytical results that are not perfectly representative of the real world.  While error itself is inevitable, we should seek to minimize and acknowledge it in our work. 

Geographers, by virtue of their work, gain firsthand knowledge of these many uncertainties. They've encountered measurement errors that introduce variability, struggled with data that has become outdated over time, and faced the challenges of data that are overly generalized, limiting the accuracy of their analyses. These experiences underscore the need for geographers to adopt a responsible approach to managing uncertainty in their research.

As geographers, we have a set of crucial responsibilities when it comes to uncertainty in our research:

**Transparency**: Our primary responsibility is to be transparent about the sources of uncertainty in our research. Whether it's measurement error, outdated data, or ambiguity in definitions, acknowledging these uncertainties is the first step in ensuring that our findings are credible.

**Documentation**: We must meticulously document the sources of uncertainty and the methods employed to address them. This documentation serves as a valuable guide for other geographers who may wish to build upon or adapt our research. It enables them to understand the precise level of uncertainty present in our analyses.

**Standards and Consistency**: To bolster the reliability of geographic research, it's crucial for the community to agree on consistent standards. Reducing ambiguity and vagueness in our definitions and methodologies helps create a solid foundation for future work.

Fulfilling these responsibilities requires the application of several key strategies:

**Open-Source Scholarship**: Embracing open-source practices, such as making data, code, and research findings accessible to others, enhances transparency and invites collaboration and scrutiny. This collaborative approach can help uncover and address uncertainties effectively.

**Standardization**: Collaborative efforts to establish standards for data collection, processing, and analysis can minimize variability and enhance the consistency of geographic research.

**Error Propagation**: Geographers should consider the impact of uncertainty on their results. Developing strategies to measure and account for error propagation, particularly when conducting spatial analyses, is essential. Geographers must acknowledge and emphasize this such that future users of their work can accurately understand the quality and similarity of their representations to real-world phenomena that they are trying to analyze or model.

**Validation**: Prioritizing internal and external validation of research findings is crucial. Acknowledging that uncertainties in data can lead to uncertainties in the results of analyses is a critical step in addressing and mitigating these challenges. This can involve overlaying datasets with different lineages to reveal and rectify unexpected errors.

In my own experience, working with outdated and non-standardized raster has presented a major source of uncertainty.  During Fall 2022, I had the privilege of working as a Research Assistant for Professor Will Amidon at Middlebury College, working on using raster climatic data to use as equation inputs for modelling evapotranspiration rates in Utah.  The gridded dataset that we were working with did not have much metadata, and we struggled to understand what exact units the radiation and windspeed layers were presented in.  The best we could do was assume that it met the conventions for what we saw other papers commonly using.  Ultimately, our modeled evapotranspiration seemed to do a decent job predicting actual measured evapotranspiration, but we had to carry uncertainty in our model that stemmed from our lack of complete confidence in knowing the measurement units.

In conclusion, uncertainty is an intrinsic and complex aspect of the geography field. Rather than trying to eliminate it entirely, our role as responsible geographers is to acknowledge, manage, and document it. By embracing transparency, standardization, and the open sharing of our work, we can continue to uncover the intricate and nuanced stories that geographic research has to tell, while enabling others to build upon our findings with a clear understanding of the inherent uncertainties.


**REFERENCES:**
Longley, P. A., M. F. Goodchild, D. J. Maguire, and D. W. Rhind. 2008. Geographical information systems and science 2nd ed. Chichester: Wiley.
 > Chapter 6: Uncertainty, (pages 127-153)
  
Tullis, J. A., and B. Kar. 2021. Where Is the Provenance? Ethical Replicability and Reproducibility in GIScience and Its Critical Applications. Annals of the American Association of Geographers 111 (5):1318–1328. DOI:10.1080/24694452.2020.1806029
