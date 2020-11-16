# PowerAmplifierInverseFunction
Background: Power amplifiers (PAs) have nonlinearity, which can be modeled with different nonlinear functions. Lets assume that the PA output at time 't' is a function of inputs at time 't', 't-1', ..., 't-M', where 'M'is the memory of PA. 

Goal:
The goal is to model the inverse function that models the behaviour of a real power amplifier. In this script, we use random inputs and feed them to a real PA to measure the PA outputs. We use these inputs and outputs to model the PA nonlinearities with a neural network. Particularly, we find the inverse function that models the PA. Therefore, we find a function that gets the output of PA and gives you an estimate of the input that has been fed to PA.

To do so, we use the measured data using "weblab".

To run the code, take the following steps: 
1- Run MATLAB code to generate the required .mat files or use already generated (uploaded) .mat files 
2- Run Python code to find the inverse function of PA

Notes: 1- "weblab" is used to access output data from a real power amplifier. Random data input is fed into the PA, and the output is read from "weblab". Then, a fully connected neural network is used to model the PA behaviour. 
2- To generate random constellation we used "randconst" function. You should either write your own code to generate random constellaion or ask "RFWebLab@dpdcompetition.com" to access the code.

For more info about "weblab" please see http://www.dpdcompetition.com/
