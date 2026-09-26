C3NeF Functional Assay Analysis

Functional Analysis of C3 Nephritic Factor Using Synthetic Hemolytic Assay Data

 Overview

C3 nephritic factor (C3NeF) is an autoantibody associated with dysregulation of the alternative complement pathway. C3NeF can stabilize the alternative-pathway C3 convertase, prolonging its activity and potentially contributing to persistent complement activation.

This project demonstrates a reproducible Python workflow for analyzing **functional C3NeF assay data** using synthetic hemolytic measurements.

The analysis focuses on quantifying the persistence of complement-mediated hemolytic activity over time and comparing functional activity between synthetic C3NeF-positive and C3NeF-negative samples.

Important: All data in this repository are synthetic and created for educational and portfolio purposes. They are not patient data or real laboratory results.


Scientific Background

The alternative complement pathway involves formation of the C3 convertase, **C3bBb**.

C3NeF can bind to and stabilize the alternative-pathway C3 convertase, reducing its normal decay and thereby prolonging complement activity.

A functional C3NeF assay can therefore evaluate the ability of a sample to maintain complement-mediated activity over a defined period.

In a hemolytic assay format:

Alternative pathway activation
            │
            ▼
      C3 convertase
         (C3bBb)
            │
            │
      C3NeF stabilization
            │
            ▼
 Prolonged convertase activity
            │
            ▼
      Complement activation
            │
            ▼
       RBC hemolysis
            │
            ▼
   Measurable hemolytic signal
