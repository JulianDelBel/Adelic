## Overview
This repository contains implementations of a mathematical framework based on prime-based adelic products and their mathematical relationships. The system is completely dimensionless by construction, with no arbitrary physical constants or dimensional parameters introduced.

All computations herein are strictly dimensionless. No arbitrary physical constants or dimensional parameters are required. All normalizations rely solely on prime-based adelic products and their intrinsic mechanisms.

## Mathematical Foundation

### Validation of Dimensionlessness
The construction is verified to be dimensionless through the following explicit checks:

#### 1. Prime Factors
Each prime $p$ is a pure integer → reciprocal $\frac{1}{p}$ is dimensionless.

#### 2. Real Factor
$$\prod_p \frac{1}{1-p^{-1}} = \prod_p \frac{p}{p-1}$$

Each term is a ratio of integers, preserving dimensionlessness.

#### 3. Normalization Factor ($dx$)
Defined as:
$$dx = \left(\frac{1}{\prod_p \frac{1}{1-p^{-1}} \prod_p \frac{1}{p}}\right)^{1/4}$$

This is constructed from dimensionless products, ensuring that the normalization itself remains dimensionless.

## Core Mathematical Construction

The adelic integration system is defined through:
$$\Lambda = \text{Re}_{dx} \times \prod_p \frac{1}{1-p^{-1}} \times \prod_p \frac{1}{p}$$

### Dimensionless Components

- **Real factor**: $\prod_p (1-p^{-1})^{-1}$ (Euler-type product)
- **p-adic factor**: $\prod_p \frac{1}{p}$ (Prime reciprocals)
- **Normalization**: $dx^4 = \left(\prod_p \frac{1}{p(p-1)}\right)^{-1}$

## Implementation Verification

The resulting computed value ($\Lambda = 1.0$) confirms internal consistency and dimensionlessness. The implementation correctly avoids introducing arbitrary "human constants" or dimensional scales, ensuring intrinsic mathematical purity.

## Key Results

The system demonstrates that fundamental mathematical relationships can be expressed through dimensionless constructions derived solely from the natural structure of prime numbers and their relationships.

## **Publications and Resources**

**Zenodo Records:**

* [Zenodo Record 14970879](https://zenodo.org/records/14970879)  
* [Zenodo Record 14969006](https://zenodo.org/records/14969006)  
* [Zenodo Record 14949122](https://zenodo.org/records/14949122)  
* [Zenodo Record 14994094](https://zenodo.org/records/14994094)  
* [Zenodo Record 14948910](https://zenodo.org/records/14948910)  
* [Zenodo Record 15022520](https://zenodo.org/records/15022520)  
* [Zenodo Record 15022735](https://zenodo.org/records/15022735)  
* [Zenodo Record 15069399](https://zenodo.org/records/15069399)  
* [Zenodo Record 15069479](https://zenodo.org/records/15069479)  
* [Zenodo Record 15069572](https://zenodo.org/records/15069572)  
* [Zenodo Record 15069438](https://zenodo.org/records/15069438)  
* [Zenodo Record 15069590](https://zenodo.org/records/15069590)  
* [Zenodo Record 15098044](https://zenodo.org/records/15098044)  
* [Zenodo Record 15099081](https://zenodo.org/records/15099081)  
* [Zenodo Record 15106995](https://zenodo.org/records/15106995)  
* [Zenodo Record 15106886](https://zenodo.org/records/15106886)  
* [Zenodo Record 15121962](https://zenodo.org/records/15121962)  
* [Zenodo Record 15127270](https://zenodo.org/records/15127270)  
* [Zenodo Record 15123307](https://zenodo.org/records/15123307)  
* [Zenodo Record 15107264](https://zenodo.org/records/15107264)

**Discussions:**

* [Validation of Recursive Expansive Dynamics](https://ask.igwn.org/t/validation-of-recursive-expansive-dynamics-reds-cmb-gravitational-wave-echoes-and-galactic-rotation-curves/1170)

**Computational Notebooks:**

* [Exceptional Lie Algebra Analysis](https://colab.research.google.com/github/JulianDelBel/Adelic/blob/main/Exceptional_Lie_Algebra_Analysis.ipynb)
