# Wildfire prediction using IA

## Introduction
Wildfires is a problematic natural risk. Each year a new increased collection of catastrophic events are causing alot of humain, economic and ecological damages. Many reasons are behind the growing number of such events and they are mainly related to climate change and the urbain extensions in the wildland. The last summer was a saison of record devastation especialy in Northern Hemisphere. Prevention policies with a scientific aproach witch is based on prediction and management measures have become extremely important. 

## Wildfire modeling

* Physical based models: 

Several research works are dedicated to the understanding of the basic physical mechanisms governing the behavior of wildfires. In order to study the effects in wildfires spread, numerical simulation using a fully-physical fire model have the potential to accurately predict the parameters of interest and provide the basic information needed for proper description of  the fire propagation processes like heat transfers and  chemical  kinetics. 

The limiation of this kind of models is their complexity, coupling multi-phase equations with a large number of parameters is not trivial. The resulting simulations can be computationally intensive and they need a lot of resources. But, the reduced models [1] can be used for the calibration of parameters for other type of approches based on semi-physical or laboratory models for example.

* Empirical based models:

Empirical models, also called statistical models,  are  predicting  more  likely  fire  behavior  from average conditions and accumulating acknowledges obtained from outdoor observations. Just like the fully physical method, the empirical one is also dependent on the number of considered paremeters and the model cannot easily be generalized. But, with the emergence of data driven methods, many limitations can be exceeded. For example, in the case of forest fire prediction, a comparaion has been studied btween two popular artificial intelligence based methods, artificial neural networks (ANN) and support vector machines (SVM) [2]. A recent work with an application of a statistically-based regression model was done [3], and it concerns a located lands in Spain which are an intense wildfire hotspot around Mediterranean Basin (cf. image below).
 
![fig](https://user-images.githubusercontent.com/16169832/150703572-49146a6f-a127-42f9-93aa-cb5b2f8f036b.png)

Fig. 1: Fire danger forecasts initialized on July/August 2021, showing very extreme (purple shading) around the Mediterranean countries. Credit: The European Centre for Medium-range Weather Forecasts (ECMWF). It has recently developed an open source fire danger model, called the Global ECMWF Fire Forecast model (GEFF) [4].

## Case study

The aim of this case study is developing of a simple machine learinig model which can predict whether information fire spread from given set of data [5].

> add jupyter notebook here..

## Conclusion

## References

[1] Nicolas Frangieh et al. "Wildfires front dynamics: 3D structures and intensity at small and large scales". Combustion and Flame, Volume 211, 2020, Pages 54-67, ISSN 0010-2180. https://doi.org/10.1016/j.combustflame.2019.09.017.

[2] George E. Sakr el al. "Efficient forest fire occurrence prediction for developing countries using two weather parameters". Engineering Applications of Artificial Intelligence, Volume 24, Issue 5, 2011, Pages 888-894, ISSN 0952-1976. https://doi.org/10.1016/j.engappai.2011.02.017.

[3] Lara Vilar et al. "Modelling wildfire occurrence at regional scale from land use/cover and climate change scenarios". Environmental Modelling & Software,
Volume 145, 2021, Pages 105-200, ISSN 1364-8152. https://doi.org/10.1016/j.envsoft.2021.105200.

[4] GEFF repository: https://git.ecmwf.int/projects/CEMSF/repos/geff

[5] Forest Fires Dataset source: http://www3.dsi.uminho.pt/pcortez/forestfires/

