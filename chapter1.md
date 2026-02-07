Chapter 1: Introduction to Medical Imaging

1.1 What Is Medical Imaging?

Medical imaging is the science and technology of visualizing the internal structures and functions of the human body for clinical diagnosis, treatment planning, and biomedical research. Rather than relying solely on physical examination or invasive procedures, medical imaging allows clinicians to observe anatomy and physiological processes in a noninvasive or minimally invasive manner.

Medical imaging plays a central role in modern healthcare. It supports early disease detection, guides surgical and interventional procedures, and enables longitudinal monitoring of disease progression and treatment response. Beyond clinical practice, imaging technologies are also essential tools in biomedical research, enabling the study of biological structures and processes in vivo.

1.2 Goals of Medical Imaging
The primary goals of medical imaging include:

Visualization of anatomy: Identifying the size, shape, and structure of organs and tissues

Functional assessment: Measuring physiological processes such as blood flow, metabolism, or neural activity

Disease detection and diagnosis: Identifying abnormalities such as tumors, fractures, or lesions

Treatment guidance: Assisting in surgical planning and image-guided interventions

Monitoring and follow-up: Tracking disease progression or treatment effectiveness over time

Different imaging modalities emphasize different goals, leading to trade-offs in spatial resolution, contrast, acquisition speed, patient safety, and cost.

1.3 Overview of Major Imaging Modalities
Medical imaging encompasses a wide range of technologies, including:

X-ray Imaging and Computed Tomography (CT)

X-ray imaging uses ionizing radiation to generate projection images of internal structures, particularly useful for visualizing bones and dense tissues. Computed Tomography (CT) extends this principle by acquiring multiple projections and reconstructing cross-sectional images with high spatial resolution.

Magnetic Resonance Imaging (MRI)

MRI uses strong magnetic fields and radiofrequency pulses to produce images with excellent soft-tissue contrast. It is especially valuable for imaging the brain, spinal cord, muscles, and internal organs without exposing patients to ionizing radiation.

Ultrasound Imaging

Ultrasound uses high-frequency sound waves to generate real-time images. It is widely used due to its safety, portability, and low cost, particularly in obstetrics, cardiology, and point-of-care diagnostics.

Nuclear Medicine Imaging (PET and SPECT)

Positron Emission Tomography (PET) and Single Photon Emission Computed Tomography (SPECT) use radioactive tracers to image metabolic and functional processes. These modalities are commonly used in oncology, neurology, and cardiology.

Optical and Microscopic Imaging

Optical imaging techniques, such as fluorescence microscopy and optical coherence tomography, are widely used in biomedical research and selected clinical applications, including ophthalmology.

1.4 Medical Imaging as an Interdisciplinary Field
Medical imaging is inherently interdisciplinary, combining principles from:

Physics: radiation, electromagnetism, acoustics

Engineering: signal processing, instrumentation, image reconstruction

Computer Science: image analysis, machine learning, artificial intelligence

Biology and Medicine: anatomy, physiology, pathology

Advances in imaging technology often arise from collaboration across these disciplines.

1.5 From Imaging Systems to Mathematical Systems
While medical imaging technologies may appear diverse, they share a common underlying structure: each imaging modality can be modeled as a system that transforms an input (such as an object or physical signal) into an output (such as a measured signal or reconstructed image).

To analyze, design, and improve imaging systems, we rely on mathematical system theory. In the remainder of this chapter, we introduce the concept of systems—particularly linear and shift-invariant linear systems—which form the foundation for signal processing and imaging analysis.

1.6 Definition of a System
A system is a process or operator that maps an input signal y: y=S{x}

In medical imaging, systems can represent physical devices, data acquisition processes, reconstruction algorithms, or digital filters.

1.7 Linear Systems
A system is linear if it satisfies the principle of superposition, which allows complex inputs to be analyzed as combinations of simpler inputs.

Mathematically, a system 
𝑆
S is linear if for any signals x1​ and x2, and constant a and b:
S{ax1 + bx2} = aS{x1} + bS{x2}

Linearity is a key assumption in signal processing and medical imaging because it enables the use of powerful analytical tools such as convolution and Fourier analysis.

1.8 Additivity and Homogeneity

The principle of superposition consists of two conditions:

Additivity
S{x1 + x2}=S{x1} + S{x2}
Homogeneity(scaling)
S{ax} = aS{x}

A system is linear if and only if it satisfies both additivity and homogeneity.

1.9 Nonlinear Systems

A system that does not satisfy additivity or homogeneity is nonlinear. Examples include systems involving squaring, thresholding, saturation, or magnitude-dependent behavior.

Although many real-world imaging systems exhibit nonlinear effects, linear models are often used as accurate approximations for analysis and design.

1.10 Shift-Invariant Linear Systems

A system is shift-invariant if a shift in the input signal produces an identical shift in the output: S{x(t-t0)}=y(t-t0)

Systems that are both linear and shift-invariant (LSI) play a central role in signal processing. These systems can be fully characterized by their response to simple inputs, leading directly to the concept of convolution, which will be introduced in the next chapter.

1.11 Chapter Summary

This chapter introduced the field of medical imaging and its interdisciplinary nature, then established the mathematical foundation of systems, with emphasis on linear and shift-invariant linear systems. These concepts provide the basis for understanding convolution, Fourier analysis, signal processing, and image quality in subsequent chapters.
