# Distances between Triangles and Points in 3D (on a GPU)

<p align="center"> 
<img src="https://github.com/ml-jku/TPDistance/blob/main/triangle.png" height="300" alt="Triangle - Cases">
</p>


This is a pre-release of the code for the computation of distances between triangles and points in 3D from our work on [**Boundary Graph Neural Networks for 3D Simulations**](https://arxiv.org/abs/2106.11299):

    @misc{bib:mayr2021boundary,
      title={Boundary Graph Neural Networks for 3D Simulations},
      author={Andreas Mayr and Sebastian Lehner and Arno Mayrhofer and Christoph Kloss and Sepp Hochreiter and Johannes Brandstetter},
      year={2021},
      eprint={2106.11299},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
    }

 and our work  on [**Learning 3D Granular Flow Simulations**](https://arxiv.org/abs/2105.01636):
 
    @misc{mayr2021learning, 
      title={Learning 3D Granular Flow Simulations}, 
      author={Andreas Mayr and Sebastian Lehner and Arno Mayrhofer and Christoph Kloss and Sepp Hochreiter and Johannes Brandstetter}, 
      year={2021}, 
      eprint={2105.01636}, 
      archivePrefix={arXiv}, 
      primaryClass={cs.LG} 
    }

<br>

We adopted the computation idea from [**Eberly (1999)**](https://www.geometrictools.com/Documentation/DistancePoint3Triangle3.pdf), especially 
from a former version of an C++ implementation, that seems now available [here](https://www.geometrictools.com/GTE/Mathematics/DistPointTriangleExact.h). The possible best citation for the work of Eberly (we found) is this (although the included journal link does not seem to work anymore):

    @article{eberly1999distance,
      title={Distance between point and triangle in 3D},
      author={Eberly, David},
      journal={Magic Software, http://www.magic-software.com/Documentation/pt3tri3.pdf},
      year={1999}
    }
    


### Please note:
1. 
**THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT
SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE SOFTWARE BE LIABLE
FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.**

2.
**FOR THIS SOFTWARE, WE DID NOT TAKE ANY CARE FOR ANY POTENTIAL 
NUMERICAL PROBLEMS (DATA TYPE CONVERSIONS, CUT-OFF ERRORS, 
NUMERICAL PRECISION, ETC.). THIS SOFTWARE DOES VERY LIKELY 
NOT EXACTLY REPRODUCE THE RESULTS FROM THE SOFTWARE OF 
DAVID EBERLY. THIS SOFTWARE MAY BE BASED ON DIFFERENT DATA TYPES
WITH DIFFERENT NUMERICAL PRECISIONS AND FOR FURTHER USAGE OF THIS
SOFTWARE, ONE SHOULD PAY ATTENTION TO THIS.**


