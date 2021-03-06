# This document contains examples of the model coefficients, generated using ARMPM\_BUILDMODEL

**March 2019 - Due to an urgent request I have created this document to provide some example models and coefficients. Please note that the models need to be retrained for each system they are used on. I have demonstrated significant variability, even between boards using the same SoC, therefore the tables given here are just to provide a case study. Practical use involves using the entire methodology to generate/validate models. I can't guarantee that these coefficients will perform well, when used on a different system.**

The tables, presented in this document, refer to the PMU events by their *RAW* identifiers. I have provided a table at the end listing all the events corresponding to these identifiers that are avilable for the ODROID XU3. These coefficients are also available in *Appendix D* of my doctorate dissertation [**Power Modelling and Analysis on Heterogeneous Embedded Systems**](https://seis.bristol.ac.uk/~eejlny/downloads/kris_thesis.pdf).

## ODROID-XU3 Cortex-A15 Single-Thread Power Model Coefficients

| Frequency 	| Constant 	| r011      	| r014     	| r004     	| r01D      	| r065      	| r079     	|
|-----------	|----------	|-----------	|----------	|----------	|-----------	|-----------	|----------	|
| 2         	| 1.45E+00 	| 2.87E-07  	| 1.23E-09 	| 6.50E-10 	| -1.44E-06 	| -8.28E-06 	| 8.94E-10 	|
| 1.9       	| 1.31E+00 	| -1.22E-07 	| 1.06E-09 	| 5.49E-10 	| 6.08E-07  	| -9.27E-06 	| 3.26E-09 	|
| 1.8       	| 1.13E+00 	| -3.10E-07 	| 9.54E-10 	| 5.01E-10 	| 1.55E-06  	| -8.23E-06 	| 1.93E-10 	|
| 1.7       	| 9.50E-01 	| -6.75E-08 	| 8.62E-10 	| 4.93E-10 	| 2.70E-07  	| -5.48E-06 	| 1.81E-09 	|
| 1.6       	| 8.40E-01 	| 1.77E-08  	| 8.09E-10 	| 4.37E-10 	| -7.07E-08 	| -4.97E-06 	| 1.30E-09 	|
| 1.5       	| 6.97E-01 	| -2.10E-07 	| 7.62E-10 	| 3.88E-10 	| 8.41E-07  	| -2.71E-06 	| 1.69E-09 	|
| 1.4       	| 6.59E-01 	| -1.12E-07 	| 7.06E-10 	| 3.89E-10 	| 4.48E-07  	| -2.93E-06 	| 8.86E-10 	|
| 1.3       	| 5.74E-01 	| -1.43E-07 	| 6.93E-10 	| 3.80E-10 	| 4.28E-07  	| -2.13E-06 	| 1.21E-09 	|
| 1.2       	| 4.27E-01 	| -1.54E-08 	| 6.46E-10 	| 3.70E-10 	| 4.66E-08  	| 1.04E-07  	| 1.89E-09 	|
| 1.1       	| 3.46E-01 	| -2.10E-07 	| 6.44E-10 	| 3.03E-10 	| 6.31E-07  	| 9.50E-07  	| 1.78E-09 	|
| 1         	| 2.71E-01 	| -5.93E-08 	| 5.85E-10 	| 3.30E-10 	| 1.78E-07  	| 1.71E-06  	| 1.99E-09 	|
| 0.9       	| 2.78E-01 	| -5.38E-08 	| 5.49E-10 	| 3.17E-10 	| 1.62E-07  	| 6.12E-07  	| 1.87E-09 	|
| 0.8       	| 2.31E-01 	| -3.13E-08 	| 5.16E-10 	| 2.99E-10 	| 9.41E-08  	| 8.82E-07  	| 2.08E-09 	|
| 0.7       	| 2.19E-01 	| -3.18E-08 	| 5.05E-10 	| 2.95E-10 	| 9.57E-08  	| 7.05E-07  	| 1.77E-09 	|
| 0.6       	| 1.90E-01 	| -2.96E-08 	| 5.11E-10 	| 2.98E-10 	| 8.89E-08  	| 8.87E-07  	| 1.61E-09 	|
| 0.5       	| 1.68E-01 	| -1.94E-08 	| 5.13E-10 	| 2.95E-10 	| 5.82E-08  	| 1.15E-06  	| 1.60E-09 	|
| 0.4       	| 1.52E-01 	| -2.40E-09 	| 5.04E-10 	| 2.96E-10 	| 7.05E-09  	| 1.78E-06  	| 1.53E-09 	|
| 0.3       	| 9.94E-02 	| -1.09E-08 	| 4.96E-10 	| 2.94E-10 	| 3.27E-08  	| 5.06E-06  	| 1.14E-09 	|
| 0.2       	| 8.07E-02 	| 3.34E-09  	| 4.83E-10 	| 2.98E-10 	| -1.04E-08 	| 5.48E-06  	| 7.77E-10 	|

## ODROID-XU3 Cortex-A7 Single-Thread Power Model Coefficients

| Frequency 	| Constant 	| r011      	| r060      	| r017     	| r00F     	| r01D      	|
|-----------	|----------	|-----------	|-----------	|----------	|----------	|-----------	|
| 1.4       	| 2.30E-01 	| -5.27E-08 	| -1.56E-08 	| 3.72E-08 	| 5.51E-09 	| 2.11E-07  	|
| 1.3       	| 1.87E-01 	| 1.00E-08  	| -1.42E-08 	| 3.45E-08 	| 8.69E-09 	| -2.98E-08 	|
| 1.2       	| 1.76E-01 	| 2.25E-08  	| -1.28E-08 	| 3.52E-08 	| 6.17E-09 	| -6.74E-08 	|
| 1.1       	| 1.47E-01 	| 1.25E-08  	| -1.13E-08 	| 3.23E-08 	| 6.46E-09 	| -3.73E-08 	|
| 1         	| 1.41E-01 	| -1.41E-08 	| -1.01E-08 	| 2.78E-08 	| 6.70E-09 	| 4.23E-08  	|
| 0.9       	| 1.17E-01 	| -2.47E-08 	| -8.48E-09 	| 2.36E-08 	| 7.17E-09 	| 7.40E-08  	|
| 0.8       	| 8.97E-02 	| 2.37E-10  	| -7.38E-09 	| 2.29E-08 	| 6.47E-09 	| -6.58E-10 	|
| 0.7       	| 8.13E-02 	| -1.20E-09 	| -6.45E-09 	| 2.13E-08 	| 6.80E-09 	| 3.58E-09  	|
| 0.6       	| 6.91E-02 	| -2.47E-09 	| -5.49E-09 	| 1.91E-08 	| 5.92E-09 	| 7.34E-09  	|
| 0.5       	| 5.76E-02 	| 5.77E-10  	| -4.74E-09 	| 1.77E-08 	| 6.18E-09 	| -1.85E-09 	|
| 0.4       	| 4.95E-02 	| 5.51E-10  	| -4.11E-09 	| 1.64E-08 	| 5.70E-09 	| -1.80E-09 	|
| 0.3       	| 4.58E-02 	| 1.82E-10  	| -4.35E-09 	| 1.82E-08 	| 5.22E-09 	| -8.43E-10 	|
| 0.2       	| 2.76E-02 	| 4.37E-10  	| -3.56E-09 	| 1.49E-08 	| 3.63E-09 	| -1.50E-09 	|

## ODROID-XU3 Cortex-A15 Multi-Thread Power Model Coefficients

| Frequency 	| Constant 	| Number of Cores 	| r011    	| r040      	| r010     	| r07E     	| r058     	| r078     	| r01D     	|
|-----------	|----------	|-----------------	|---------	|-----------	|----------	|----------	|----------	|----------	|----------	|
| 1.8       	| 5.98E-1  	| 2.08E-1         	| 9.38E-7 	| 2.78E-10  	| -3.35E-8 	| -1.91E-7 	| 1.76E-6  	| 3.51E-9  	| -4.69E-6 	|
| 1.7       	| 5.02E-1  	| 1.02E-1         	| 7.71E-7 	| 6.93E-10  	| -3.09E-8 	| -9.53E-8 	| -8.86E-6 	| 2.47E-9  	| -3.08E-6 	|
| 1.6       	| 4.51E-1  	| 5.72E-2         	| 7.79E-7 	| 2.40E-10  	| -2.67E-8 	| -9.63E-8 	| -9.22E-6 	| 2.78E-9  	| -3.11E-6 	|
| 1.5       	| 4.11E-1  	| 4.81E-2         	| 3.88E-7 	| 3.78E-10  	| -2.43E-8 	| -8.93E-8 	| -1.22E-5 	| 2.25E-9  	| -1.55E-6 	|
| 1.4       	| 3.53E-1  	| 7.79E-2         	| 5.70E-7 	| 2.44E-10  	| -2.61E-8 	| -1.14E-7 	| -6.77E-6 	| 2.41E-9  	| -2.28E-6 	|
| 1.3       	| 3.15E-1  	| 8.55E-2         	| 8.06E-7 	| 9.80E-11  	| -2.43E-8 	| -1.08E-7 	| -3.81E-6 	| 2.40E-9  	| -2.42E-6 	|
| 1.2       	| 2.80E-1  	| 6.98E-2         	| 6.21E-7 	| 1.85E-11  	| -2.42E-8 	| -1.04E-7 	| -1.64E-6 	| 2.38E-9  	| -1.86E-6 	|
| 1.1       	| 2.47E-1  	| 4.54E-2         	| 4.76E-7 	| 2.37E-10  	| -2.08E-8 	| -7.57E-8 	| -2.27E-6 	| 1.83E-9  	| -1.42E-6 	|
| 1         	| 2.25E-1  	| 5.67E-2         	| 3.92E-7 	| -2.57E-10 	| -2.31E-8 	| -1.03E-7 	| -6.46E-6 	| 2.49E-9  	| -1.17E-6 	|
| 0.9       	| 1.89E-1  	| 2.45E-2         	| 3.96E-7 	| -1.40E-10 	| -2.06E-8 	| -7.52E-8 	| -1.75E-6 	| 2.12E-9  	| -1.19E-6 	|
| 0.8       	| 1.70E-1  	| 2.93E-2         	| 4.11E-7 	| -6.24E-11 	| -1.82E-8 	| -7.84E-8 	| -2.57E-6 	| 1.76E-9  	| -1.23E-6 	|
| 0.7       	| 1.43E-1  	| 2.58E-2         	| 2.70E-7 	| 1.48E-10  	| -1.76E-8 	| -6.45E-8 	| -2.27E-6 	| 1.40E-9  	| -8.09E-7 	|
| 0.6       	| 1.25E-1  	| 1.59E-2         	| 1.77E-7 	| 1.27E-10  	| -1.75E-8 	| -5.97E-8 	| -2.07E-6 	| 1.40E-9  	| -5.30E-7 	|
| 0.5       	| 1.06E-1  	| 1.16E-2         	| 1.90E-7 	| 2.38E-10  	| -1.67E-8 	| -5.41E-8 	| -1.27E-6 	| 1.25E-9  	| -5.70E-7 	|
| 0.4       	| 8.18E-2  	| 1.12E-2         	| 1.07E-7 	| 3.13E-10  	| -1.60E-8 	| -4.82E-8 	| -1.41E-6 	| 1.07E-9  	| -3.19E-7 	|
| 0.3       	| 6.24E-2  	| 3.82E-3         	| 6.08E-8 	| 4.20E-10  	| -1.59E-8 	| -3.65E-8 	| -4.52E-7 	| 9.73E-10 	| -1.81E-7 	|
| 0.2       	| 4.38E-2  	| 2.35E-3         	| 1.44E-8 	| 4.86E-10  	| -1.54E-8 	| -2.85E-8 	| -3.91E-7 	| 9.02E-10 	| -4.15E-8 	|

## ODROID-XU3 Cortex-A7 Multi-Thread Power Model Coefficients

| Frequency 	| Constant 	| Number of cores 	| r011     	| r014     	| r015     	| r006     	| r00D      	|
|-----------	|----------	|-----------------	|----------	|----------	|----------	|----------	|-----------	|
| 1.4       	| 9.54E-02 	| 1.46E-02        	| 9.30E-11 	| 3.34E-10 	| 2.56E-09 	| 2.28E-10 	| -2.55E-10 	|
| 1.3       	| 8.04E-02 	| 1.14E-02        	| 8.38E-11 	| 3.15E-10 	| 2.80E-09 	| 1.98E-10 	| -2.47E-10 	|
| 1.2       	| 6.79E-02 	| 1.21E-02        	| 7.72E-11 	| 2.61E-10 	| 2.07E-09 	| 2.01E-10 	| -2.18E-10 	|
| 1.1       	| 5.89E-02 	| 1.08E-02        	| 7.23E-11 	| 2.71E-10 	| 2.21E-09 	| 1.00E-10 	| -2.23E-10 	|
| 1         	| 5.03E-02 	| 8.83E-03        	| 6.98E-11 	| 2.40E-10 	| 1.97E-09 	| 1.33E-10 	| -2.50E-10 	|
| 0.9       	| 4.08E-02 	| 6.83E-03        	| 6.79E-11 	| 2.03E-10 	| 1.82E-09 	| 1.51E-10 	| -1.74E-10 	|
| 0.8       	| 3.07E-02 	| 4.12E-03        	| 6.92E-11 	| 1.97E-10 	| 1.68E-09 	| 9.39E-11 	| -1.94E-10 	|
| 0.7       	| 2.38E-02 	| 3.59E-03        	| 6.52E-11 	| 1.72E-10 	| 1.66E-09 	| 1.17E-10 	| -1.53E-10 	|
| 0.6       	| 1.72E-02 	| 3.52E-03        	| 6.08E-11 	| 1.87E-10 	| 1.85E-09 	| 5.89E-11 	| -1.95E-10 	|
| 0.5       	| 1.31E-02 	| 2.49E-03        	| 6.10E-11 	| 1.49E-10 	| 1.55E-09 	| 8.33E-11 	| -1.56E-10 	|
| 0.4       	| 1.08E-02 	| 1.97E-03        	| 6.59E-11 	| 1.49E-10 	| 1.60E-09 	| 6.68E-11 	| -1.67E-10 	|
| 0.3       	| 8.60E-03 	| 1.49E-03        	| 7.00E-11 	| 1.46E-10 	| 1.62E-09 	| 6.41E-11 	| -1.83E-10 	|
| 0.2       	| 6.10E-03 	| 9.64E-04        	| 7.90E-11 	| 1.36E-10 	| 1.60E-09 	| 5.72E-11 	| -1.97E-10 	|

## ODROID-XU3 Cortex-A15 Single-Thread Inter-Core Power Model Coefficients

| Frequency 	| Constant 	| r011      	| r00A     	| r010     	| r018      	| r019      	|
|-----------	|----------	|-----------	|----------	|----------	|-----------	|-----------	|
| 2         	| 1.72E+00 	| 5.02E-11  	| 5.66E-06 	| 4.47E-08 	| 4.36E-06  	| -1.91E-07 	|
| 1.9       	| 1.38E+00 	| 6.99E-11  	| 5.21E-06 	| 3.83E-08 	| 3.23E-06  	| -1.43E-07 	|
| 1.8       	| 1.28E+00 	| -5.09E-11 	| 4.21E-06 	| 3.42E-08 	| 3.26E-06  	| -1.42E-07 	|
| 1.7       	| 1.08E+00 	| 1.28E-11  	| 4.14E-06 	| 3.19E-08 	| 2.76E-06  	| -1.21E-07 	|
| 1.6       	| 1.01E+00 	| -6.45E-11 	| 3.49E-06 	| 2.90E-08 	| 2.72E-06  	| -1.19E-07 	|
| 1.5       	| 9.69E-01 	| -1.87E-10 	| 3.25E-06 	| 2.65E-08 	| 2.64E-06  	| -1.15E-07 	|
| 1.4       	| 9.20E-01 	| -2.61E-10 	| 2.96E-06 	| 2.54E-08 	| 2.53E-06  	| -1.09E-07 	|
| 1.3       	| 8.57E-01 	| -2.80E-10 	| 2.98E-06 	| 2.36E-08 	| 2.33E-06  	| -9.94E-08 	|
| 1.2       	| 6.80E-01 	| -1.41E-10 	| 2.72E-06 	| 2.17E-08 	| 1.86E-06  	| -7.85E-08 	|
| 1.1       	| 5.24E-01 	| 8.31E-12  	| 2.80E-06 	| 2.01E-08 	| 1.24E-06  	| -5.19E-08 	|
| 1         	| 4.33E-01 	| 5.35E-11  	| 2.93E-06 	| 1.78E-08 	| 8.47E-07  	| -3.37E-08 	|
| 0.9       	| 3.71E-01 	| 5.23E-11  	| 2.72E-06 	| 1.67E-08 	| 6.82E-07  	| -2.66E-08 	|
| 0.8       	| 3.19E-01 	| 3.53E-11  	| 2.48E-06 	| 1.57E-08 	| 6.22E-07  	| -2.33E-08 	|
| 0.7       	| 2.95E-01 	| -2.57E-11 	| 2.55E-06 	| 1.51E-08 	| 5.90E-07  	| -2.26E-08 	|
| 0.6       	| 2.34E-01 	| 5.20E-11  	| 2.65E-06 	| 1.52E-08 	| 4.63E-07  	| -1.71E-08 	|
| 0.5       	| 1.90E-01 	| 8.85E-11  	| 2.72E-06 	| 1.48E-08 	| 2.13E-07  	| -5.98E-09 	|
| 0.4       	| 1.38E-01 	| 1.79E-10  	| 2.57E-06 	| 1.43E-08 	| 6.63E-08  	| 1.17E-09  	|
| 0.3       	| 9.34E-02 	| 2.82E-10  	| 2.50E-06 	| 1.37E-08 	| -8.23E-08 	| 8.33E-09  	|
| 0.2       	| 7.42E-02 	| 2.17E-10  	| 2.32E-06 	| 1.37E-08 	| 7.21E-10  	| 5.57E-09  	|

## ODROID-XU3 Cortex-A7 Single-Thread Inter-Core Power Model Coefficients

| Frequency 	| Constant 	| r011      	| r014     	| r012      	|
|-----------	|----------	|-----------	|----------	|-----------	|
| 1.4       	| 2.26E-01 	| -4.32E-11 	| 3.79E-10 	| -3.20E-10 	|
| 1.3       	| 1.91E-01 	| -3.71E-11 	| 3.66E-10 	| -3.43E-10 	|
| 1.2       	| 1.70E-01 	| -4.79E-11 	| 3.20E-10 	| -3.16E-10 	|
| 1.1       	| 1.47E-01 	| -4.80E-11 	| 2.99E-10 	| -3.02E-10 	|
| 1         	| 1.34E-01 	| -6.17E-11 	| 2.79E-10 	| -3.21E-10 	|
| 0.9       	| 1.13E-01 	| -5.71E-11 	| 2.54E-10 	| -3.06E-10 	|
| 0.8       	| 8.69E-02 	| -5.63E-11 	| 2.29E-10 	| -2.85E-10 	|
| 0.7       	| 7.95E-02 	| -7.35E-11 	| 2.10E-10 	| -2.85E-10 	|
| 0.6       	| 6.59E-02 	| -7.49E-11 	| 1.85E-10 	| -2.54E-10 	|
| 0.5       	| 6.33E-02 	| -1.16E-10 	| 1.70E-10 	| -2.50E-10 	|
| 0.4       	| 5.43E-02 	| -1.23E-10 	| 1.59E-10 	| -2.55E-10 	|
| 0.3       	| 5.38E-02 	| -2.07E-10 	| 1.75E-10 	| -2.91E-10 	|
| 0.2       	| 4.38E-02 	| -2.71E-10 	| 1.42E-10 	| -2.02E-10 	|

## ODROID-XU3 Cortex-A15 Multi-Thread Inter-Core Power Model Coefficients

| Frequency 	| Constant 	| Number of Cores 	| r011     	| r009      	| r018      	| r010      	| r00A     	|
|-----------	|----------	|-----------------	|----------	|-----------	|-----------	|-----------	|----------	|
| 1.8       	| 6.22E-01 	| 1.24E-01        	| 1.26E-09 	| -8.41E-05 	| -3.58E-07 	| 1.46E-09  	| 4.07E-05 	|
| 1.7       	| 5.50E-01 	| 9.43E-02        	| 1.17E-09 	| -7.16E-05 	| -2.86E-07 	| 2.02E-09  	| 3.41E-05 	|
| 1.6       	| 4.65E-01 	| 8.24E-02        	| 1.09E-09 	| -7.12E-05 	| -2.37E-07 	| 3.16E-09  	| 3.45E-05 	|
| 1.5       	| 4.07E-01 	| 5.28E-02        	| 1.03E-09 	| -7.18E-05 	| -2.08E-07 	| 7.13E-10  	| 3.54E-05 	|
| 1.4       	| 3.54E-01 	| 9.22E-02        	| 9.24E-10 	| -5.13E-05 	| -1.87E-07 	| -9.73E-10 	| 2.34E-05 	|
| 1.3       	| 3.20E-01 	| 5.92E-02        	| 9.44E-10 	| -5.52E-05 	| -1.63E-07 	| -1.54E-09 	| 2.62E-05 	|
| 1.2       	| 2.96E-01 	| 5.62E-02        	| 8.74E-10 	| -3.23E-05 	| -1.42E-07 	| -3.78E-09 	| 1.40E-05 	|
| 1.1       	| 2.52E-01 	| 3.90E-02        	| 8.53E-10 	| -4.78E-05 	| -1.32E-07 	| -2.61E-09 	| 2.29E-05 	|
| 1         	| 2.30E-01 	| 2.24E-02        	| 8.12E-10 	| -5.05E-05 	| -1.09E-07 	| -6.49E-10 	| 2.45E-05 	|
| 0.9       	| 2.03E-01 	| 2.77E-02        	| 7.50E-10 	| -4.17E-05 	| -9.46E-08 	| -2.84E-09 	| 1.97E-05 	|
| 0.8       	| 1.74E-01 	| 1.94E-02        	| 7.13E-10 	| -2.37E-05 	| -7.46E-08 	| -3.52E-09 	| 1.04E-05 	|
| 0.7       	| 1.48E-01 	| 1.08E-02        	| 7.17E-10 	| -3.14E-05 	| -6.38E-08 	| -3.05E-09 	| 1.48E-05 	|
| 0.6       	| 1.27E-01 	| 5.94E-03        	| 7.35E-10 	| -2.69E-05 	| -5.23E-08 	| -2.92E-09 	| 1.24E-05 	|
| 0.5       	| 1.07E-01 	| 5.33E-03        	| 7.44E-10 	| -3.31E-05 	| -4.65E-08 	| -3.78E-09 	| 1.58E-05 	|
| 0.4       	| 8.31E-02 	| 2.49E-03        	| 7.75E-10 	| -3.04E-05 	| -3.44E-08 	| -4.21E-09 	| 1.44E-05 	|
| 0.3       	| 6.29E-02 	| 1.15E-03        	| 7.92E-10 	| -2.41E-05 	| -2.43E-08 	| -4.35E-09 	| 1.11E-05 	|
| 0.2       	| 4.39E-02 	| 3.10E-04        	| 8.12E-10 	| -1.96E-05 	| -1.64E-08 	| -4.64E-09 	| 8.71E-06 	|

## ODROID-XU3 Cortex-A7 Multi-Thread Inter-Core Power Model Coefficients

| Frequency 	| Constant 	| Number of Cores 	| r011     	| r009      	| r00A      	|
|-----------	|----------	|-----------------	|----------	|-----------	|-----------	|
| 1.4       	| 1.17E-01 	| 2.12E-02        	| 1.70E-10 	| 4.10E-06  	| -3.16E-06 	|
| 1.3       	| 9.59E-02 	| 1.77E-02        	| 1.61E-10 	| 2.18E-06  	| -1.96E-06 	|
| 1.2       	| 7.98E-02 	| 1.73E-02        	| 1.46E-10 	| -1.32E-06 	| 1.83E-08  	|
| 1.1       	| 6.73E-02 	| 1.43E-02        	| 1.39E-10 	| 7.18E-07  	| -9.82E-07 	|
| 1         	| 5.77E-02 	| 1.22E-02        	| 1.32E-10 	| 4.44E-07  	| -8.17E-07 	|
| 0.9       	| 4.74E-02 	| 1.05E-02        	| 1.26E-10 	| 3.94E-07  	| -7.39E-07 	|
| 0.8       	| 3.51E-02 	| 7.22E-03        	| 1.22E-10 	| -1.13E-06 	| 1.62E-07  	|
| 0.7       	| 2.71E-02 	| 5.32E-03        	| 1.20E-10 	| -6.75E-07 	| -1.69E-08 	|
| 0.6       	| 1.97E-02 	| 4.29E-03        	| 1.17E-10 	| -5.34E-07 	| -5.17E-08 	|
| 0.5       	| 1.48E-02 	| 3.42E-03        	| 1.11E-10 	| -8.65E-07 	| 1.57E-07  	|
| 0.4       	| 1.22E-02 	| 2.61E-03        	| 1.15E-10 	| -1.05E-06 	| 2.92E-07  	|
| 0.3       	| 9.41E-03 	| 1.72E-03        	| 1.21E-10 	| -6.99E-07 	| 1.23E-07  	|
| 0.2       	| 6.48E-03 	| 9.49E-04        	| 1.29E-10 	| -1.58E-06 	| 6.49E-07  	|

## Available PMU Events for the big.LITTLE System

| Event Name                       	| Cortex-A15 	| Cortex-A7 	|
|----------------------------------	|------------	|-----------	|
| SW_INCR                          	| r000       	| r000      	|
| L1I_CACHE_REFILL                 	| r001       	| r001      	|
| L1I_TLB_REFILL                   	| r002       	| r002      	|
| L1D_CACHE_REFILL                 	| r003       	| r003      	|
| L1D_CACHE_ACCESS                 	| r004       	| r004      	|
| L1D_TLB_REFILL                   	| r005       	| r005      	|
| DATA_READS                       	| -          	| r006      	|
| DATA_WRITES                      	| -          	| r007      	|
| INST_RETIRED                     	| r008       	| r008      	|
| EXCEPTION_TAKEN                  	| r009       	| r009      	|
| EXCEPTION_RETURN                 	| r00A       	| r00A      	|
| CID_WRITE_RETIRED                	| r00B       	| r00B      	|
| SW_CHANGE_PC                     	| -          	| r00C      	|
| IMMEDIATE_BRANCHES               	| -          	| r00D      	|
| PROCEDURE_RETURNS                	| -          	| r00E      	|
| UNALIGNED_LOAD_STORE             	| -          	| r00F      	|
| BRANCH_MISPRED                   	| r010       	| r010      	|
| CPU_CYCLES                       	| r011       	| r011      	|
| BRANCH_PRED                      	| r012       	| r012      	|
| DATA_MEM_ACCESS                  	| r013       	| r013      	|
| L1I_CACHE_ACCESS                 	| r014       	| r014      	|
| L1D_CACHE_WB                     	| r015       	| r015      	|
| L2D_CACHE_ACCESS                 	| r016       	| r016      	|
| L2D_CACHE_REFILL                 	| r017       	| r017      	|
| L2D_CACHE_WB                     	| r018       	| r018      	|
| BUS_ACCESS                       	| r019       	| r019      	|
| LOCAL_MEMORY_ERROR               	| r01A       	| -         	|
| INST_SPEC_EXEC                   	| r01B       	| -         	|
| TTBR_WRITE_RETIRED               	| r01C       	| -         	|
| BUS_CYCLES                       	| r01D       	| r01D      	|
| L1D_READ_ACCESS                  	| r040       	| -         	|
| L1D_WRITE_ACCESS                 	| r041       	| -         	|
| L1D_READ_REFILL                  	| r042       	| -         	|
| L1D_WRITE_REFILL                 	| r043       	| -         	|
| L1D_WB_VICTIM                    	| r046       	| -         	|
| L1D_WB_CLEAN_COHERENCY           	| r047       	| -         	|
| L1D_INVALIDATE                   	| r048       	| -         	|
| L1D_TLB_READ_REFILL              	| r04C       	| -         	|
| L1D_TLB_WRITE_REFILL             	| r04D       	| -         	|
| L2D_READ_ACCESS                  	| r050       	| -         	|
| L2D_WRITE_ACCESS                 	| r051       	| -         	|
| L2D_READ_REFILL                  	| r052       	| -         	|
| L2D_WRITE_REFILL                 	| r053       	| -         	|
| L2D_WB_VICTIM                    	| r056       	| -         	|
| L2D_WB_CLEAN_COHERENCY           	| r057       	| -         	|
| L2D_INVALIDATE                   	| r058       	| -         	|
| BUS_READ_ACCESS                  	| r060       	| r060      	|
| BUS_WRITE_ACCESS                 	| r061       	| r061      	|
| BUS_NORMAL_ACCESS                	| r062       	| -         	|
| BUS_NOT_NORMAL_ACCESS            	| r063       	| -         	|
| BUS_NORMAL_ACCESS_2              	| r064       	| -         	|
| BUS_PERIPH_ACCESS                	| r065       	| -         	|
| DATA_MEM_READ_ACCESS             	| r066       	| -         	|
| DATA_MEM_WRITE_ACCESS            	| r067       	| -         	|
| UNALIGNED_READ_ACCESS            	| r068       	| -         	|
| UNALIGNED_WRITE_ACCESS           	| r069       	| -         	|
| UNALIGNED_ACCESS                 	| r06A       	| -         	|
| INST_SPEC_EXEC_LDREX             	| r06C       	| -         	|
| INST_SPEC_EXEC_STREX_PASS        	| r06D       	| -         	|
| INST_SPEC_EXEC_STREX_FAIL        	| r06E       	| -         	|
| INST_SPEC_EXEC_LOAD              	| r070       	| -         	|
| INST_SPEC_EXEC_STORE             	| r071       	| -         	|
| INST_SPEC_EXEC_LOAD_STORE        	| r072       	| -         	|
| INST_SPEC_EXEC_INTEGER_INST      	| r073       	| -         	|
| INST_SPEC_EXEC_SIMD              	| r074       	| -         	|
| INST_SPEC_EXEC_VFP               	| r075       	| -         	|
| INST_SPEC_EXEC_SOFT_PC           	| r076       	| -         	|
| BRANCH_SPEC_EXEC_IMM_BRANCH      	| r078       	| -         	|
| BRANCH_SPEC_EXEC_RET             	| r079       	| -         	|
| BRANCH_SPEC_EXEC_IND             	| r07A       	| -         	|
| BARRIER_SPEC_EXEC_ISB            	| r07C       	| -         	|
| BARRIER_SPEC_EXEC_DSB            	| r07D       	| -         	|
| BARRIER_SPEC_EXEC_DMB            	| r07E       	| -         	|
| IRQ_EXCEPTION_TAKEN              	| -          	| r086      	|
| FIQ_EXCEPTION_TAKEN              	| -          	| r087      	|
| EXTERNAL_MEMORY_REQUEST          	| -          	| r0C0      	|
| NONCACHE_EXTERNAL_MEMORY_REQUEST 	| -          	| r0C1      	|
| PREFETCH_LINEFILL                	| -          	| r0C2      	|
| PREFETCH_LINEFILL_DROPPED        	| -          	| r0C3      	|
| ENTERING_READ_ALLOC              	| -          	| r0C4      	|
| READ_ALLOC                       	| -          	| r0C5      	|
| Reserved                         	| -          	| r0C6      	|
| ETM_EXT_OUT_0                    	| -          	| r0C7      	|
| ETM_EXT_OUT_1                    	| -          	| r0C8      	|
| DATA_WRITE_STALL                 	| -          	| r0C9      	|
| DATA_SNOOPED                     	| -          	| r0CA      	|
