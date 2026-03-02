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

2.5 Sinusoidal Functions

Sinusoidal functions describe oscillatory behavior and are characterized by smooth, repeating waveforms. These functions are typically expressed using sine or cosine functions, which include parameters that control amplitude, frequency, and phase. Sinusoidal behavior is commonly observed in natural and engineered systems.

In signal processing, sinusoidal functions are fundamental because they form the building blocks of more complex signals. Many biomedical signals, including electromagnetic waves used in imaging systems, exhibit sinusoidal properties. Techniques such as Fourier analysis rely on the fact that any complex signal can be represented as a combination of sinusoidal components.

In bioimaging applications, sinusoidal functions are used to encode, transmit, and analyze information. For example, MRI systems use oscillating magnetic fields and radiofrequency signals that are inherently sinusoidal. Understanding sinusoidal functions is therefore essential for analyzing frequency content, designing filters, and interpreting imaging data.

2.6 Comparison of Linear and Sinusoidal Functions

Linear and sinusoidal functions serve different but complementary roles in bioimaging and signal processing. Linear functions are primarily used to describe proportional relationships and system responses, while sinusoidal functions are used to model periodic and frequency-based behavior. Both types of functions are essential for a complete understanding of imaging systems.

Linear functions are especially useful in modeling amplification, attenuation, and calibration processes. Sinusoidal functions, on the other hand, are critical for understanding signal modulation, wave propagation, and spectral analysis. Together, these functions provide a mathematical framework for describing how bioimaging systems acquire and process data.

2.7 Taylor Expansion

The Taylor expansion is a mathematical technique used to approximate complex functions using a sum of simpler polynomial terms. Rather than working directly with a complicated function, the Taylor expansion represents the function as a series of terms that are easier to analyze and compute. This approach is especially valuable in engineering and bioimaging, where exact analytical expressions may be difficult or impossible to evaluate.

A Taylor expansion begins at a specific point, often called the expansion point or operating point. The first term in the expansion is a constant equal to the value of the function at that point. This constant term provides a baseline approximation and represents the function’s output when the input is exactly at the expansion point.

The next term in the Taylor expansion is a linear term, which depends on the first derivative of the function evaluated at the same point. This term accounts for how the function changes in response to small variations in the input. In practical systems, this linear term often dominates the behavior near the operating point and forms the basis for linear approximations used in signal processing and system modeling.

Higher-order terms are then added to improve the accuracy of the approximation. The quadratic term depends on the second derivative of the function and captures curvature in the function’s behavior. Additional terms involving higher-order derivatives can be included as needed, allowing the approximation to more closely match the original function over a wider range of inputs.

In bioimaging and biomedical signal processing, Taylor expansions are commonly used to simplify nonlinear system behavior. Small deviations around an operating point can often be analyzed using only the constant and linear terms, resulting in a linearized model. This technique enables efficient analysis of imaging systems, noise behavior, and signal distortions while maintaining sufficient accuracy for practical applications.

2.8 Linear Functions in One and Two Dimensions

Linear functions are among the most important mathematical tools used in engineering and medical imaging because of their simplicity and interpretability. In one dimension, a linear function describes how a single input variable maps to a single output variable, typically in the form f(x) = mx+bf(x) = mx + bf(x) = mx+b. This type of function is commonly used to model relationships such as signal amplitude as a function of time or sensor output as a function of input intensity.

Two-dimensional linear functions extend this concept by mapping inputs from a two-dimensional domain to outputs. In medical imaging, two-dimensional linear relationships often arise when modeling images, which can be represented as functions of spatial coordinates (x,y)(x, y)(x,y). Linear models in two dimensions are frequently used in image formation, filtering, and reconstruction algorithms.

Linear functions are easy to analyze because their behavior is predictable and well understood. They obey principles such as superposition and scaling, which allow complex problems to be broken down into simpler components. Additionally, linear functions are fast to compute, making them especially well suited for real-time imaging applications where large amounts of data must be processed efficiently.

In medical imaging, linear approximations are widely used even when systems are not perfectly linear. Many imaging devices are designed to operate within a range where their response is approximately linear, enabling accurate modeling and reconstruction. This reliance on linear functions forms the mathematical foundation for many imaging techniques, including image filtering, noise reduction, and tomographic reconstruction.

