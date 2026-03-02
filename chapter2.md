Chapter 2: Signal and System Foundations for Medical Imaging

2.1 Introduction

Mathematical functions are fundamental tools used to describe and analyze systems in bioimaging and biomedical signal processing. Imaging modalities such as magnetic resonance imaging (MRI), ultrasound, and optical imaging rely on mathematical models to relate physical inputs to measurable outputs. By representing these relationships using functions, complex biological and physical processes can be systematically analyzed and optimized.
In bioimaging, signals and images are often interpreted as functions of time, space, or frequency. Understanding how these functions behave allows engineers and scientists to design imaging systems that accurately capture biological information. This chapter introduces the core concepts of functions and mapping, followed by an exploration of linear and sinusoidal functions, which are widely used in bioimaging and signal processing applications.

2.2 Functions and System Definitions

A function is a mathematical relationship that assigns exactly one output value to each input value. This concept is especially important when describing systems that transform an input signal into an output signal. In bioimaging, systems can include physical devices, biological tissues, or computational algorithms that operate on data.
A system can be modeled mathematically as a function that processes an input to produce an output. For example, an optical imaging system maps reflected light intensity from tissue to a digital image, while an MRI system converts electromagnetic signals into spatial information. Representing these systems as functions allows their behavior to be predicted, analyzed, and improved using mathematical techniques.

2.3 Domain, Range, and Mapping

The domain of a function is the set of all input values for which the function is defined. In bioimaging applications, the domain may represent time intervals, spatial coordinates, or frequency ranges over which measurements are taken. Ensuring that inputs remain within the domain is critical for accurate and stable system performance.
The range of a function consists of all possible output values produced when the function is applied to the domain. In imaging systems, the range may correspond to signal amplitudes, pixel intensities, or voltage levels. Understanding the range helps prevent issues such as saturation, clipping, or loss of information in measurement systems.
A mapping describes how each element of the domain is associated with an element of the range. In bioimaging systems, this mapping defines how physical quantities such as tissue properties or electromagnetic signals are converted into measurable data. A valid function ensures that each input maps to a single output, preserving consistency and interpretability in system design.

2.4 Linear Functions

A linear function is a function in which the output changes proportionally with the input. It is commonly expressed in the form 𝑓(𝑥) = 𝑚𝑥+𝑏f(x) = mx+b, where the slope determines the rate of change and the intercept defines the output when the input is zero. Linear functions are among the simplest mathematical models used in engineering and science.
In bioimaging systems, linear functions are frequently used to model sensor responses and signal amplification. For example, an increase in light intensity detected by a photodetector may produce a proportional increase in electrical voltage within a linear operating range. Linear models are particularly useful because they allow for straightforward analysis and interpretation of system behavior.
Many imaging systems are designed to operate in a region where their response is approximately linear. This assumption enables the use of linear system theory, including superposition and scaling, which greatly simplifies signal processing and image reconstruction. Although real systems may exhibit nonlinear behavior, linear approximations remain a powerful and widely used tool.
