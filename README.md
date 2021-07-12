# Optimization_Electricity_Dispatching
This real-world optimization problem of Electric Power Dispatching in Sweden includes the phases of **data collection**, **problem modeling** and **optimization solution**

Electricity is the vital energy source in both industrial production manufacturing and people’s daily lives so the importance of electric power generation and transmission is beyond question. As a link between electric power generation and transmission, electric power dispatching decides the effective and healthy operation of the whole power grid.
The automation and intelligence of electric power dispatching is a long time issue concerning power grids deserving thorough research.

* #### data collection
In the first phase, ten cities of Sweden were chosen,then by tracking the power lines passing through these ten cities and locating the power plants that provide electricity to them, the below graph shows cities and their connected power plants assuming that these power plants are only at the service of the Swenden cities (power line routes can be found in [openinframap](https://openinframap.org/#5.38/62.287/16.149)).
<p align="center">
  
<img src="https://github.com/niushamir/Optimization_Electricity_Dispatching/blob/main/Images/Sweden%20Map.jpg" width="350" height="400">
  
<img src="https://github.com/niushamir/Optimization_Electricity_Dispatching/blob/main/Images/Graph.jpg" width="900" height="500">


</p>
   
* #### problem modeling
The cost of each link in our problem is simplified and considered as the lenght/resistance of each link.

*This table determines lengths and types of each electric powwr transmission line between nodes (cities)*:
<p align="center">
  
<img src="https://user-images.githubusercontent.com/40741680/125337205-f49b0680-e363-11eb-940f-5e3d077d8005.png" width="800" height="300">
  </p>
  
  * #### optimization solution
  Python (MIP library) is used for implementing the solution. please find the step-by-step description of the code implementation in *code.ipynb* notebook.
  ##### Solution figure legends:	
  - The required production capacity of each power plant is shown in ![#0000ff](https://via.placeholder.com/15/0000ff/000000?text=+) `blue color`
  - The transmission power of each line is shown in ![#c0c0c0](https://via.placeholder.com/15/c0c0c0/000000?text=+) `gray color`
  - The consumed power of each ecity is shown in ![#f80400](https://via.placeholder.com/15/f80400/000000?text=+) `red color`
  <p align="center">
  
<img src="https://github.com/niushamir/Optimization_Electricity_Dispatching/blob/main/Images/Solution.jpg" width="900" height="500">
  </p>
  
  
You could find more detailed information in the *Report.pdf* file.