2.9 Systems, Inputs, and Outputs

A system is a process that takes an input, performs some operation, and produces an output. In mathematical terms, a system can be represented as an operator that acts on an input signal or function. This abstraction allows physical devices, biological processes, and computational algorithms to be described using a common mathematical framework.
If v(t)v(t)v(t) represents an input signal and w(t)w(t)w(t) represents an output signal, a system can be written as

w(t) = L(v(t))w(t) = L(v(t))w(t) = L(v(t))

where LLL denotes the system operator. In cases where time dependence is not explicitly emphasized, the system may be written more compactly as w=L(v)w = L(v)w=L(v). This notation highlights that the output is determined entirely by how the system processes the input.

In medical imaging systems, inputs may include electromagnetic signals, acoustic waves, or electrical measurements, while outputs may be digital images or reconstructed signals. The system performs a sequence of physical and computational operations that transform the input into a usable form. Understanding the relationship between inputs and outputs is essential for designing, analyzing, and improving imaging systems.

Mathematics and tomographic scanners are tightly integrated within these systems. Tomographic imaging modalities rely on mathematical models to reconstruct internal structures from external measurements. By treating the scanner as a system and using linear operators to describe its behavior, engineers can develop algorithms that accurately convert raw data into clinically meaningful images.

2.10 Measurement Systems

A measurement system is a system designed to quantify an unknown physical quantity by comparing it to a known reference. The reference provides a standard against which the unknown value can be evaluated, allowing the measurement to be expressed in meaningful units. This comparison process is fundamental to all scientific and engineering measurements.

For example, measuring electrical voltage involves comparing an unknown voltage to a calibrated reference within a voltmeter. Similarly, measuring tissue temperature requires comparing thermal energy emitted by tissue to a known temperature scale. In each case, the accuracy of the measurement depends on the quality of the reference and the reliability of the system performing the comparison.

Measurement systems are essential in biomedical engineering because biological quantities cannot be directly observed in numerical form. Instead, sensors and instruments convert physical or chemical properties into measurable signals. These systems form the foundation upon which imaging systems and diagnostic tools are built.

2.11 Imaging Systems

An imaging system is a specialized type of measurement system that produces a spatial representation of an object or region of interest. Rather than measuring a single value, imaging systems measure variations across space and map them into an image. Each point in the image corresponds to a specific location in the object being measured.

Magnetic resonance imaging (MRI) scanners are a prominent example of imaging systems in medicine. In an ideal imaging system, a single point in the reconstructed image corresponds exactly to a single point in the body. This precise correspondence allows anatomical structures and physiological features to be accurately visualized.

In practice, imaging systems are imperfect, and their limitations affect image quality. A low-quality imaging system may blur features, causing distinct structures to appear smeared or indistinct. This blurring is a characteristic of the system itself and reflects how the system processes and transforms the measured signals. Understanding these system characteristics is essential for interpreting images and improving imaging performance.

2.12 Control Systems

A control system is a type of system that does not stop after producing an output, but instead uses that output as feedback to modify its own behavior. In a control system, the output is continuously monitored and compared to a desired reference or goal. Any difference between the actual output and the desired output is used to adjust the system’s operation.

This feedback mechanism allows control systems to maintain stability and accuracy even in the presence of disturbances or changing conditions. For example, a thermostat-controlled heating system measures the current room temperature and compares it to a set temperature. If the temperature deviates from the desired value, the system automatically adjusts the heating output to correct the difference.

Control systems are widely used in biomedical and engineering applications because they enable precise regulation of complex processes. In medical devices, feedback control can be used to regulate drug delivery, maintain stable physiological conditions, or adjust imaging parameters in real time. The ability to self-correct makes control systems more robust and reliable than open-loop systems.

2.13 Robotic Systems

A robotic system is a specialized type of control system that integrates sensing, computation, and actuation to interact with its environment. In addition to feedback control, robotic systems often incorporate a level of machine intelligence that allows them to make decisions and adapt their behavior. These systems typically maintain a three-dimensional model of the surrounding world, which helps them navigate and perform tasks accurately.

In real-world applications, robotic systems are used in manufacturing, exploration, and healthcare. For example, industrial robots adjust their motion based on sensor feedback to assemble products with high precision. Autonomous vehicles use sensors and control algorithms to adapt to changing road conditions and avoid obstacles.

