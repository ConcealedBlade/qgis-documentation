# Change Detection

## Overview

> The change detection function is located in the **Change Detection** tab, enabling detection and analysis of changes in remote sensing imagery.

![Interface](/change-detection.png)

## Operation Steps

1. **Select Comparison Images**
    - Two remote sensing image samples from different time periods must be selected
    - These represent the ground conditions before and after changes occurred

2. **Image Analysis**
    - The system employs the [**CTMTNet**](https://ieeexplore.ieee.org/document/10740028) model for change detection
    - Multiple result display methods are supported for intuitive understanding of ground feature changes
        - Images highlighting newly added objects
        - Corresponding change description text

<!-- tabs:start -->

#### **Image Results**

![Image Results](/change-detection_result.png)

#### **Text Results**

![Text Results](/change-detection_caption.png)

<!-- tabs:end -->

?> **Technical Note**: [**CTMTNet**](https://ieeexplore.ieee.org/document/10740028) is a CNN-Transformer-based multi-task network model that not only detects changes in remote sensing images but also automatically generates descriptive text of the changes.

!> Please ensure that the two input remote sensing images cover the same geographical area.