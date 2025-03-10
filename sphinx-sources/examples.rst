Examples.
=========

Interference examples.
**********************

When two or more waves overlap each other in space a more or less complicated pattern of fringes can be observed on a screen placed in the overlap area. These fringes are the result of superposition of the fields, which cause local enhancement or decrement of the intensity depending on the phase and amplitude distribution of the waves in the observation regio.
In this chapter we will demonstrate a number of interference examples.

.. toctree::
   :maxdepth: 1
   
   YoungsExperiment
   MichelsonInterferometer
   MultiHoleAndSlit
   InterferenceDoughnutCollinear
   InterferenceDoughnutTilted
   
Diffraction examples.
*********************

.. toctree::
   :maxdepth: 1
   
   DiffractionRoundHole
   PoissonSpot
   FresnelZonePlate
   
.. Index::
     Airy beam; 1D; 2D
     Bessel beam
     Poisson spot
     Arago spot
     Annular slit
     Axicon
     CircularScreen
     CircularAperture
     Begin
     Forvard
     Fresnel
     Intensity

Non-diffracting Airy beams.
***************************

An Airy beam will propagate without diffraction and keeps its shape 
during long propagation distances. That makes it interesting for a 
large number of applications.
A special feature of the Airy beam is that it accellerates in the 
transverse direction by its self, although the center of 
gravity propagates as a straight line as it should be.
From LightPipes for Python version 2.1.4. there are two new commands which 
substitude an Airy beam into the field. A one- and a two-dimensional 
Airy beam: :func:`~LightPipes.AiryBeam1D` and :func:`~LightPipes.AiryBeam2D`
For further reading we recommend the 
`open access review article <https://www.mdpi.com/2076-3417/7/4/341/htm>`_ by Yiqi Zhang et al. [#a1]_

Below we demonstrate how an Airy beam can be generated using a Gaussian 
laser beam, a spatial light modulator (SLM) and a Fourier transform 
with a postive lens. The SLM substitutes a cubic phase into the field.
A non-diffracting 2D Airy beam will exist along a long distance from 
the focus of the lens.

.. toctree::
   :maxdepth: 1
   
   2DAiryBeam

.. rubric:: References:

.. [#a1] Yiqi Zhang, Hua Zhong, Milivoj R., Belić and Yanpeng Zhang, Appl. Sci. 2017, 7(4), 341; https://doi.org/10.3390/app7040341

Non-diffractive Bessel beam.
****************************

A Bessel beam has the interesting property that it does not diffract and that it keeps its shape
over large distances. Several meters, depending on parameters, can be realized. Applications of Bessel beams
take advantage of the very large size of the focus, which cannot be obtained using lenses or mirrors.
For example generation of a long narrow plasma channel can be realized using a high-power
laser beam converted into a Bessel beam by an axicon lens.
 
Besides an axicon, a combination of an annular slit and a positive lens or concave mirror can be used in stead [#b1]_.
In the following example a Poisson spot is generated by illuminating a circular disk by a plane mono-chromatic beam.
The disk is positioned in the primary focus of a positive lens so that the waves originating from the edge of teh disk will be collimated.
By blocking the rest of the incoming beam only the edge waves remain which results in a 
non-diffracting Bessel beam.

.. rubric:: Reference:

.. [#b1] J.Durnin, "Exact solutions for nondiffracting beams. I. The scalar theory.", JOSA A, Vol. 4, Issue 4, pp. 651-654 (1987)

.. toctree::
   :maxdepth: 1
   
   PoissonSpottoBesselBeam
   BesselBeamWithAxicon

.. Index::
     laser
     stable laser resonator
     unstable laser resonator
     resonator
     Gauss mode
     Hermite Gauss mode
     Laguerre Gauss mode
     doughnut mode
     Begin
     Forvard
     Gain
     Lens
     Intensity
     
Laser examples.
***************

.. toctree::
   :maxdepth: 2
   
   HermiteGaussModes
   LaguerreGaussModes
   DoughnutModes
   StableLaserResonator
   UnstableLaserResonator
   TransformationtoDoughnutMode
   LaserModeTransformer
   resonator_geometric_optics
   
.. Index::
     phase recovery
     Begin
     Forvard
     Interpol
     SubIntensity
     Phase
     PhaseUnwrap
     Intensity

Phase recovery.
***************

.. toctree::
   :maxdepth: 1
   
   PhaseRecoveryGerchbergSaxton

.. Index::
    Zernike aberration
    Zernike

Zernike aberration.
*******************

Any aberration in a circle can be decomposed over a sum of Zernike 
polynomials. The Zernike command accepts four arguments:
1. The radial order n  2. The 
azimuthal order m. 3. The radius, R 4. The 
amplitude of the aberration.



.. toctree::
   :maxdepth: 1
   
   ZernikeAberrations
   RadialShearInterferometer
   ShackHartmannSensor
   
.. Index::
    Graded index media GRIN
    GRIN lens
    Lenslike medium
    
Graded index media GRIN.
************************

.. toctree::
   :maxdepth: 1
   
   GRINDemo
   GRINYoung
   PropagationLensLikeMedium

.. Index::
   Fourier optics
   Pattern recognition
    
Fourier optics.
***************

.. toctree::
   :maxdepth: 1
   
   PatternRecognition