In medicine, robotic systems are increasingly used alongside medical imaging to guide surgical procedures. Imaging systems provide spatial information about the patient’s anatomy, while the robotic system uses this information to position instruments accurately. By combining imaging data, feedback control, and intelligent decision-making, robotic systems enhance precision, reduce invasiveness, and improve patient outcomes during complex surgical interventions.

2.14 Neurological Systems

The neurological system is a complex biological system responsible for sensing, processing, and responding to information from the environment. Neurons receive input in the form of chemical or electrical signals and transmit electrical impulses that propagate through neural networks. These signals enable essential functions such as perception, movement, cognition, and regulation of internal bodily states.

At the cellular level, neurons act as information-processing units that integrate multiple inputs before generating an output signal. This process closely resembles engineered systems in which inputs are transformed through defined mechanisms to produce outputs. In bioimaging and neuroscience, measuring and visualizing neural activity is critical for understanding how information flows through the nervous system.

The neurological system does not operate in isolation but interacts continuously with other systems in the body. Sensory input, motor output, and internal feedback loops work together to maintain coordinated function. This system-level perspective is essential for studying brain function and neurological disorders.

2.15 The Human Body as an Interconnected System

The human body can be understood as an interconnected system composed of multiple levels of organization. These levels range from genes and cells to tissues, organs, and large-scale systems such as the circulatory, respiratory, and neurological systems. Each level interacts with others, creating a highly integrated and dynamic biological network.

Biomedical engineering and bioimaging focus on studying the body as a collection of interacting components rather than isolated parts. Changes at the molecular or cellular level can propagate upward to affect organ function and overall health. Imaging technologies play a crucial role in visualizing these interactions across scales, allowing researchers and clinicians to observe structure and function simultaneously.

Viewing the human body as a system enables more accurate modeling, diagnosis, and treatment of disease. Systems-based approaches support advances such as personalized medicine, functional imaging, and targeted therapies. This perspective aligns closely with the mathematical and system-theoretic concepts introduced earlier in this chapter.

2.16 Convergence of Human and Robotic Systems

The distinction between human biological systems and artificial engineered systems is becoming increasingly blurred. Advances in technology have enabled direct interactions between the human nervous system and machines, particularly in the fields of brain–machine interfaces and neural prosthetics. These developments allow artificial systems to receive input from, and deliver output to, biological systems.

Emerging fields such as neuro-inspired artificial intelligence and embodied intelligence draw inspiration from how humans sense, learn, and adapt to their environment. In these systems, intelligence is not purely computational but is shaped by interaction with the physical world. This mirrors how human cognition is deeply connected to sensory input, motor control, and feedback.

In biomedical applications, robotic and artificial systems are increasingly integrated with medical imaging and neural data. Examples include brain-controlled prosthetic limbs and image-guided robotic surgery systems. As these technologies continue to develop, understanding both human and artificial systems through a shared systems framework becomes essential for advancing medicine and healthcare.

2.17 Linear Systems

A system is defined as linear if it satisfies two fundamental properties: additivity and homogeneity. These properties describe how the system responds to combinations and scalings of inputs. Linear systems are central to biomedical signal processing and medical imaging because they are mathematically tractable and allow powerful analytical tools to be applied.

Mathematically, if a system is represented by an operator LLL acting on an input signal v(t)v(t)v(t), linearity ensures predictable and consistent behavior. This predictability is essential in imaging systems, where signals are often decomposed, processed, and recombined. Many imaging and reconstruction algorithms are explicitly designed under the assumption of linearity.

An important consequence of linearity is that a linear system must produce zero output when given zero input. If an input signal contains no energy or information, the system cannot generate output on its own. This condition follows directly from the properties of additivity and homogeneity.

2.18 Additivity

Additivity describes how a system responds to the sum of two inputs. A system is additive if the response to a combined input equals the sum of the individual responses. In mathematical terms, this property is expressed as

L(v1(t)+v2(t))=L(v1(t))+L(v2(t)).L(v_1(t) + v_2(t)) = L(v_1(t)) + L(v_2(t)).L(v1​(t)+v2​(t))=L(v1​(t))+L(v2​(t)).

