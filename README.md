# HPC-for-materials

## Applications of HPC in materials

High-performance computing (HPC) plays a crucial role in the field of materials science, as it allows researchers to perform advanced simulations, calculations, and analyses of materials at various length and time scales. By leveraging the power of HPC systems, researchers can gain insights into the fundamental properties of materials and design new materials with specific properties for various applications. Some of the key applications of HPC in materials science include:

1. Electronic structure calculations: HPC is used to perform quantum mechanical calculations, such as density functional theory (DFT) and many-body perturbation theory, to study the electronic structure of materials. These calculations provide insights into material properties like band structure, density of states, and magnetic properties, which are essential for understanding and predicting material behavior.

2. Molecular dynamics simulations: HPC enables large-scale molecular dynamics (MD) simulations, which involve the study of the motion and interactions of atoms and molecules over time. These simulations can reveal essential information about material properties, such as mechanical strength, thermal conductivity, and diffusion rates.

3. Monte Carlo simulations: HPC is utilized for Monte Carlo simulations, which involve statistical sampling techniques to explore the thermodynamic properties of materials, such as phase transitions, chemical equilibrium, and reaction kinetics.

4. First-principles calculations: HPC allows for accurate first-principles calculations based on quantum mechanics, which can predict various material properties, such as electronic, optical, and vibrational properties, without relying on experimental data.

5. Materials genome initiative: HPC plays a significant role in the Materials Genome Initiative, which aims to accelerate the discovery, design, and deployment of new materials by leveraging computational methods, data mining, and machine learning techniques.

6. Machine learning and data-driven materials discovery: HPC enables the application of machine learning algorithms for materials discovery, which involves training models on large datasets generated from simulations or experiments to predict material properties and identify new materials with specific characteristics.

7. Multiscale modeling: HPC allows for the integration of models across different length and time scales, providing a comprehensive understanding of material behavior from the atomic level to the macroscopic level.

By harnessing the power of HPC, researchers can accelerate materials discovery, optimize material properties for specific applications, and reduce the time and cost associated with experimental studies, leading to significant advancements in fields such as energy storage, electronics, aerospace, and medicine.

**The Materials Project(by the Lawrence Berkeley National Laboratory)** https://materialsproject.org/

The database contains over 1M computed properties based on DFT.

Introduction: Harnessing the power of supercomputing and state-of-the-art methods, the Materials Project provides open web-based access to computed information on known and predicted materials as well as powerful analysis tools to inspire and design novel materials.

## What is high performance computing?

Open course: https://omscs.gatech.edu/cse-6220-intro-hpc

High performance computing also known as supercomputing, scalable parallel computing, it's different from personal laptop and web server. HPC is about solving big, complex, computational-expensive problems as efficiently as possible.

“Scale” refers to two things: efficient as the problem size grows, and efficient as the system size grows (measured in numbers of cores or compute nodes).

There are many scientific problems requires increasingly more efficient algorithm and computational resources. We can use supercomputers to do many important stuff. Stuff like:

    • Weather forecast
    • Solid state materials (thousands of millions of atoms in condensed matter)
    • Bio-molecules system(protein)
    • Computational fluid dynamics
    • Image processing
    • Financial risk management
    • Cosmology
    • AI(large language model. With the demands of machine learning outstripping conventional computing, HPC is also at the forefront of artificial intelligence)

Many scientists believe we won't gain any insight into these problems without some combination of mathematical models, algorithm, more high quality data.

The main question we should be interested in is, given a computational problem and an affordable machine, how can we compute at the absolute limits of scale and speed.

We will encounter many limits throughout the field of HPC, one of the interesting ones, come from physics, like the limit based on the speed of light, or the amount of energy, power or heat transfer in the materials inside the system. 

That's why I'm also interested in quantum computing system, which represents the ultimate state of physical computation. I believe it's a promising solution to break the limits of conventional computing systems.

## Why high performance computing?

Computation or simulation is the third methodology after theory, experiments. However, accuate, faster and bigger system in scientific computation and modeling drive the need for greater computing resource, but single-core processors(serial processor) don’t have enough resource for such assignments.

### Limitation

Making processors with faster speed is difficult due to cost and energy, thermal, speed of light limitations. 

Moore's law: Clock speed increases as inter-transistor distance decrease, so performance doubled every 18-24 months. However, the distance between transistors cannot be shortened infinitely(Quantum tunnelling)

It's also unrealistic to put huge memory on a single processor. 

That's why we need HPC to divide the work among numerous linked systems, solve these parts simultaneously, and bring all the intermediate answers together to get the final answer.

## What's the performance refers to in HPC?

For scientific computation, use FLOPS(floating point operations per second)

generally, the peak or the maximum number of floating point operations we can do in per second. Modern supercomputers measured in PFLOPS(PetaFLOPS)

Kilo, Mega, Giga, Tera, Peta, Exa=10^3, 10^6, 10^9, 10^12, 10^15

Runtime for specific code.

## HPC system layout and work flow


**Typical layout**

<img width="741" alt="Screenshot 2023-04-13 at 00 25 24" src="https://user-images.githubusercontent.com/98719524/231661615-945c3f03-d4d9-4f1f-97fe-97ed1ad9faf6.png">

**Typical usage flow**

<img width="849" alt="Screenshot 2023-04-13 at 00 26 18" src="https://user-images.githubusercontent.com/98719524/231661748-8100512b-e650-4b5f-8105-7edb881e75b7.png">


# Some useful tools that pave the way to HPC

### 1.Bash Scripting Tutorial – Linux Shell Script and Command Line for Beginners

https://www.freecodecamp.org/news/bash-scripting-tutorial-linux-shell-script-and-command-line-for-beginners/


# Other relevant topics 

## DFT, HPC, machine learning

#### DFT: physics-informed materials research, based on equation and physical meaning.

Schordinger's equation

Kohn-Sham equation


#### Machine learning: data-driven materials research, based on big data and statistics.

#### HPC: GPU acceleration for real ab initio calculation


## HPC: pave the way to quantum computing

Know more about computer architecture, hardware layout, electrical and optical connections, etc.



