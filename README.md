The world has grown warier of fossil fuel and 
has seen a large push towards renewable sources of energy. 
Solar energy is one of the biggest areas for renewable 
energy. As such many new solar power plants are being 
built or upgraded. This raises the question of which sites to 
select and whether it would be beneficial to upgrade an 
existing solar power plant. This project looks to address 
these questions by predicting total solar energy generation 
based on the local environment variables.

I. MOTIVATION

The importance and demand for energy from 
renewable sources have been on the rise. In this area, solar 
energy has seen the most focus. Governments across the 
world are leading this change by becoming energy 
independent through solar power plants, either 
implemented on rooftops or within city utility sites.
This project aims to help with this move by using local 
weather variables to predict annual solar energy produced.
The hypothesis proposed is that weather parameters like 
wind speed, temperature, solar radiation, day length, 
vapour pressure, precipitation, snowfall, and the altitude 
of the solar power plant impact the daily solar energy 
generated.

Hence, these variables are used to train a model for the 
prediction of solar energy production for the power 
stations present in Calgary. This model can then be used 
for capacity prediction of potential power plant locations.

II. METHOD

For this project, we are planning on using a fully 
connected ANN. The input for our model would be 
different environment variables and the output would be 
generated solar power.

The dataset would be collected from various sources. 
We are planning to perform the prediction on the City of 
Calgary. The location and power generation data will 
come from the official City of Calgary website and the 
environment data will be taken from the Daymet dataset.
The Daymet dataset is a NASA initiative that provides 
weather data for 1km grids in North America.

III. INTENDED EXPERIMENTS
We intend to fully explore the data before getting to the 
model building part. We want to see what variables are 
affecting power generation and if any correlation is 
present in the data. Further, we want to find out if and how
feature scaling affects the model. Also, we might 
implement feature reduction techniques if required.
After the data analysis, our focus would be on the 
model. We want to experiment with the number of layers 
and neurons in those layers. Lastly, we will test different
optimizers and training speeds.
