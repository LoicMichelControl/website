---
permalink: /
#title: "Academic Pages"
author_profile: true
redirect_from: 
  - /about/
---

<!-- I am a researcher associated with the Laboratory of Digital Sciences of Nantes [LS2N](https://www.ls2n.fr) (UMR 6004 CNRS) at École Centrale de Nantes, France. -->
  
  
I am a Research Associate in Control and Learning Systems at the Laboratory of Digital Sciences of Nantes [LS2N](https://www.ls2n.fr) (UMR 6004 CNRS), École Centrale de Nantes, France. I currently explore intersections between control theory, machine learning, and biologically inspired modeling.  
I also teach systems,control theory, and introductory programming as an adjunct lecturer.

My current research focuses on developing model-free and learning-based control approaches for complex multi-physical systems, with applications ranging from power electronics and robotics to biologically inspired motor control models.
I am particularly interested in bridging control theory with adaptive and neuro-inspired dynamics to better understand and design intelligent systems.
I also have strong interests in optimization algorithms and numerical methods as key enablers for advanced control and learning techniques.

<!-- My research primarily centers on
developing model-free control approaches applicable to multi-physical systems, such as
power electronics, aerodynamics, robotics, and epidemiology. I also have an interest in
related areas of applied computer science, including optimization algorithms and numerical
methods. ! -->
  
<!-- news ! -->

Brief bio...
---
I earned my Ph.D. from the University of Quebec (UQTR) in 2012, focusing on control applied
to power electronics systems. My doctoral work involved optimizing IGBT switching and
creating novel control strategies for power converters. Since then, I've built a diverse
academic and professional background that spans nonlinear control and numerical
methods.

My work includes developing model-control methodologies for different engineering fields like aerodynamics / CFD,
robotics, and epidemiology, including experimental validations. Additionally, I've worked on
algorithmic strategies for numerical (semi-implicit) differentiation and
numerical algorithms for simulation, involving the Parareal
algorithm and Non-Standard Finite Difference methods.


...and perspectives
------
Moving forward, I aim to broaden my expertise in control systems by exploring probabilistic
methods, especially concerning large-scale networked systems and neurocomputing. I'm
also keenly interested in programming and formal proof computing, which I am eager to
explore and develop further.

I am open to collaborative opportunities, particularly in the application of model-free control
algorithms. 


<font color='red'> <b> Application of model-free based control algorithms </b> </font>


In addition to advanced control techniques that require minimal process model
knowledge, I am passionate about exploring the properties of the Model-Free Control
method (Fliess & Join, 2013) and the [Para-Model Control](https://loicmichelcontrol.github.io/website/portfolio/) algorithm I proposed a few years ago. My
ongoing work includes developing a stability theory using optimization proof techniques and
formal proof environments.


<font color='blue'> Neural networks / connectome perspectives </font>
This is a very challenging work to build a growing neural network in order to explore the concept of learning through a closed-loop control algorithm and additionally propagate statistic information from the synaptic weights. 
To emphasize the interactions between the connections and the neurons, the connections are activated randomly, like into a « connectome », for which the neurons can be used simultaneously to learn and store several type of information 
from the learning process and the wiring statistics, depending on the configuration of the connections.
 [[GitHub]](https://github.com/LoicMichelControl/netPMC).

<div style="display:flex;text-align:center;display:block">
  <video controls="" style="width:50%">
    <source src="./files/figures/connectome_video_2103.mp4" type="video/mp4">
    Sorry, your browser doesn't support embedded videos.
  </video>
</div>
 
In another project, I started investigating the memory effect when the information are "stored" in neurons through a closed-loop [[Slides]](./files/figures/presentation_NN_memory.pdf).

 
<font color='blue'> Experimental & CFD aerodynamics for wind turbines </font> 
Development of a complete experimental setup 
within a wind tunnel environment at the LHEEA laboratory. 
The goal was to validate nonlinear control strategies 
devoted to manage the aerodynamic lift of wind turbines at the blade scale, taking into account local 
aerodynamic perturbations (such as fall down of the lift inducing lack of controllability). A fully customized embedded control board was designed for this purpose. 
In addition, we performed investigations of the lift-based control in CFD (using the [ISIS-CFD](https://lheea.ec-nantes.fr/research-impact/software-and-patents/isis-cfd) solver) 
as well as investigations within the [OpenFAST](https://www.nrel.gov/wind/nwtc/openfast.html)  environment of the Para-Model Control algorithm [[GitHub]](https://github.com/LoicMichelControl/lcost).

<div style="display:flex; justify-content:center;">
<div style="flex: 1 1 75%;align-self: center;">
    <img src="./files/figures/NS_equation.png" >
  </div>
  <video controls="" style="width:50%">
    <source src="./files/figures/airfoil_PMC_gust.mp4" type="video/mp4">
    Sorry, your browser doesn't support embedded videos.
  </video>
</div>

<font color='blue'> Experimental grasping control in robotics </font> A robot gripper, based on pneumatic muscles, has been developed 
in the framework of a PhD work (design of a new hand for grasping tasks - defended in Dec. 2022).
I have been associated to this work in order to develop a hybrid multi-objective control to manage speed, force and positioning sequential control  during 
grasping tasks.   

<div style="display:flex;text-align:center;">
  <video controls="" style="width:50%">
    <source src="./files/figures/video_gripper.mp4" type="video/mp4">
    Sorry, your browser doesn't support embedded videos.
  </video>
  <div style="flex: 1 1 75%;align-self: center;">
    <img src="./files/figures/JDA_portance_prehenseur.jpg" >
  </div>
</div>


<font color='blue'> Epidemiology HIV minimization </font> This was a joint work with the university of Aveiro (Portugal) to 
consider the [HIV propagation model](https://arxiv.org/abs/2004.11903) as a real-time control problem for which very interesting 
results have been obtained, highlighting more « flexibility » than optimal control strategy. 
Next steps would be to extend to PDE-based epidemiological models...

<div style="display:flex;text-align:center;">
<div style="flex: 1 1 75%;align-self: center;">
    <img src="./files/figures/SICA_model.png" >
  </div>
  <div style="flex: 1 1 75%;align-self: center;">
    <img src="./files/figures/CVIM_epidemio.png" >
  </div>
</div>

<font color='blue'> Control of the nonlinear Epstein Framework </font> 

An [Epstein frame](https://en.wikipedia.org/wiki/Epstein_frame) is a standardized measurement device for measuring the magnetic properties of soft magnetic materials, especially used for testing of electrical steels.

The normalized measurements require to use calibrated signals, for which a closed-loop aims to re-shape these signals according to the nonlinear magnetic properties of the materials under test.
This was the first experimental validation of the Para-Model Control, used to re-normalize the shape of signals in real-time, highlighting very interesting properties of "robustness" towards magnetic operating points, frequency of the signals... 
Although no dynamical model of the test-bed was available, the control was simulated initially with the [Jiles–Atherton model](https://en.wikipedia.org/wiki/Jiles–Atherton_model) of magnetic hysteresis. [[Slides]](./files/figures/PMC_Epstein_Frame.pdf)



<font color='red'> <b> Projects in power electronics & electrical networks </b> </font>

Among the very first applications I made in control through Model-Free Control and Posicast techniques.

<div style="display:flex;text-align:center;">
  <div style="flex: 1 1 75%;align-self: center;">
      <img src="./files/figures/Posicast_1.png" border="0">
  </div>
  <div style="flex: 1 1 75%;align-self: center;">
    <img src="./files/figures/Posicast_2.png" >
  </div>
</div>


I contributed also to develop a specific power converter  devoted to de-ice train pantograph, for which several
patents have been issued.

<div style="display:flex;text-align:center;">
  <div style="flex: 1 1 75%;align-self: center;">
      <img src="./files/figures/panto_circuit.jpg" border="0">
  </div>
  <video controls="" style="width:50%">
    <source src="./files/figures/video_panto.mp4" type="video/mp4">
    Sorry, your browser doesn't support embedded videos.
  </video>
</div>

In addition, I collaborated recently to the development (and debug) of a simulation 
software dedicated to calculate resonant nodes within the official French national 
electrical network model.


<font color='red'> <b> Numerical methods </b> </font>

I have also strong interests in numerical methods, that I do consider very close 
of control problems, dealing with the differentiation of noisy signals 
(used when differentiation is need in closed-loop), as well as studying ODE solver architectures.

<font color='blue'> Semi-implicit differentiation and observers for noisy signals </font> Development of homogeneous-based high-order differentiators to improve the robustness towards noise rejection and flexibility of the tuning [[Slides]](./files/figures/Differentiation_presentation_LS2N_0824.pdf). 

$$\left \lbrace \begin{array}{l}
{z}_4^+= z_4+  h \left( \lambda_4 { \mu^4} \left|{e_1}\right|^{4\,\alpha-3} \mathcal{N}_4  \right)  \\
{z}_3^+= z_3+  h \left(z_4^++\lambda_3 { \mu^3} \left|{e_1}\right|^{3\,\alpha-2} \mathcal{N}_3 \right)  \\
{z_2^+}= z_2+  h \left(z_3^+ {- h \frac{1}{2} z_4^+ } + \lambda_2 { \mu^2} \left|{e_1}\right|^{2\,\alpha-1} \mathcal{N}_2  \right) \\
z_1^+= z_1+ h \left( z_2^+ {- \frac{h}{2} z_3^+ +  \frac{h^2}{3!} z_4^+ } +  \lambda_1 {\mu} |{e_1}|^{\alpha} \mathcal{N}_1 \right)  \\
\end{array} \right.$$


where $$z_i$$ is the estimation of the $$(i-1)$$ th order of differentiation.

Denote $$y = x_1$$ the signal to differentiate.
The projector $$\mathcal{N}_q$$ for $$q = 1..4$$ behaves either as a sign function, or as a nonlinear "slope" depending on the value of the error $$e_1 = x_1 - z_1$$. It is defined by:

$$
\mathcal{N}_q (\epsilon_1):= \left \lbrace
\begin{array}{l}
\epsilon_1\in SD  \rightarrow \displaystyle{  \mathcal{N}_q = {\frac{\lceil \epsilon_1\rfloor^{q(1-\alpha)}}{ \lambda_q (\mu h)^q} } } \\    
\epsilon_1 \notin SD  \rightarrow  \mathcal{N}_q = \mathrm{sign}(\epsilon_1) \\
\end{array} \right.
$$



- application in robotics (PID-based closed-loop trajectories with parallel cable robot that need advanced differentiation);


<div style="display:flex;text-align:center;display:block">
  <video controls="" style="width:50%">
    <source src="./files/figures/CPR_diff.mp4" type="video/mp4">
    Sorry, your browser doesn't support embedded videos.
  </video>
</div>


- pneumatics piston (trajectory differentiation to be used in sliding mode control).



<font color='blue'> Numerical integration algorithms </font> 
- acceleration / extrapolation methods for series (Shanks & Wynn algorithms) could be used for example in the Parareal algorithm to improve the precision convergence;
- ODE solving using semi-implicit differentiation as a promising way to deal with usual numerical solvers by including observer-based differentiator to refine the precision of the numerical solution with respect to Euler and RK methods. [[GitHub]](https://github.com/LoicMichelControl/SemiImplicitDifferentiation)

<!---
<img src="./files/figures/panto_circuit.jpg" width="500">


<div style="display:flex;text-align:center;">
  <div style="flex: 1 1 75%;align-self: center;">
      <img src="./files/figures/panto_circuit.jpg" border="0">
  </div>
  <div style="flex: 1 1 75%;align-self: center;">
    <img src="./files/figures/panto_circuit.jpg" >
  </div>
</div>



-->
