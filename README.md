# HPC-for-materials

Strongly recommended open source: 

**The Materials Project(by the Lawrence Berkeley National Laboratory)** https://materialsproject.org/

Introduction: Harnessing the power of supercomputing and state-of-the-art methods, the Materials Project provides open web-based access to computed information on known and predicted materials as well as powerful analysis tools to inspire and design novel materials.

## What is high performance computing?

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





# Other relevant topics

## DFT, HPC, machine learning

#### DFT: physics-informed materials research, based on equation and physical meaning.

Schordinger's equation

Kohn-Sham equation


#### Machine learning: data-driven materials research, based on big data and statistics.

#### HPC: GPU acceleration for real ab initio calculation


## HPC: pave the way to quantum computing

Know more about computer architecture, hardware layout, electrical and optical connections, etc.



