Chapter 1: Introduction to Medical Imaging

1.1 What Is Medical Imaging?

Medical imaging is the science and technology of visualizing the internal structures and functions of the human body for the purposes of diagnosis, treatment planning, and biomedical research. By enabling clinicians to observe anatomy and physiological processes noninvasively or minimally invasively, medical imaging has become an essential component of modern healthcare. Imaging techniques reduce reliance on exploratory surgery and allow for earlier detection and more precise treatment of disease.

Beyond clinical practice, medical imaging plays a critical role in biomedical research and technological development. Imaging tools allow researchers to study biological processes in vivo, evaluate new therapies, and improve understanding of disease mechanisms. Advances in imaging have been driven by progress in physics, engineering, and computer science, making the field highly interdisciplinary.

At its core, medical imaging can be understood as a process that transforms physical signals from the human body into visual representations that can be interpreted by humans or computers. To analyze and design imaging systems rigorously, it is necessary to introduce the concept of a system and the mathematical framework used to describe system behavior.

1.2 Goals of Medical Imaging
In engineering and signal processing, a system is defined as an entity that transforms an input into an output according to a specific rule or set of rules. The input may be a signal, image, or physical quantity, while the output represents the system’s response to that input. Systems may be physical devices, computational algorithms, or mathematical models.

In medical imaging, the imaging chain itself can be viewed as a system. For example, the patient anatomy serves as the input, while the acquired image is the output. Between these two stages lie multiple components, including signal generation, detection, amplification, processing, and reconstruction. Each of these components can be modeled as an individual system, or together as a composite system.

Understanding imaging systems as mathematical systems allows engineers and scientists to predict system behavior, optimize image quality, and analyze limitations such as noise and resolution. This system-based perspective forms the foundation for much of medical imaging theory and practice.

1.3 Overview of Major Imaging Modalities
A system is said to be linear if it satisfies specific mathematical properties that allow for simplified analysis and prediction of its output. Linear systems are particularly important in medical imaging because many imaging processes can be approximated as linear over a useful range of operating conditions. This approximation enables the use of powerful analytical tools such as convolution and Fourier analysis, which will be introduced in later chapters.

Linear systems are attractive because they allow complex inputs to be decomposed into simpler components. By analyzing the system’s response to these components individually, the overall system behavior can be reconstructed efficiently. Although real imaging systems are not perfectly linear, linear models often provide accurate and practical representations.

In imaging, linear system assumptions are commonly used when modeling blur, spatial resolution, and signal propagation. For example, the formation of an X-ray image can often be approximated as a linear process relating the object attenuation to the measured detector signal.

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
