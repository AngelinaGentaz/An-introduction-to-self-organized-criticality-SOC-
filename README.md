# An-introduction-to-self-organized-criticality-SOC-

Welcome! This project file is very big, so GitHub may not be able to display it correctly, in which case I recommend that you download it and open it yourself on Jupyter Notebook.  

*Abstract*:  
Our project is inspired by the work of the physicist Per Bak, who coined the term 'self-organising criticality'. In his book 'When nature organizes itself', he tries to establish a simple model to study the evolution and interactions of living species and to account for natural selection through his point of view as a physicist/mathematician and this is what we are interested in.  

The algorithm is as follows: we arrange the species spatially on a circle. Each species interacts with its two neighbours on the circle, which could correspond to something like a food chain in which each species has its predator on the left and its prey on the right. At the beginning of the simulation, each of these species is assigned a random number between 0 and 1, this number representing the fitness of the species. At each time step, the lowest number, as well as the numbers of its two neighbours, are replaced by new numbers between 0 and 1 drawn at random.


