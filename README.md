# Joseph Hood PhD Dissertation LaTeX

## Quantized State Simulation of Electrical Power Systems

### Abstract

An alternative is proposed to the current state-of-the-art simulation methods for the transient simulation of electrical power systems. The proposed method combines the Latency Insertion Method (LIM), the Quantized Discrete Event Specification (QDEVS), and the Quantized State System (QSS) method of integration. Using LIM, the power system state equations are decoupled in a way that allows the formulation of the system into a QDEVS-compliant model, which can then be directly solved with various QSS integration techniques. This combination of methods is called the Quantized DEVS-LIM method, or simply, QDL. A key feature of QDL is the asynchronous updates of all system states, which has many implications. Some benefits of QDL for power system simulation are improved computational efficiency and the ability to model, within the same simulation, the wide range of fast and slow dynamic behavior inherent to power systems. Also, by careful selection of the quantization step size for each state, the desired balance of accuracy and speed can be achieved. Two object-oriented QDL simulator prototypes are developed, a MATLAB implementation for the efficient simulation of linear QDL systems, and a Python implementation for non-linear QDL systems using advanced QSS integration techniques. The suitability of QDL for very stiff systems is demonstrated by successfully simulating a system with a stiffness ratio around $10^{9}$. Also, the feasibility of applying the QDL method to real-world power systems is tested with a reasonably large (32 state), multi-machine, highly nonlinear power system. Some challenges encountered are the presence of steady-state oscillations, the difficulty in selecting acceptable quantization step sizes for larger systems, and inefficiencies in larger simulations due to excessive numerical noise. Several solutions to these problems are proposed and tested to various levels of success. Overall, the QDL method is shown to be a promising new approach to power system simulation that can provide important benefits over existing methods, especially if the remaining limitations can be adequately addressed.   
