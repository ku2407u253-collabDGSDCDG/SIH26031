## Problem Statement ID

26031

## Problem Statement Title

Quality assessment and grading of onions are often subjective and vary across procurement centers, resulting in disputes and inconsistencies.

## Description

Expected Solution: Develop an AI-based mobile application that:

- Uses image processing to assess onion quality.
- Identifies damaged, rotten, sprouted, or undersized onions.
- Estimates Grade A and URS percentages.
- Generates a digital quality report instantly.
- Reduces human bias and improves transparency.

## Organization

Ministry of Consumer Affairs, Food & Public Distribution

## Department

Department of Consumer Affairs (DoCA)

## Category

Software

## Theme

Smart Automation



## Idea Title

## Technical Approch

## FEASIBILITY AND VIABILITY

- Technically Feasible: The solution uses established technologies such as computer vision, deep learning, image processing, mobile application development, and cloud/backend services, making the proposed system technically achievable.

- Data Feasibility: A dedicated dataset of onion images can be created and annotated across different sizes, varieties, lighting conditions, orientations, and quality defects to train and validate the AI models.

- Cost Effective: The system primarily requires a smartphone camera and software infrastructure, minimizing the need for expensive specialized inspection equipment.

- Scalable: The architecture can support different AI models and can be improved continuously as more real-world inspection data becomes available.

- Real-Time Potential: Optimized AI models can provide rapid analysis of onion batches, making the system suitable for use at procurement centers where large quantities need to be inspected efficiently.

- User Friendly: A simple mobile interface allows inspectors to capture images, review AI-assisted results, and generate quality reports without requiring specialized technical knowledge.

- Reliable and Transparent: Confidence scores, detected defect images, batch statistics, and inspection records provide visual evidence and an auditable trail, helping reduce subjectivity and disputes.

- Standards-Based: The final grading decision will be derived from AI-extracted quality parameters and applicable official quality standards, rather than relying solely on an AI prediction.

- Future Viability: The platform can be extended to on-device AI, multilingual interfaces, real-time camera inspection, historical analytics, and integration with existing procurement and supply-chain systems.

Overall Viability

The proposed solution is feasible with currently available AI, computer-vision, mobile, and cloud technologies, while its modular architecture allows continuous improvement, cost-effective deployment, and large-scale adoption across onion procurement centers.

## IMPACT AND BENEFITS

- Reduces Human Subjectivity: Provides a standardized AI-assisted assessment process, reducing variations between inspectors and procurement centers.

- Improves Grading Accuracy: Uses image-based analysis to identify damaged, rotten, sprouted, abnormal, and undersized onions, enabling more consistent quality assessment.

- Faster Inspection: Automates the analysis of onion batches, reducing the time required for manual inspection and enabling quicker procurement decisions.

- Transparent Quality Assessment: Provides visual evidence, confidence scores, defect-wise statistics, and grading results, making the assessment easier to verify.

- Reduces Disputes: Digital inspection records and standardized grading can provide objective evidence during disagreements between farmers, suppliers, inspectors, and procurement centers.

- Instant Digital Reports: Automatically generates a quality report containing batch information, onion counts, defect percentages, and Grade A/URS percentages.

- Improves Farmer and Supplier Trust: A transparent assessment process can help create greater confidence in the fairness and consistency of procurement decisions.

- Scalable Across Procurement Centers: The mobile-based approach can be deployed across multiple locations without requiring expensive specialized inspection equipment.

- Creates Valuable Data: Historical inspection records can support quality trend analysis, model improvement, procurement planning, and supply-chain decision-making.

- Supports Food Quality and Reduces Waste: Early identification of rotten or damaged onions can help improve handling, sorting, and storage decisions, potentially reducing avoidable post-harvest losses.

Overall Impact

The solution aims to make onion quality assessment faster, more consistent, transparent, and data-driven while improving trust between farmers, suppliers, and procurement authorities.

## RESEARCH AND REFERENCES

Our proposed solution is supported by existing research in computer vision, machine learning, image processing, and automated agricultural grading. The research indicates that image-based systems can effectively measure onion size, detect defects, and automate quality classification.

Key Research Findings

- Machine Vision for Onion Grading: Previous research has demonstrated the use of machine vision for grading onions based on size, achieving high classification efficiency. This supports the feasibility of automated visual size assessment.

   # https://computers.stmjournals.com/index.php/JoIPPRP/article/view/111 #
   # https://agritech.tnau.ac.in/horticulture/horti_vegetables_bellaryonion.html # 

- Multimodal Onion Quality Inspection: Research has explored combining RGB, spectral, depth, and X-ray imaging to measure onion diameter, volume, density, and defects. The study reported successful classification of healthy and defective onions, demonstrating the potential of computer vision for non-destructive quality inspection.

  # https://www.sciencedirect.com/science/article/abs/pii/S0260877415002824  #

- Automated Size Grading: Research on onion grading machines shows that onion size is an important factor in commercial grading and can be measured using automated systems. ( for hardware the reference are as.)

  # https://www.sciencedirect.com/science/article/pii/S2211601X16000237/pdf?md5=57ab907d030ed0072018891d23e5e309&pid=1-s2.0-S2211601X16000237-main.pdf  #

- AI-Based Defect/Quality Assessment: Recent research has explored deep-learning-based approaches for automated onion quality classification and disease assessment, supporting the use of AI for reducing dependence on subjective visual inspection.

  # https://www.minicod.com/papers/vision-based-automation-system-for-onion-grading-using-robotic-arm-1ef035ee  #

  - Indian Onion Quality Standards: Government and agricultural organizations provide established standards and guidelines for onion quality, grading, sorting, procurement, and post-harvest handling. These standards can form the basis of the application's rule-based grading engine rather than allowing the AI model alone to determine the final grade.

    AGMARKNET — Commodity Profile on Onion
    # https://agmarknet.gov.in/commodity_profile_pdf/Post%20Harvest%20Profile%20of%20Onions%202023.pdf  #

    
