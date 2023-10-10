<div>
<img src="slides/img/IRIS-HEP%20logo.png" width="200" align="right"/>
</div>
<div>
<img src="slides/img/Princeton%20logo.png" width="150" align="right"/>
</div>

# An Awkward module for round-tripping data structures between Python and Julia
Both Julia and Python have a strong presence in the sciences. In a typical HEP data analysis process Python is more common, however, there is an obvious advantage to transitioning legacy software to Julia. We discuss the sharing of Awkward Array data structures between the two worlds to encourage the Python users to run their analysis both in an eco-system of their choice and in Julia.
We discuss how the memory, the data buffer copies, and the dependencies are managed. We analyse the performance acceleration calling Julia from Python and vise versa for the intensive array-oriented calculations on a large scale, but not very large dimension arrays of HEP data.

## Acknowledgements
<div>
<img src="slides/img/NSF%20logo.png" width="60" align="left"/>
</div>

Support for this work was provided by NSF cooperative agreement [OAC-1836650](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1836650) (IRIS-HEP) and PHY-2323298

