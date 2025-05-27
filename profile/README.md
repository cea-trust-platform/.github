# Hi there 👋 and welcome to the __CEA TRUST Platform's organization__ on Github

<font size="8"> This organization consists of several **public git repositories** </font>

## **1. TRUST code**

<font size="8"> 

**TRUST** is a thermalhydraulic software package for CFD simulations. This software was originally designed for conduction, incompressible single-phase, and Low Mach Number (LMN) flows with a robust Weakly-Compressible (WC) multi-species solver. However, a huge effort has been conducted recently, and now TRUST is able to simulate real compressible multi-phase flows. 

TRUST is also being progressively ported to support GPU acceleration (NVidia/AMD).

The software is OpenSource (**[BSD license](https://github.com/cea-trust-platform/trust-code/blob/master/License.txt)**). 

Current TRUST version : **[v1.9.6](https://github.com/cea-trust-platform/trust-code/releases/tag/v1.9.6)** (released in May 2025).

Here are some useful links:

  - **[TRUST Website](https://cea-trust-platform.github.io)**: The official website
  
  - **[TRUST Sources](https://github.com/cea-trust-platform/trust-code)**: You'll find there how to download/install code and get access to documentation (tutorials, ...)
  
  - **[TRUST Documentation](https://cea-trust-platform.readthedocs.io/en/latest/)**: You'll find there the following

    - TRUST Generic Guide (what you should read to start using the code)
    - TRUST Keyword Reference Manual (what you can use in a TRUST dataset)
    - TRUST Tools Documentation (for Jupyter notebooks and stats postprocessing package)
    - TRUST C++ API Documentation
    - TRUST Numerical Methods Documentation

</font>

<p align="right">
<img src="https://github.com/cea-trust-platform/trust-code/blob/master/bin/HTML/logo_trust.gif?raw=true" style="width:9cm;">
</p>


## **2. TrioCFD code**

<font size="8">

**TrioCFD** is the Computational Fluid Dynamics (CFD) code based on the TRUST platform. The code contains Front-Tracking, Radiation, ALE for fluid/structure interactions and Turbulence LES & RANS models.

This software is OpenSource (BSD license). 

Current TrioCFD version : **[v1.9.5](https://github.com/cea-trust-platform/TrioCFD-code/releases/tag/v1.9.5)** (released in December 2024).
  
Here are some useful links:

  - **[TrioCFD Website](https://triocfd.cea.fr)**
  
  - **[TrioCFD Sources](https://github.com/cea-trust-platform/TrioCFD-code)**

  - **[TrioCFD Documentation](https://triocfd-documentation.readthedocs.io/en/latest/)**

</font>

<p align="right">
<img src="https://github.com/cea-trust-platform/.github/blob/main/profile/tcfd.png">
</p>
 
## **3. ICoCo interface**

<font size="8">
  
**ICoCo** stands for Interface for Code Coupling. This is a norm that a code may choose to implement to facilitate its coupling with other ICoCo-compliant codes.

The public ICoCo git repository is available at **[this link](https://github.com/cea-trust-platform/icoco-coupling)**.

</font>

## **4. ICoCo SWIG wrapper for TRUST BALTIKs**

<font size="8">

The public icoco-swig-baltik git repository is available at **[this link](https://github.com/cea-trust-platform/icoco-swig-baltik)**.

This project defines an ICoCo SWIG wrapper that can be used for any BALTIK project based on the TRUST platform.

</font>

## **5. EOS Code**

<font size="8">

**EOS** stands for Equation Of State ! 

This is a public open-source C++ interface useful to call thermo-physical properties libraries (like REFPROP, etc...)

This software is OpenSource (BSD license) and available **[here](https://github.com/cea-trust-platform/EOS_code)**.

</font>

<p align="right">
<img src="https://github.com/cea-trust-platform/.github/blob/main/profile/EOS.png?raw=true" style="width:4cm;">
</p>

## **6. MEDCoupling tutorials**

<font size="8">
  
**MEDCoupling** is a powerful library that can be used to manipulate fields/data within a numerical simulation. Click **[here](https://docs.salome-platform.org/latest/dev/MEDCoupling/developer/index.html)** to visit the documentation.
  
This public repository contains some jupyter python tutorials illustrating various useful applications of MEDCoupling and is available on  **[this link](https://github.com/cea-trust-platform/MEDCoupling_tutos)**.

</font>

## **7. R&D Codes**

<font size="8">
  
  - **Stokes_NCFEM**
  
    Matlab code devoted for order 1 and 2 nonconforming finite elements for Stokes in 2D.
  
    The public git repository is available at **https://github.com/cea-trust-platform/Stokes_NCFEM**
  
  - **FluidDyn** 
  
    Python 1D code for multiphase flow and interface tracking.
  
    The public git repository is available at **https://github.com/cea-trust-platform/FluidDyn**
    
</font>
