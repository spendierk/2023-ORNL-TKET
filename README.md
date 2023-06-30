# 2023-ORNL-QC-User-Workshop-TKET

July 17th – 20th, 2023

Hosted by the Oak Ridge Leadership Computing Facility at Oak Ridge National Laboratory

The Quantum Computing User Forum, hosted by Oak Ridge National Laboratory, brings together users to discuss best practices in quantum computing development. It features presentations from top researchers in the field, including keynote talks, invited talks, poster sessions (July 18-19), and associated workshops.  For more information about this event please visit: https://www.olcf.ornl.gov/calendar/quantum-computing-user-forum-2023/


## QUANTINUUM WORKSHOP

The Quantinuum workshop consists of three sections that cover various aspects of the [Quantinuum H-Series platform](https://www.quantinuum.com/hardware). It concludes with a Quantinuum Q&A Panel, allowing participants to address any queries regarding the platform.

1) Introduction to Quantinuum H-Series and Unique Features: 
In this section, we will highlight the unique features of Quantinuum H-Series trapped ion quantum computers, such as high two-qubit gate fidelity, full connectivity, qubit re-use, mid-circuit measurement, plus some recent new additions.  We will also discuss how to take advantage of these unique features and showcase examples of actual circuits that have been run on the hardware.

2) Quantum Error Correction/Detection/Mitigation on H-Series:
Participants will study error correction and mitigation on the H-Series platform, including real-time decoding with color code, two-qubit gates, and circuit construction using OpenQASM, Q#, and QIR. The session also covers error detection via Iceberg code.

4) TKET User Features:
This section highlights the powerful features of [TKET](https://www.quantinuum.com/developers/tket), Quantinuum's advanced software development kit (SDK). Among other topics, participants will learn about PyTKET, circuit submission to H-series devices, compilation options, emulator usage with noise models, mid-circuit measurement, and circuit conversion to and from other SDKs. They will also explore performance optimization for IBM and otherRigetti platforms.

## This repository contains the notebook for the "TKET User Features" section of the workshop.

# Getting started with TKET

# [Installation](https://cqcl.github.io/pytket/manual/manual_intro.html#installation)
Tket is currently available through its pythonic realisation `pytket`, which is freely available under the Apache 2 license. To install using the pip package manager, just run `pip install pytket` from your terminal. Each extension module can also be installed similarly as `pip install pytket_X`, e.g. `pip install pytket_qiskit`.

`pytket` is available for python versions 3.8-10 on Linux, MacOS, and Windows. For any difficulties with installation, please consult our [troubleshooting page](https://cqcl.github.io/tket/pytket/api/install.html).