This concept can be illustrated using function notation. If an input function f1(x)f_1(x)f1​(x) is processed by a system HHH to produce an output K1(x)K_1(x)K1​(x), and another input f2(x)f_2(x)f2​(x) produces an output K2(x)K_2(x)K2​(x), then the combined input f1(x)+f2(x)f_1(x) + f_2(x)f1​(x)+f2​(x) must produce the combined output K1(x)+K2(x)K_1(x) + K_2(x)K1​(x)+K2​(x). Symbolically,

f1(x)→H[f1(x)]→K1(x),f_1(x) \rightarrow H[f_1(x)] \rightarrow K_1(x),f1​(x)→H[f1​(x)]→K1​(x), f2(x)→H[f2(x)]→K2(x),f_2(x) \rightarrow H[f_2(x)] \rightarrow K_2(x),f2​(x)→H[f2​(x)]→K2​(x), f1(x)+f2(x)→H[f1(x)+f2(x)]→K1(x)+K2(x).f_1(x) + f_2(x) \rightarrow H[f_1(x) + f_2(x)] \rightarrow K_1(x) + K_2(x).f1​(x)+f2​(x)→H[f1​(x)+f2​(x)]→K1​(x)+K2​(x).

Additivity allows complex inputs to be broken into simpler components that can be analyzed independently. Each component is processed separately, and the individual results are then combined to understand the system’s overall response. In medical imaging, this principle is critical for image reconstruction, where measured signals are often decomposed into contributions from different spatial locations or tissue properties.

2.19 Homogeneity

Homogeneity describes how a system responds when an input is scaled by a constant factor. A system is homogeneous if scaling the input by a scalar α\alphaα results in the output being scaled by the same factor. This property is expressed mathematically as

L(αv(t))=αL(v(t)).L(\alpha v(t)) = \alpha L(v(t)).L(αv(t))=αL(v(t)).

Using function notation, if an input f1(x)f_1(x)f1​(x) produces an output K1(x)K_1(x)K1​(x), then scaling the input by a constant a1a_1a1​ must scale the output accordingly. This relationship can be written as

f1(x)→H[f1(x)]→K1(x),f_1(x) \rightarrow H[f_1(x)] \rightarrow K_1(x),f1​(x)→H[f1​(x)]→K1​(x), a1f1(x)→H[a1f1(x)]→a1K1(x),a_1 f_1(x) \rightarrow H[a_1 f_1(x)] \rightarrow a_1 K_1(x),a1​f1​(x)→H[a1​f1​(x)]→a1​K1​(x),

which implies

H[a1f1(x)]=a1H[f1(x)].H[a_1 f_1(x)] = a_1 H[f_1(x)].H[a1​f1​(x)]=a1​H[f1​(x)].

Homogeneity ensures that the system preserves relative signal strength. In medical imaging, this means that doubling the signal intensity from tissue should double the measured response, assuming the system is operating within its linear range. This property is essential for accurate quantitative imaging.

2.20 Superposition and Zero Input Response

The superposition principle states that the response of a linear system to a weighted sum of inputs equals the same weighted sum of the individual responses. This principle follows directly from the combined application of additivity and homogeneity. Together, these properties allow linear systems to handle complex inputs by decomposing them into simpler signals.

A direct consequence of homogeneity is that if the input to a linear system is zero, the output must also be zero. Setting the scalar α=0\alpha = 0α=0 in the homogeneity condition yields

L(0⋅v(t))=0⋅L(v(t))=0.L(0 \cdot v(t)) = 0 \cdot L(v(t)) = 0.L(0⋅v(t))=0⋅L(v(t))=0.

This confirms that linear systems cannot generate output without an input.
When dealing with infinite sums of input components, linearity requires that the resulting infinite sum of outputs must converge. This condition ensures that the system’s response remains finite and physically meaningful. In imaging systems, convergence is critical when reconstructing images from large or continuous datasets.

2.21 Relationship Between Additivity and Homogeneity

Additivity and homogeneity are closely related but represent distinct aspects of linearity. Neither property alone is sufficient to guarantee that a system is linear. Additivity describes how the system handles multiple inputs, while homogeneity describes how it handles scaling.

Together, additivity and homogeneity define linearity, and both are required as separate conditions. However, when both properties hold, they combine to produce the superposition principle. In practice, linear systems are tested by verifying both conditions rather than attempting to derive one from the other.

