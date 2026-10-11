# Physics-I Mid-Semester Examination Questions

## North Western University, Khulna

### Department of Computer Science and Engineering

**Examination:** Mid-Semester Examination, Spring–2025  
**Program:** 4 Year B.Sc. in Computer Science and Engineering (HSC Intake)  
**Semester:** 1st Year, 1st Semester  
**Course Title:** Physics-I  
**Course Code:** Phy-1133  
**Time:** 45 Minutes  
**Marks:** 20

**Instructions:** Answer any **Two (02)** questions from the following questions. Figures in the right margin indicate full marks.

### Q1

**a)** How does light travel through space? **[04]**

**b)** Write down the physical significance of Maxwell’s equations. **[06]**

### Q2

**a)** What are the conditions for interference? **[02]**

**b)** The fringe width doesn’t depend on the fringe number—prove. **[05]**

**c)** Newton’s rings are observed in reflected light of wavelength \(5.9 \times 10^{-5}\) cm. The diameter of the 10th ring is 0.5 cm. Find the radius of curvature. **[03]**

### Q3

**a)** How is an interference pattern obtained in a Fresnel biprism? **[05]**

**b)** Find an expression for the wavelength of monochromatic light by Newton’s rings. **[05]**

---

## North Western University, Khulna

### Department of Computer Science and Engineering

**Examination:** Mid-Semester Examination, Spring–2026  
**Program:** 4 Year B.Sc. in Computer Science and Engineering (HSC Intake)  
**Semester:** 1st Year, 1st Semester  
**Course Title:** Physics-I  
**Course Code:** Phy-1133  
**Time:** 45 Minutes  
**Marks:** 20

**Instructions:** Answer any **Two (02)** questions from the following questions. Figures in the right margin indicate full marks.

### Q1

**a)** Write down the significance of Maxwell’s equations. **[04]**

**b)** Find the expression for true path difference due to reflected light. **[06]**

### Q2

**a)** Write down the conditions of interference. **[02]**

**b)** Find an expression for finding refractive index by Newton’s rings. **[05]**

**c)** Newton’s rings are observed in reflected light of wavelength \(5.9 \times 10^{-5}\) cm. The diameter of the 10th ring is 0.5 cm. Find the radius of curvature. **[03]**

### Q3

**a)** Differentiate between the types of diffraction. **[03]**

**b)** The superposition of linearly polarized waves at right angles leads to an ellipse—prove. **[07]**

---

# Answers

## Spring–2025 Examination

### Q1(a) How does light travel through space? **[04]**

Light travels through space in the form of **electromagnetic waves**. It does not require any material medium, so it can propagate through a vacuum.

An electromagnetic light wave consists of two mutually perpendicular oscillating fields:

- an electric field \(\vec{E}\), and
- a magnetic field \(\vec{B}\).

Both fields are perpendicular to the direction of propagation and are also perpendicular to each other. The electric and magnetic fields vary simultaneously and sustain each other as the wave travels through space.

In vacuum, light travels with the speed

\[
c = \frac{1}{\sqrt{\mu_0\varepsilon_0}} \approx 3 \times 10^8\ \text{m s}^{-1},
\]

where \(\mu_0\) is the permeability and \(\varepsilon_0\) is the permittivity of free space.

### Diagram

```text
                         Electric field, E
                              ↑
                              │
                              │
                              │
                              └──────────────→ Direction of propagation
                             /
                            /
                           ⊙  Magnetic field, B
                         (perpendicular to the page)
```

Therefore, light travels through space as a **transverse electromagnetic wave**, with \(\vec{E}\), \(\vec{B}\), and the direction of propagation mutually perpendicular to one another.

### Q1(b) Write down the physical significance of Maxwell’s equations. **[06]**

Maxwell’s equations describe the fundamental relationships between electric fields, magnetic fields, electric charge, and electric current. In differential form, they are:

1. **Gauss’s law for electricity**
   \[
   \nabla\cdot\vec E=\frac{\rho}{\varepsilon_0}
   \]
   Electric charge is the source or sink of electric fields. The electric flux through a closed surface equals the enclosed charge divided by \(\varepsilon_0\).

