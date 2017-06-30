# Lesson10:
*Dan Cojoc*

### Optical microscopy and tweezers

The optical microscopy is the most used in life science.
It's the only way to look into a cell with minimally invasive tecniques.

*inverted microscopy image with short optics ideas*

$$ \Phi = \frac{1}{\mathcal{f} [m]}$$

the powers of the lens is inversely to the focal lens, the focal lens decreases with curvature.

The advantage of `infinite optical length` system is the aberration correction, the numerical aperture can be bigger.

#### Numerical aperture
it's important to have good resolution.
$$ NA = n \sin{\alpha} $$
where $n$ is the refractive index.
Na reflects te capacity to collect light and resolv details of a sample positioned at fixed distance.
The *Airy disk* is sharper with highrer $NA$
This deformation is due to the finite size of instrumentation.
The resolution is proportial to the diameter of the mirror.
[](http://spiff.rit.edu/classes/phys213/lectures/diffr/diffr_long.html)
with Abbe or Rayleigh resolution criterium.

**Depth of Field** defines the axial resolution.

#### Contrast

$$ Contrast = \frac{I_{max} - I_{min}}{I_{min}+I_{max}} $$

Bright field is not suited to see cells.
Usually the decetors measure the intensity of light, not the phase, barely the polarization.
The phase detector doesn't exist and the best/only way is through interference.

##### Phase Contrast method
by Frits Zernike.

The cell has an average a different refractive index respect to the medium, then the optical path will be different, as the phase  $ \frac{2\pi}{\lambda} (n_{sample}- n_{medium}) d = \phi $

**Differenial interference contrast** is used with high NA and high magnification and use polarization and birifrangence.

**Darkfield and Polarized Light**
Use the light scattering to deviate rays which are not direct to the lens!

##### Digital holographic microscopy.
**Holography** is the ability of create 3D images using the phase shift.

Captures both amplitude and phase information using a second reference wave.
The collector is a digital camera which measures the intensity.
Some tricks let you separate phase from intensit information, not always! (reference light tilt in example)
Fourier transform back-forward let you distinguish the 2 contribution

The phase image is the more interesting, but unwrapping algorithm are needed. This method gives you the thickness of the cell, but actually what we have is the optical path.

Pro cons:
- Measure height profile
- High axial resolution $\sim 10nm$

- Low lateral resolution
- the measure is the optical path.

### Epifluorescence

##### Total internal reflection fluorescence microscopy
Uses the evanescent wave to illuminate only the closest elements of the cell ~ 200 nm

##### Confocal microscopy
Marvin Minsky:
Two pinholes in laser and detector allow to collect only the light coming from the focal  plane and eliminate the noise on the z axes!

### Nanoscopy
Manipulate the state of molecules (On/Off) to resolve it.
Some protein can be swithc on off by light.

**STED** Really nice results are obtained with chemical dyes with metastable properties that can be switched on on a certain frequency and the react in a colorful way to different stimulation lights.

**PALM** Photo activated localization microscopy.
Many cycles of activation-relevation.
The activation light will let particle get visible and be localized, each repetition activate some particle with certain probability

### Optical Manipulation
The use of lasers to trap size in the range from 20nm to 100um: can do things without contact!

#### Optical tweezers:
Up to 6 freedom degrees (not always (asymmetry is required to rotate)!)
Higly focalized laser let you to move the sample, the light has another source.
The basic idea is to transfer energy and momentum to the sample using the light-object intaraction to generate force.
even if the tranferred momentum is little the really little mass of the particle let up to 34g (gravity aceleration)

if the system is dumped a limit velocity is reached, but since $$ m \sim d^3 \\
\gamma_{damping} \sim d$$
second is dominant.

Or reflection or refraction can move the bead
(1986 Observation of single beam gradient force optical trap)
Ashkin did a great work on the laser traps.

##### Optical tweezers can measure forces.
The force field which leads the beads to the focus point acts as a spring in the close region.
Thermal forces are relevant too.
Statistical mechanic allows to describe the stiffness of optical tweezers and then the potential.
like a brownion motion with parabolic potential!
Measuring the displacement let you to know the force, like an AFM



#### Laser scalpels:
Let us to ablate with nano cuts
