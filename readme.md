# Radar Communication Integrated System - Joint Radar-Communication (JRC)

🎯 This framework provides computational validation for the research paper "FBMC Waveforms for Joint Radar-Communication" by IEEE, comparing theoretical predictions with simulation results through multiple performance metrics.
Core Features•
Dual Implementation: Python (main) and MATLAB versions
•  
Comprehensive Analysis: Spectral Characteristics, Distance-Doppler Processing, Diffuse Function and Doppler Limit
•  
Can be directly used for publication: High-quality charts and indicator tables, suitable for academic papers.
•  
Reproducible Research: Complete verification framework with documented parameters.
🚀 Quick Start Prerequisites•
Python ≥ 3.12  
•  
UV package manager
Installation and Usage # Clone or navigate to the repository cd fbmc_ttdf# Run the verification framework uv run main.py\nThe framework will generate comprehensive verification charts and metrics in the logs/ directory.
📊 Generated output visualization file 1
spectral_comparison.png - Power spectral density comparison
2  
range_doppler_comparison.png - 2D range-Doppler plot
3  
ambiguity_comparison.png - ambiguity function contour plot
4  
doppler_tolerance.png - Doppler Tolerance Curve
5  
metrics_table.png - Performance Metrics Table
Performance indicators
OFDM  
FBMC  
Improvement margin
Spectral efficiency
0.800  
1.000  
+25.0%  
Out-of-band radiation at 1.5 times bandwidth
Variable
Variable
Scheduled for 3-36 dB
Peak-to-average power ratio (PAPR)
~9.7 dB  
~10.1 dB  
A bit higher
Sidelobe level
Variable
Variable
Up to 15 dB
Complexity calculation
1.0×  
2.0×  
Increase by 2 times
🔬 Core Components for Technology Implementation
OFDM: Complete OFDM implementation with cyclic prefix
•  
FBMC: FBMC-OQAM with PHYDYAS prototype filter
•  
WaveformGenerator: Base class for QAM symbol generation
2. Signal Processing •
RadarProcessor: Distance-Doppler Processing, Diffusion Function
•  
Target simulation (configurable delay, Doppler shift, and amplitude)
•  
Noisy injection in multi-target scenarios
3. Analyze functions...
plot_spectral_comparison() - Spectral Analysis and Band-Band Radiation
•  
plot_range_doppler_comparison() - 2D radar processing plot
•  
plot_ambiguity_functions() - Time-frequency ambiguity analysis
•  
plot_doppler_tolerance() - Doppler Sensitivity Curve
•  
compute_performance_metrics() - Quantitative Metrics Calculation
•  
numpy >= 2.3.4 - Numerical Computation
•  
matplotlib >= 3.10.7 - Plotting and Visualization
•  
scipy >= 1.16.3 - Signal Processing and Scientific Computing
📈 Case Study Research •
IEEE paper verification: Provide computational support for theoretical claims
•  
Performance benchmark test: quantitative comparison framework
•  
Reproducible results: Standardization indicators and visualization
System Design •
Waveform selection: Comparison of evidence-based JRC applications
•  
Parameter Optimization: Sensitivity Analysis of Cross-System Parameters
•  
Implementation Planning: Balancing Complexity and Performance
Education field •
Algorithm Understanding: Clear Implementation of FBMC and OFDM
•  
Visualization: Intuitive charts for conceptual explanations
•  
Practical Learning: Modifiable parameters for experimental use.
🔬 Verification Method 1. Signal Generation
Generate M-QAM symbols for two waveforms
•  
Application of modulation (OFDM with IFFT, FBMC with multi-phase filtering)
•  
The same symbol sequence ensures fair comparison.
2. Radar Processing •
Simulate target echoes with real-world delay and Doppler shifts
•  
Add AWGN noise to simulate real-world scenarios
•  
Application of Matched Filtering and Doppler Processing
3. Metrics Calculation •
Spectral Efficiency: Considering the Prefix Overhead
•  
Out-of-band radiation: Measured at standardized frequency offset
•  
Peak-to-Average Power Ratio (PAPR): Peak-to-Average Power Ratio Calculation
•  
Sidelobes: Autocorrelation analysis
•  
Doppler tolerance: the relationship between correlation degradation and frequency offset
🔬 Scientific background of FBMC's advantages 1
No Loop Prefix: 20-25% Increase in Spectral Efficiency
2  
Improved Spectral Rejection: 10-40 dB Band-Away Radiation
3  
Better time-frequency locality: Improved sidelobes
4  
Enhanced Doppler Tolerance: approx. 2x performance improvement
OFDM's advantages 1
Lower complexity: Simple implementation based on FFT
2  
Mature technology: Comprehensive standards and hardware support.
3  
Lower peak-to-average power ratio: slightly higher efficiency of the power amplifier.
🛠 Advanced Usage Custom Parameter Scan
# Modify parameters N_subcarriers = [128, 256, 512] in fbmc_ofdm_validation.py
# Test different sizes of cp_ratios = [0.125, 0.25, 0.5]
# Various cyclic prefix lengths

Extension Analysis
# Add custom metrics to compute_performance_metrics() function
def compute_custom_metric():
    # Add your analysis code here
    pass

Integration with Research Tools
This framework is designed for integration with the following tools:
• Channel modeling tool
• Hardware simulation platform
• Standard development process

Contribution Guide
This is a research verification framework. For modifications:
1. 
Parameters Change: Update system parameters in the class constructor
2. 
New Indicators: Add to compute_performance_metrics() function
3. 
Additional Charts: Follow existing patterns to add new plotting functions
4. 
MATLAB Synchronization: Maintain consistency between the two implementations
📚 Relevant Work References
• FBMC-OQAM modulation theory
• PHYDYAS prototype filter design
• Joint radar-communication systems
• 5G/6G waveform comparisons

Application Areas
• Automotive Radar: Application in the 77-81 GHz band
• 5G/6G communication: Waveform research for next-generation systems
• Internet of Things and Massive MIMO: Spectral efficiency requirements
• Cognitive radio: Dynamic spectrum access scenarios

End

## Images

![(Radar Communication Integrated)Filter Bank Multicarrier (FBMC) and Orthogonal Frequency Division Multiplexing (OFDM) Waveforms in Joint Radar-Communication (JRC) Systems [with Python]](01.jpg)
![(Radar Communication Integrated)Filter Bank Multicarrier (FBMC) and Orthogonal Frequency Division Multiplexing (OFDM) Waveforms in Joint Radar-Communication (JRC) Systems [with Python]](02.jpg)
![(Radar Communication Integrated)Filter Bank Multicarrier (FBMC) and Orthogonal Frequency Division Multiplexing (OFDM) Waveforms in Joint Radar-Communication (JRC) Systems [with Python]](03.jpg)
![(Radar Communication Integrated)Filter Bank Multicarrier (FBMC) and Orthogonal Frequency Division Multiplexing (OFDM) Waveforms in Joint Radar-Communication (JRC) Systems [with Python]](04.jpg)
![(Radar Communication Integrated)Filter Bank Multicarrier (FBMC) and Orthogonal Frequency Division Multiplexing (OFDM) Waveforms in Joint Radar-Communication (JRC) Systems [with Python]](05.jpg)
![(Radar Communication Integrated)Filter Bank Multicarrier (FBMC) and Orthogonal Frequency Division Multiplexing (OFDM) Waveforms in Joint Radar-Communication (JRC) Systems [with Python]](06.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
