# QOSF-Mentorship
 This is the answer to screening task 1 of the second round of QOSF mentorship program.

The file task1-v1 uses scipy.optimize.minimize to minimize the cost function and in each update of the cost function builds a new QuantumCircuit object.

In task1-v2 a parametric circuit is built in the begining and the parameters are updated by minimize function.

In task1-v2-bonus the Rx gates in the odd blocks have been replaced by Ry gates. The final circuit converges with almost the same order of magnitude of layer numbers and optimization time.