2. **Gauss’s law for magnetism**
   \[
   \nabla\cdot\vec B=0
   \]
   There are no isolated magnetic monopoles; magnetic field lines form closed loops, so the net magnetic flux through a closed surface is zero.

3. **Faraday’s law of electromagnetic induction**
   \[
   \nabla\times\vec E=-\frac{\partial\vec B}{\partial t}
   \]
   A changing magnetic field produces a circulating electric field. This is the principle behind electromagnetic induction.

4. **Ampère–Maxwell law**
   \[
   \nabla\times\vec B=\mu_0\vec J+\mu_0\varepsilon_0\frac{\partial\vec E}{\partial t}
   \]
   Magnetic fields are produced by electric current and by a changing electric field (the displacement-current term).

Together, these laws predict electromagnetic waves. In a vacuum their speed is
\[
c=\frac{1}{\sqrt{\mu_0\varepsilon_0}},
\]
which is the speed of light. Thus, Maxwell’s equations unify electricity, magnetism, and optics and show that light is an electromagnetic wave.

### Q2(a) What are the conditions for interference? **[02]**

For a clear, steady interference pattern:

1. The two waves must be **coherent**—they have the same frequency (or wavelength) and a constant phase difference.
2. They should have the same state of polarization and comparable amplitudes for good fringe visibility.
3. The waves must overlap in the observation region. In practice, they are usually derived from the same source to maintain coherence.

### Q2(b) Prove that fringe width does not depend on fringe number. **[05]**

In Young’s double-slit experiment, let the slit separation be \(d\), the screen distance be \(D\), and the wavelength be \(\lambda\), with \(D\gg d\). At a point a distance \(y\) from the central axis, the path difference is approximately
\[
\Delta=d\sin\theta\simeq d\frac{y}{D}.
\]

For a bright fringe of order \(m\), \(\Delta=m\lambda\). Therefore its position is
\[
y_m=\frac{m\lambda D}{d}.
\]
The next bright fringe is at
\[
y_{m+1}=\frac{(m+1)\lambda D}{d}.
\]
Hence the fringe width (separation of consecutive bright fringes) is
\[
\beta=y_{m+1}-y_m
=\frac{(m+1)\lambda D}{d}-\frac{m\lambda D}{d}
=\boxed{\frac{\lambda D}{d}}.
\]
The fringe order \(m\) cancels. Thus fringe width is the same for every pair of consecutive fringes and does **not** depend on fringe number.

### Q2(c) Newton’s rings: find the radius of curvature. **[03]**

Given \(\lambda=5.9\times10^{-5}\) cm, ring order \(m=10\), and diameter \(D_{10}=0.5\) cm. For the \(m\)-th dark ring in reflected light,
\[
D_m^2=4m\lambda R,
\]
where \(R\) is the radius of curvature. Therefore,
\[
R=\frac{D_{10}^2}{4m\lambda}
=\frac{(0.5)^2}{4(10)(5.9\times10^{-5})}\text{ cm}
\approx 105.9\text{ cm}.
\]
\[
\boxed{R\approx 106\text{ cm}=1.06\text{ m}}
\]

### Q3(a) How is an interference pattern obtained in a Fresnel biprism? **[05]**

A Fresnel biprism consists of two thin prisms joined at their bases. A narrow slit \(S\), illuminated by monochromatic light, is placed in front of it. Refraction through the two halves forms two virtual images, \(S_1\) and \(S_2\), of the same slit.

Because \(S_1\) and \(S_2\) originate from the same slit, they are coherent sources. Their refracted beams overlap on a screen. At points where the waves arrive in phase they produce bright fringes; where they arrive in opposite phase they produce dark fringes. The result is a set of approximately straight, equally spaced fringes parallel to the slit.

```text
                         Fresnel biprism                 Screen
S (slit)  ────────────────   /\   ─────────────────────── │
                             /  \       overlapping beams │  bright/dark
                            /____\                         │  fringes
                         S₁ ·    · S₂                     │
                       virtual coherent sources           │
```

The fringe width is \(\beta=\lambda D/d\), where \(d\) is the separation of the virtual sources and \(D\) is their distance from the screen.

### Q3(b) Derive an expression for the wavelength using Newton’s rings. **[05]**

