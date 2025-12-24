This is a demonstration of how Student T Distributions can be used in R to help improve probability distributions used in risk calculations. This test example is based on industrial flow sensors, but the science can be applied to any industry. The purpose is to demonstrate the improvement in probability calculations by leveraging Student T distribution and compensating for fat tailed scenarios. 

The example is pulled from an industrial  flow sensor. In this case, the false reject with the flow sensor would lead to excessive alarms and alerts in a computer system. Costs would incur from excess investigations from maintenance and quality departments. In order to improve lean six sigma operations at controlling costs, a quality team would analyze the probabilty of alarms signaling so they can input it into their risk model. 

The input data was taken from a calibration report at an ISO 17025 laboratory. 5 test points were used to establish linearity. The residuals were calculated and a standard uncertainty and expanded uncertainty were calculated. From there the expanded uncertainty was set to a 95% confidence factor. 
Both data sets were modeled at 95% with one being modeled with 4 degrees of freedom representing the fat tailed risk adjusted distribution, while the second data set was modeled at 30 degrees of freedom representing a normal distribution. 

An application was developed to model different tolerances and output probabilities of false rejects. 

A perfect operation process with no process variation would underestimate risk if the fat tail risk wasn’t quantified. 

False Reject Risk (4 df): 0.776%

False Reject Risk (30 df): .003%

This relationship is non linear and scales differently depending on how the tolerances are set. 

Linearity was used as the only source of uncertainty due to logistical and economical factors. In most real-world cases, a calibration record would be a primary source of data in this case. 
The purpose of this test was to demonstrate how Student T Distributions can help improve probability calculations in risk determinations. 
