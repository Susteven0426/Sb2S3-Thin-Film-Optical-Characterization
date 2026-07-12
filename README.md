# 高折射率低損耗 Sb2S3 光學等級薄膜成長之研究
(High-Refractive-Index Low-Loss Sb2S3 Optical-Grade Thin Films Grown by Chemical Bath Deposition)

This repository contains the research data and MATLAB fitting program for my Master's thesis at the Department of Optics and Photonics, National Central University[cite: 1].

## 📖 Project Overview

This research aims to fabricate high-refractive-index, low-loss antimony sulfide (Sb2S3) thin films using a low-cost Chemical Bath Deposition (CBD) method[cite: 1]. Because existing CBD literature lacks complete refractive index (n) and extinction coefficient (k) dispersion data, this project developed a custom MATLAB ellipsometry fitting program to establish a comprehensive optical constants database for phase-change photonic devices[cite: 1].

## ✨ Key Research Highlights

*   **Optimized CBD Process:** Established an optimal low-temperature deposition process at 6~8°C for 5 hours with SnCl2 substrate pretreatment[cite: 1]. This method successfully yields smooth, optical-quality amorphous Sb2S3 films[cite: 1].
*   **Custom MATLAB Fitting Program:** Developed an ellipsometry fitting program based on the Tauc-Lorentz model[cite: 1]. It innovatively introduces a "Normalized Mean Square Error (Normalized MSE)" algorithm to solve the weight imbalance issue between Psi (Ψ) and Delta (Δ) parameters[cite: 1].
*   **Accurate Optical Constants:** The extracted amorphous films achieved a refractive index of n ≈ 2.33~2.43 (at 633 nm) and an optical bandgap of approximately 2.09~2.15 eV[cite: 1]. Tauc plot and Photoluminescence (PL) analyses further confirmed it is an indirect bandgap semiconductor[cite: 1].
*   **Annealing & Phase Change Analysis:** Investigated the phase change behavior, showing that annealing between 250°C and 300°C transformed the films into the orthorhombic crystalline phase[cite: 1]. This process drops the bandgap to about 1.44 eV and reaches 93.77% crystallinity at 300°C[cite: 1].

## 📂 Repository Structure

*   `Thesis/`: Full PDF document of the Master's thesis.
*   `MATLAB_Code/`: The custom ellipsometry fitting program featuring the Normalized MSE algorithm.
*   `Data/`: Raw measurement data including Spectroscopic Ellipsometry, Transmittance, GIXRD, and PL spectra.

## 👨‍🔬 Author

**Sheng-Xun Su (蘇聖勛)**[cite: 1]
M.S., Department of Optics and Photonics, National Central University (國立中央大學光電科學與工程學系)[cite: 1]