In biomedical signal processing and medical imaging, verifying linearity allows engineers to apply powerful mathematical tools such as convolution, Fourier analysis, and inverse problem techniques. These tools form the foundation of image formation, reconstruction, and enhancement algorithms used throughout modern medical imaging.

2.22 Equivalence of Additivity and Homogeneity in Continuous Systems

In general, linearity is defined by the two separate conditions of additivity and homogeneity. However, in the special case of continuous systems, these two properties are not independent. Under continuity assumptions, one property can be derived from the other, meaning that additivity and homogeneity become mathematically equivalent.

This equivalence is important in theoretical system analysis because it simplifies the conditions required to establish linearity. Instead of verifying both properties independently, it is sufficient to verify one property along with continuity. This result has practical implications for modeling physical and imaging systems, which are often assumed to behave continuously.

2.23 Homogeneity Implies Scaling Properties

Consider a function f(x)f(x)f(x) that satisfies homogeneity, meaning that for any scalar nnn,
f(nx)=nf(x).f(nx) = n f(x).f(nx)=nf(x).

This equation expresses the idea that scaling the input by a factor nnn scales the output by the same factor. This is the defining characteristic of homogeneity.
From this property, additional scaling relationships can be derived. For example, the function value at xxx can be written as

f(x)=f(mxm)=mf(xm),f(x) = f\left(\frac{m x}{m}\right) = m f\left(\frac{x}{m}\right),f(x)=f(mmx​)=mf(mx​),

which implies

f(xm)=1mf(x).f\left(\frac{x}{m}\right) = \frac{1}{m} f(x).f(mx​)=m1​f(x).

This result shows that homogeneity applies not only to integer scaling but also to fractional scaling, provided the system behaves continuously.

Homogeneity also imposes constraints on the function’s behavior at the origin. Using additivity at zero,

f(0)=f(x+(−x))=f(x)+f(−x),f(0) = f(x + (-x)) = f(x) + f(-x),f(0)=f(x+(−x))=f(x)+f(−x),

which implies

f(−x)=−f(x).f(-x) = -f(x).f(−x)=−f(x).

This result confirms that homogeneous functions must be odd functions, a property consistent with linear behavior.

2.24 Constructing Additivity from Homogeneity

To demonstrate how additivity can be derived from homogeneity in continuous systems, consider two inputs x1x_1x1​ and x2x_2x2​ defined as scaled versions of a common variable xxx, such that

x1=α1x,x2=α2x,x_1 = \alpha_1 x, \quad x_2 = \alpha_2 x,x1​=α1​x,x2​=α2​x,

with x≠0x \neq 0x=0. These definitions allow both inputs to be expressed in terms of a single reference variable.

Applying the function to the sum of the inputs yields

f(x1+x2)=f(α1x+α2x)=f((α1+α2)x).f(x_1 + x_2) = f(\alpha_1 x + \alpha_2 x) = f((\alpha_1 + \alpha_2)x).f(x1​+x2​)=f(α1​x+α2​x)=f((α1​+α2​)x).

Using homogeneity, this becomes

f((α1+α2)x)=(α1+α2)f(x).f((\alpha_1 + \alpha_2)x) = (\alpha_1 + \alpha_2)f(x).f((α1​+α2​)x)=(α1​+α2​)f(x).

The right-hand side can be separated as

(α1+α2)f(x)=α1f(x)+α2f(x).(\alpha_1 + \alpha_2)f(x) = \alpha_1 f(x) + \alpha_2 f(x).(α1​+α2​)f(x)=α1​f(x)+α2​f(x).

Applying homogeneity again gives

α1f(x)=f(α1x),α2f(x)=f(α2x),\alpha_1 f(x) = f(\alpha_1 x), \quad \alpha_2 f(x) = f(\alpha_2 x),α1​f(x)=f(α1​x),α2​f(x)=f(α2​x),

which leads to

f(x1+x2)=f(x1)+f(x2).f(x_1 + x_2) = f(x_1) + f(x_2).f(x1​+x2​)=f(x1​)+f(x2​).

This confirms that additivity can be constructed directly from homogeneity under continuity assumptions.

2.25 Implications for Linear System Theory

The derivation above demonstrates that in continuous systems, homogeneity alone is sufficient to guarantee additivity. As a result, additivity and homogeneity are not independent conditions in this special case. Either property can imply the other when continuity is assumed.

