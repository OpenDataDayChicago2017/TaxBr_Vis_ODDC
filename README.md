# TaxBrain Visualization Projects for Open Data Day Chicago 2017
This repository contains a description here of suggested visualization projects to augment the policy offerings from the TaxBrain web interface, as well as data sources to simulate what would eventually become a front-end integrated visualization tool.

[TaxBrain](http://www.ospc.org/taxbrain/) ([http://www.ospc.org/taxbrain/](http://www.ospc.org/taxbrain/)) is a web application that allows users with no economic modeling expertise to run a rich set of fiscal policy experiments using a number of sophisticated economic models.

The front-end web interface was built primarily through a partnership between the Open Source Policy Center at the American Enterprise Institute and developers at [Continuum Analytics](https://www.continuum.io/) in Austin, Texas. The TaxBrain web application allows users to change a large set of tax policy parameters, submit those changes to be executed in a sophisticated economic model, have the model run on Amazon Web Services (AWS), and return the results as (currently) tabular output on a permanent URL web page associated with that particular experiment. All the code for the front-end web app is available in the GitHub repository [https://github.com/OpenSourcePolicyCenter/webapp-public](https://github.com/OpenSourcePolicyCenter/webapp-public).

The back end of the TaxBrain web application is a suite of economic models ranging from microsimulation models that take 30 seconds to run ([Tax-Calculator](https://github.com/open-source-economics/Tax-Calculator)) to general equilbrium overlapping generations models that take seven hours to run ([OG-USA](https://github.com/open-source-economics/OG-USA)).


## Proposed visualization projects

1. Interactive visualizations for Cost of Capital Calculator output
2. Interactive visualizations for Tax-Calculator output
3. Interactive visualizations for OG-USA output


## 1. Interactive visualizations for Cost of Capital Calculator output

The [Cost of Capital Calculator](https://www.ospc.org/ccc/) ([https://www.ospc.org/ccc/](https://www.ospc.org/ccc/)) is a front-end web app for an underlying microsimulation model that takes corporate tax policy parameters and estimates the marginal tax rates on investment faced by firms broken down by industry, method of financing, and asset type.

Currently, the Cost of Capital Calculator output are tabular and can be changed by selecting different button options (see screenshot below).

![Alt text](/images/CCCscreenshot.png?raw=true "CCC Screenshot")

One potential visualization using this data that has been used by the Congressional Budget office is the bubble chart below. We would love any ideas or improvements that you might have for better visualizing the tabular data above.

![Alt text](/images/CorpBubble.png?raw=true "Corporate Bubble Plot")

Example data from the tabular output above is in the data folder of this repository. Tabular output for options Industry, METTR, and Reform are in [data/ccc_tab_output1.csv]()attached in the 

