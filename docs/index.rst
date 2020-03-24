GEFIT: KSTAR EFIT enhancing toolkit
===================================

GEFIT enhances KSTAR EFIT reconstruction with harnessing the high resolution diagnostics, 
evaluating the external H&CD and re-furbishing the MSE data.

Connection to EFIT and MDS
    If you need to get a detailed equilibrium to analyze plasma physics, 
    GEFIT will get the basic information from diagnostic system such as MDS and
    EFIT(magnetic or MSE-only).

Profile fitting and fast ion calculation
    To build the plasma temperature and density distribution, simulated MSE and fast ion spatial information,
    GEFIT can provide the profile fitting and fast ion pressure and current drive
    using the GFIT tool and NUBEAM wrapper.

GUI-based kinetic EFIT
    From the physics-based information, GEFIT supports GUIs for the entire equilibrium reconstruction
    Users can control the inputs, check the results and optimize it for proper purposes,
    following experimental data as accurately as possible.


Access to use GEFIT
-------------------

You can use GEFIT toolkit in only uKSTAR server now.
If you don't have account, create your iKSTAR account.


Getting started
---------------

Intro

* **Overview of core features**:
  :doc:`features`
* **Getting equilibrium using GUI**:
  :doc:`Run program<execution>`

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Getting started

   features
   execution
   

Advanced features
-----------------

GEFIT offers many advanced features and options.

* **Physics-based profile fitting**:
  :doc:`GFIT<profile-fitting>`
* **Analysis of pedestal stability**:
  :doc:`With EPED predictor<eped-predictor>` |
  :doc:`With PED scanner<ped-scanner>`
* **External H&CD calculation**:
  :doc:

.. toctree::
   :maxdepth: 1
   :hidden:
   :glob:
   :caption: Advanced features

   profile-fitting
   eped-predictor
   ped-scanner

GEFIT interfaces
----------------

GEFIT project
-------------

.. toctree::
   :maxdepth: 2
   :caption: Contents: