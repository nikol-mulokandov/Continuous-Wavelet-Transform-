

## **Project Overview**

This project implements Continuous Wavelet Transform (CWT) techniques based on the article "Application of Wavelet Transform in Analysis of Cough Sound Records" to analyze cough signals. CWT is ideal for handling the rapid temporal changes in cough signals by providing simultaneous time and frequency domain representation.

### **Implementation**

- **Data Processing:** Applied CWT to cough recordings using Mexican Hat, Haar, and Morlet wavelets. Verified the approach with a reference signal and generated scalograms as time vs. scale.
- **Resolution Analysis:** Evaluated four resolutions (1:16, 1:31, 1:61, 1:128) to explore frequency and scale relationships.

### **Results**

- **Reference Signal:** Scalograms aligned with expected results, confirming the inverse relationship between frequency and scale.
- **Cough Signal:** Morlet and Haar wavelets demonstrated the best correlation and detail, while the Mexican Hat wavelet was less effective.

### **Conclusion**

The project effectively applied CWT for analyzing cough signals, with Morlet wavelet showing the most suitability. The analysis provides insights into selecting appropriate wavelets and resolution for detailed signal representation.