Newton’s rings are formed by interference between light reflected from the upper and lower surfaces of the thin air film between a plano-convex lens and a glass plate. For normally incident monochromatic light, one reflected ray undergoes a phase reversal of \(\pi\), so the centre is dark.

Let \(R\) be the lens radius of curvature and \(t\) the air-film thickness at radius \(r\). From the geometry of the lens,
\[
r^2=2Rt-t^2\simeq2Rt \qquad (t\ll R),
\]
so \(t\simeq r^2/(2R)\). The condition for the \(m\)-th dark ring in reflected light is
\[
2t=m\lambda.
\]
Substituting for \(t\),
\[
\frac{r_m^2}{R}=m\lambda
\quad\Longrightarrow\quad
r_m^2=m\lambda R.
\]
Since the ring diameter \(D_m=2r_m\),
\[
D_m^2=4m\lambda R.
\]
For two dark rings of orders \(m\) and \(m+p\), subtracting their equations gives
\[
D_{m+p}^2-D_m^2=4p\lambda R.
\]
Therefore, the wavelength is
\[
\boxed{\lambda=\frac{D_{m+p}^2-D_m^2}{4pR}}.
\]
For consecutive rings, \(p=1\), so \(\lambda=(D_{m+1}^2-D_m^2)/(4R)\).

---

## Spring–2026 Examination

### Q1(a) Write down the significance of Maxwell’s equations. **[04]**

Maxwell’s equations summarize how electric and magnetic fields are produced and how they change:

| Equation | Physical significance |
|---|---|
| \(\nabla\cdot\vec E=\rho/\varepsilon_0\) | Electric charges produce electric fields (Gauss’s law). |
| \(\nabla\cdot\vec B=0\) | No magnetic monopoles have been observed; magnetic field lines are closed. |
| \(\nabla\times\vec E=-\partial\vec B/\partial t\) | A changing magnetic field induces an electric field (Faraday’s law). |
| \(\nabla\times\vec B=\mu_0\vec J+\mu_0\varepsilon_0\partial\vec E/\partial t\) | Current and changing electric fields produce magnetic fields (Ampère–Maxwell law). |

The equations predict electromagnetic waves travelling in vacuum at \(c=1/\sqrt{\mu_0\varepsilon_0}\). This value equals the speed of light, establishing that light is an electromagnetic wave and unifying electricity, magnetism, and optics.

### Q1(b) Find the expression for true path difference due to reflected light. **[06]**

Consider two rays reflected from the upper and lower surfaces of a thin film of thickness \(t\) and refractive index \(\mu\). Let the angle of refraction inside the film be \(r\). The geometrical extra optical path of the ray travelling inside the film is \(2\mu t\cos r\). Accounting for the lateral separation of the rays in the wavefront construction subtracts \(2\mu t\sin r\sin i\), where \(i\) is the angle of incidence. By Snell’s law, \(\sin i=\mu\sin r\). Thus the optical path difference is
\[
\Delta_{\rm opt}=2\mu t\cos r-2\mu t\sin r\sin i
=2\mu t(\cos r-\mu\sin^2r).
\]
Using \(\mu\sin r=\sin i\) and simplifying,
\[
\boxed{\Delta_{\rm opt}=2\mu t\cos r}.
\]

At a boundary from a rarer to a denser medium, the reflected wave undergoes a phase change of \(\pi\), equivalent to an additional path difference of \(\lambda/2\). Therefore, when exactly one of the two reflected rays has this phase reversal, the **effective phase-equivalent path difference** is
\[
\boxed{\Delta_{\rm eff}=2\mu t\cos r+\frac{\lambda}{2}}.
\]
Consequently, for one phase reversal, reflected-light conditions are: dark \(2\mu t\cos r=m\lambda\), bright \(2\mu t\cos r=(m+\tfrac12)\lambda\), for integer \(m\). At normal incidence, \(r=0\), so the geometrical optical path difference is \(2\mu t\).

### Q2(a) Write down the conditions of interference. **[02]**

1. The sources must be coherent, with the same frequency (wavelength) and a constant phase difference.
2. The waves must overlap and have the same polarization; comparable amplitudes give clearly visible fringes.

### Q2(b) Find an expression for determining refractive index by Newton’s rings. **[05]**

