---
layout: default
title: "Swatch Simulator"
---

## Reference Value

### Data Reference Note
The data provided is for reference only. Due to variations in knitters' tension and stitching patterns, the density of swatches may differ even when using the same yarn and needle size. Therefore, for hand knitting, it is recommended to first knit a swatch, wash and block it, then measure the actual density to determine the final number of stitches and rows for the project, avoiding deviations in the finished product size.

### I. Core Objective
From a programming perspective, implement a **grid-based knitting/crochet swatch simulator**, with the core goal of **mapping physical yarn parameters to visual grid parameters, where each stitch is mapped to a grid cell**.

#### Core Technical Workflow
```
Input Parameters (Yarn Diameter/Count/Ply, etc.) → Calculate Standard Gauge (Stitches/Rows per 10cm) → Convert to Grid Rows/Columns for 10cm Swatch → Adapt Grid Style to Knitting/Crochet Techniques → Render Grid on App
```

### II. Basic Data Standards
All calculation formulas are based on the following international/industry standards to ensure data accuracy:

| Standard Number         | Standard Name                                  | Core Application Scenario                          |
| :---------------------- | :--------------------------------------------- | :------------------------------------------------- |
| ISO 2314:2010           | Textiles - Determination of yarn count          | Conversion between yarn count, diameter, and length |
| ASTM D2253-19           | Standard Test Method for Mass Per Unit Area and Density of Knitted Fabrics | Benchmark for calculating gauge (stitches/rows)     |
| JIS L1096:2010          | Testing methods for woven and knitted fabrics   | Industry reference range for knitting/crochet gauge |
| IWTO (International Wool Textile Organization) Standards | Correlation between wool yarn diameter and ply | Correction of actual diameter based on ply count   |

### III. Gauge Calculation (ASTM D2253 Standard)
Gauge (stitches per 10cm) is the core of grid mapping, calculated based on **actual yarn diameter + craft type**, with reference to the density range specified in JIS L1096.

| Actual Yarn Diameter (mm) | Knitting Gauge (Stitches/10cm)       | Crochet Gauge (Stitches/10cm) | Knitting Rows/10cm | Crochet Rows/10cm |
| :------------------------ | :----------------------------------- | :---------------------------- | :----------------- | :---------------- |
| 0.2~0.3                   | 27~32 (Fine Yarn)                    | 25~30                         | 23~26              | 18~21             |
| 0.3~0.5                   | 21~26 (Medium-Fine Yarn)             | 20~25                         | 19~22              | 15~18             |
| 0.5~0.8                   | 16~20 (Worsted Yarn)                 | 15~20                         | 15~18              | 12~15             |
| 0.8~1.2                   | 12~15 (Bulky Yarn)                   | 10~15                         | 11~14              | 8~11              |
| >1.2                      | 7~11 (Super Bulky Yarn)              | 7~10                          | 7~10               | 5~8               |

**Example**: Actual yarn diameter 0.25mm (2-ply fine yarn) → Knitting gauge = 29 stitches/10cm → Knitting rows = 29 × 0.8 = 23.2 rows/10cm

#### 1. Core Definitions
Gauge = **Width Gauge (Stitches per 10cm)** / **Height Gauge (Rows per 10cm)** within the specified dimension (10cm)  
- Width Gauge: Number of stitches within 10cm width (determines the width of the finished product);  
- Height Gauge: Number of rows within 10cm height (determines the length of the finished product).

#### 2. Standard Test Procedures
ASTM D2253 requires "swatch knitting + standardized measurement" to ensure accuracy, with the following steps:
1. **Knit the Swatch**:  
   - Use the actual yarn and needles for the project to knit a swatch of at least 15cm×15cm (to avoid edge deformation affecting measurement);  
   - The stitch pattern must match the finished product (density varies significantly between different stitches such as stockinette stitch and brioche stitch).
2. **Steam Blocking (Critical Step)**:  
   - Steam iron the swatch according to the yarn material (wool/cotton/synthetic fiber) (steam only, no pressing or stretching);  
   - Measure after natural drying (unblocked swatches may shrink, leading to gauge calculation errors).
3. **Precise Measurement**:  
   - Horizontal: Measure 10cm in the central area of the swatch (avoiding 2-3cm from the edges) and count the number of stitches (fractional stitches are allowed, e.g., 18.5 stitches);  
   - Vertical: Measure 10cm in the same central area and count the number of rows;  
   - Repeat measurement 2-3 times and take the average (to improve accuracy).
4. **Calculate Results**:  
   Example: 18 stitches horizontally and 24 rows vertically within 10cm → Gauge is "18 stitches × 24 rows / 10cm".

### IV. Knitting vs. Crochet
Secondary stitch categories are uniformly identified by "Short/Medium/Long".

| Universal Stitch Grade | Knitting Correlation       | Crochet Correlation       | Core Density Feature       | Correction Factor |
|:-----------------------|:---------------------------|:--------------------------|:---------------------------|:-----------------|
| Short                  | Stockinette Stitch         | Single Crochet (SC)        | Most Compact (Baseline)    | 1.0              |
| Medium                 | Reverse Stockinette Stitch | Half Double Crochet (HDC)  | Moderately Loose           | 0.85             |
| Long                   | Brioche Stitch             | Double Crochet (DC)        | Extremely Loose            | 0.7              |
