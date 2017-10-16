#### MLS - IBM 

[ **Cartesian - Inflow - Outflow** ] [ **mlsibm_if** ] [[github](https://github.com/nadnaps/mlsibm_if)]:

- Cartesian box with inflow-outflow boundary conditions and no-slip / free-slip walls. 
- Parallelised in the streamwise direction.
- Provision for multiple deformable bodies interacting with each other.
- *[to test] Fadlun forcing*

[ **Cartesian - Doubly Periodic** ] [ **mlsibm_cart** ] [[github](https://github.com/nadnaps/mlsibm_cart)]: 

- Cartesian box, doubly periodic in two directions with no-slip / free-slip walls in the third direction. 
- Parallelised in the wall-normal direction.
- Provision for multiple deformable bodies interacting with each other and can also move in periodic directions.
- *[to test] periodicity for immersed bodies (almost done)
- *[to test] Fadlun forcing*

[ **Cartesian - HIT** ] [ **mlsibm_hit** ] [[github](https://github.com/nadnaps/mls_hit)]:

- Triply periodic box with homogeneous isotropic forcing in the fluid phase. 
- Multiple deforming bodies interacting with each other. 
- *[to add] Fadlun forcing*

[ **Cartesian - Scalar Transport** ] [ **mls_ddc** ]:

- Cartesian box, doubly periodic in two directions with no-slip / free-slip walls in the third direction.
- Scalar transport on a refined grid (multiple resolution strategy)
- For heat and mass transfer with immersed bodies

[ **Cylindrical - Taylor Couette** ] [ **mlsibm_tc** ]: 

- Cylindrical system with independently rotating cylinders (Taylor-Couette flow).
- Multiple deformable bodies interacting with each other. 

[ **Cartesian - Inflow - Outflow** ] [ **mlsibm_if_mulbod** ] [ *to be tested* ] :

- Cartesian box with inflow-outflow boundary conditions and no-slip / free-slip walls. 
- Parallelised in the streamwise direction.
- Provision for multiple deformable bodies interacting with each other.
- Provision for bodies with different resolutions. 
- *[to add] Fadlun forcing*