A plano-convex lens of radius of curvature \(R\) on a transparent liquid film produces Newton’s rings in reflected light. Let the liquid’s refractive index be \(\mu\), and let \(D_m\) be the diameter of its \(m\)-th dark ring. The film thickness at radius \(r_m\) is approximately \(t=r_m^2/(2R)\). For a dark ring,
\[
2\mu t=m\lambda.
\]
Since \(D_m=2r_m\), this gives
\[
D_m^2=\frac{4m\lambda R}{\mu}.
\]
If the same ring order is measured first with air (diameter \(D_{m,\rm air}\)) and then with the liquid (diameter \(D_{m,\rm liquid}\)),
\[
D_{m,\rm air}^2=4m\lambda R,
\qquad
D_{m,\rm liquid}^2=\frac{4m\lambda R}{\mu}.
\]
Dividing,
\[
\boxed{\mu=\frac{D_{m,\rm air}^2}{D_{m,\rm liquid}^2}}.
\]
Using two rings to reduce measurement error, the equivalent practical formula is
\[
\boxed{\mu=\frac{D_{m+p,\rm air}^2-D_{m,\rm air}^2}
{D_{m+p,\rm liquid}^2-D_{m,\rm liquid}^2}}.
\]

### Q2(c) Newton’s rings: find the radius of curvature. **[03]**

Given \(\lambda=5.9\times10^{-5}\) cm, \(m=10\), and \(D_{10}=0.5\) cm. For the \(m\)-th dark ring in reflected light,
\[
D_m^2=4m\lambda R.
\]
Thus,
\[
R=\frac{D_{10}^2}{4m\lambda}
=\frac{(0.5)^2}{4(10)(5.9\times10^{-5})}\text{ cm}
\approx105.9\text{ cm}.
\]
\[
\boxed{R\approx106\text{ cm}=1.06\text{ m}}
\]

### Q3(a) Differentiate between the types of diffraction. **[03]**

Diffraction is commonly classified into two types:

| Fresnel diffraction (near-field) | Fraunhofer diffraction (far-field) |
|---|---|
| Source and screen are at finite distances from the aperture or obstacle. | Source and screen are effectively at infinite distances; lenses are often used to produce this condition. |
| Incident wavefronts are curved. | Incident wavefronts are approximately plane. |
| The diffraction pattern changes with the distance between the aperture and screen. | The pattern is observed in the focal plane and is substantially independent of distance when the arrangement is fixed. |

### Q3(b) Prove that two perpendicular linearly polarized waves can produce an ellipse. **[07]**

Let two harmonic waves of the same frequency and travelling in the same direction have mutually perpendicular electric-field components:
\[
E_x=a\cos\omega t,
\qquad
E_y=b\cos(\omega t+\delta),
\]
where \(a\) and \(b\) are their amplitudes and \(\delta\) is their phase difference. Write \(X=E_x/a\) and \(Y=E_y/b\). Then
\[
X=\cos\omega t,
\qquad
Y=\cos\omega t\cos\delta-\sin\omega t\sin\delta.
\]
Rearranging the second equation and using \(\sin^2\omega t+\cos^2\omega t=1\), we obtain
\[
\boxed{\frac{E_x^2}{a^2}+\frac{E_y^2}{b^2}
-\frac{2E_xE_y}{ab}\cos\delta=\sin^2\delta}.
\]
This is the general equation of an ellipse in the \((E_x,E_y)\) plane. Therefore the tip of the resultant electric-field vector traces an ellipse, so the wave is elliptically polarized.

```text
                         Eᵧ
                          ↑
                    .-----|-----.
                 .-'      |      `-.
               .'         |         `.
              /           |           \
             |            •────────────→ Eₓ
              \                       /
               `.                   .'
                 `-.             .-'
                    `-----------'
                 Resultant E traces an ellipse
```

Special cases:

- If \(\delta=0\) or \(\pi\), the components are in phase or opposite in phase, and the resultant is linearly polarized.
- If \(\delta=\pm\pi/2\) and \(a=b\), the ellipse becomes a circle (circular polarization).
- For other phase differences and/or unequal amplitudes, the resultant is generally elliptically polarized.
