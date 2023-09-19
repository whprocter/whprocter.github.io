In this short discussion, I will recap the main points posed by Chapter 3 of *Understanding reproducibility and replicability* from the National Academy of Sciences, as well as Rey 2009's *Show me the code: Spatial analysis and open source*.

Additionally, I will reflect on the following, along with other considerations:
1) To what extent does open source GIS help solve the problems of the reproducibility crisis for geography? How?
2) Are there problems with reproducibility and replicability in geography that open source GIS cannot help solve?

More than 230 distinct scientific fields and subfields.  Very specialized published literature.  Use of statistical analysis has expanded across disciplines.

Today's shift towards open science is merely the next step in a trend that has already been happening (ex. shift towards emphasis on randomized experiments with masking and the introduction of rigid experimental and trial protocols in the 1970s).

Democratization of data and computation --> available in all disciplines.

Pressure for researchers/scholars to get published in prestigious journals 

Potential biases of scientists - how do we identify and expose to improve accuracy in research results

The expansion of computational tools in the 1990s engendered propositions to establish expectations that data and code will be openly shared so that results could be reproduced, assuming that reanalysis of the same data with the same methods will yield the same results

Debate over the vocabulary and use of reproducibility vs. replicability:
Reproducibility = includes the act of a scond researcher recomputing the original results using the same data, code, and methods (transparencey and reproducibility of computations)

Replicability = obtaining consistent results across studies aimed at answering the same scienficic question, each of which has obtained its own data (can be the same or different researchers...what matters is collecting new data)

Underlying concepts:
1) are data layed out with sufficient transparency and clarity that the results can be checked?
2) if checked, do the data and analysis offered in support of the result *actually* support that result?
3) if the data and analysis are shown to support the original result, can the result reported be found again in the *specific study context* investigated?
4) can the result reported or the inference drawn be found again in a *broader* set of study contexts?

Variation in methods employed in a study: very slight changes in methodology can often go overlooked (ex. are survey questions conducted via email or over the phone?)

Rigor = strict application of the scientific method to ensure robust and unbiased experimental design

Transparency (of data, code, and computational methods) implies computational reproduccibility of the results.  The clarity, accuracy, specificity, and completeness in the description of study methods directly affects replicability.
---------
Open source = revolutionary collection of tools and processes through which individuals create, share, and apply new software and knowledge

Open source software and free software are similar, but have some key differences:
- free software has freely available source code, and users can modify program to suit their needs and run program for any purpose
- open source stresses more the practical benefits of open source licenses
--------
Ways that open source GIS solves reproducibility/replicability:
- open source software creates, nurtures, and grows communities of shared interest who will continue developing and organizing the code
- the volunteers
- continuous feedback channels where users can identify bugs, request features, and provide help to other users
- source code allows you to examine the precise implementation of a spatial analytical method
- errors in algorithms can be directly identified by the user
- code is usually free - students can use their own laptops to learn (don't have to rely on lab computer licenses)
- code is available to more students
- being able to access the code helps you learn...can break down the actual steps you are doing
- ability to examine, modify, enhance, and release source code to the wider community
- transparency mechanism to facilitate communication between scholars --> opens the dialogue for scientific inquiry when you can see the mechanisms you are working with
- user markets can be leveraged for new innovations essential to the reproducibility/replicability process (ex. designing specifically for that purpose, since those are the demands of the GIS user base)


Reproducibility/replicability issues in geography that open source GIS cannot solve:
-developer-centric nature of open source project
-fosters technological elitism --> only those with programming skills can participate in the development
- things can be designed for engineers and forget the end-user in mind
- poor quality documentation is a barrier for non-technical and technical users alike
- frequent updates --> teaching it is like trying to pin down a moving target (also a problem for long-term research projects which might start in an older version and have to continue in that older version because of incompatible updates)
- concerns of security breaches and quality control problems when there are multiple, often uncredentialed developers of it
- dependence on packages can be limiting
- you could in theory take open source code and use it to develop your own closed-source propriertary package *without any explicit attribution to the original authors* --> Google has done this, and has been criticized for it
- community-built infrastructure can be undervalued and underappreciated...open source developers likely won't be receiving fellowships or professor tenure --> and this type of image isn't historically welcomed in the scientific fields and academic reproducibility/replicability studies
- perception that documentation can be low quality
- Peer review in open source ≠ peer review in the context of academia