This equivalence is particularly relevant in biomedical imaging and signal processing, where systems are often modeled as continuous and smooth. Under these assumptions, verifying one linearity condition may be enough to justify the use of linear system theory. This simplification supports the widespread application of superposition, Fourier analysis, and reconstruction algorithms in medical imaging.

Understanding when and why these properties are equivalent helps clarify the theoretical foundations of linear modeling. It also highlights the importance of continuity assumptions when applying mathematical abstractions to real-world imaging systems.

2.26 Independence of Homogeneity

Although additivity and homogeneity together define linearity, additivity alone does not guarantee homogeneity. This can be demonstrated using a counterexample from complex-valued functions. Such examples are important because they show why both properties must be explicitly verified when testing whether a system is linear.

Consider the function

f(z)=z∗f(z) = z^*f(z)=z∗

where z=a+ibz = a + ibz=a+ib is a complex number and z∗=a−ibz^* = a - ibz∗=a−ib denotes its complex conjugate. This function maps each complex number to its conjugate and is commonly encountered in complex analysis and signal processing.

To test additivity, let z1z_1z1​ and z2z_2z2​ be complex numbers. Then,

f(z1+z2)=(z1+z2)∗=z1∗+z2∗=f(z1)+f(z2).f(z_1 + z_2) = (z_1 + z_2)^* = z_1^* + z_2^* = f(z_1) + f(z_2).f(z1​+z2​)=(z1​+z2​)∗=z1∗​+z2∗​=f(z1​)+f(z2​).

This confirms that the function satisfies additivity, since the conjugate of a sum equals the sum of the conjugates.

However, homogeneity does not hold for this function. For a complex scalar α\alphaα,

f(αz)=(αz)∗=α∗z∗,f(\alpha z) = (\alpha z)^* = \alpha^* z^*,f(αz)=(αz)∗=α∗z∗,

which is not equal to

αz∗=αf(z)\alpha z^* = \alpha f(z)αz∗=αf(z)

unless α\alphaα is real. Because complex conjugation also conjugates the scalar, the scaling factor is altered. This violation of homogeneity demonstrates that additivity alone is insufficient to establish linearity.

This example shows that a system can be additive without being homogeneous. Therefore, additivity does not imply homogeneity, and both conditions must be checked independently when determining whether a system is linear.

2.27 Independence of Additivity

Homogeneity alone is also insufficient to guarantee linearity, as demonstrated by a counterexample involving real-valued functions. Consider the function

f(x)={m1x,if x is rational,m2x,if x is irrational,f(x) = \begin{cases} m_1 x, & \text{if } x \text{ is rational}, \\ m_2 x, & \text{if } x \text{ is irrational}, \end{cases}f(x)={m1​x,m2​x,​if x is rational,if x is irrational,
​
where m1m_1m1​ and m2m_2m2​ are rational constants with m1≠m2m_1 \neq m_2m1​=m2​. This function behaves differently depending on whether the input is rational or irrational.
Assume that the scalar domain consists only of rational numbers. Under rational scaling, the rationality or irrationality of a number does not change. Therefore, for any rational scalar α\alphaα,

f(αx)=αf(x),f(\alpha x) = \alpha f(x),f(αx)=αf(x),

which confirms that the function satisfies homogeneity under this restricted scalar domain.

However, additivity fails for this function. Consider two irrational numbers x1x_1x1​ and x2x_2x2​ whose sum is rational. Then,

f(x1+x2)=m1(x1+x2),f(x_1 + x_2) = m_1(x_1 + x_2),f(x1​+x2​)=m1​(x1​+x2​),

since x1+x2x_1 + x_2x1​+x2​ is rational. On the other hand,

f(x1)+f(x2)=m2x1+m2x2=m2(x1+x2).f(x_1) + f(x_2) = m_2 x_1 + m_2 x_2 = m_2(x_1 + x_2).f(x1​)+f(x2​)=m2​x1​+m2​x2​=m2​(x1​+x2​).

Because m1≠m2m_1 \neq m_2m1​=m2​, these expressions are not equal, and additivity is violated.

This example demonstrates that homogeneity does not imply additivity. A system may scale inputs correctly while failing to preserve sums, which disqualifies it from being linear.
