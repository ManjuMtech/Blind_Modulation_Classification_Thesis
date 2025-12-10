# Blind AMC using EM-Based Channel Estimation and Cumulant Features
The goal of this thesis is to design a blind modulation classification system capable of operating in unknown channel environment

Steps:
• Generate PSK/QAM signals: BPSK, QPSK, N-PSK, 16-PSK, 8-QAM, 16-QAM, 32-QAM, 64-QAM.
• Estimate channel blindly using EM → obtain h and σ².
• Initialize EM parameters using K-means clustering.
• Compute cumulants: C₄₂, C₆₃, C₈₀, C₈₄ after channel inversion.
• Perform distance-based classification in cumulant feature space. Image_1.png Image_2.png

# Scenario 1: Classification Under Single-Tap Channel
1. Required sample count (histograms) for all modulation types
– evaluated using perfect and EM-estimated channel parameters.
2. Classification confidence comparison
– shown for both perfect and EM-based channel estimation.
https://github.com/ManjuMtech/Blind_Modulation_Classification_Thesis/blob/main/Image_1.png (Perfect Chl case)
https://github.com/ManjuMtech/Blind_Modulation_Classification_Thesis/blob/main/Image_2.png (EM est case)

