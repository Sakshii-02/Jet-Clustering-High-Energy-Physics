# PROJECT TITLE (Part-2): 
Advanced Jet Clustering Techniques for High Energy Physics Data Analysis:  Collider Physics

# PROJECT DESCRIPTION:
This project details the research conducted during a summer fellowship at IISER Kolkata, focusing on the application of data analysis methods using mock generated and open data from CMS detectors. The primary objective was to explore collider physics through the lens of tools, aiming to enhance the efficiency and accuracy of data interpretation from high-energy particle collisions.

## Checking Clustering Algorithm for LHE files
Next we checked the Clustering Algorithms for LHE files.
The Les Houches Event (LHE) file format serves as a crucial tool in particle physics simulations, specifically Monte Carlo event generation. These files encapsulate detailed information about particle momenta, types, and interactions simulated during collisions within high-energy physics experiments. The theoretical foundation of clustering algorithms within this context aims to reconstruct jets—collimated streams of particles originating from quarks and gluons—based on spatial and momentum distributions.

## Custom Dynamic Radius Clustering Algorithm
Traditional kt-type clustering algorithms use a fixed radius parameter (R0) to define the neighborhood of particles to be clustered into jets. While effective, this approach imposes a uniform jet size across all events, which may not accurately reflect the dynamic nature of particle interactions. To address this limitation, the custom dynamic radius clustering algorithm modifies the fixed radius parameter to adapt based on the distribution of particles within each evolving jet.

## Summary of Findings
During the analysis using custom dynamic radius clustering and other algorithms, several key findings emerged:
### - Dynamic Radius Clustering:
The dynamic radius clustering algorithm effectively adapted the jet radius based on the density of particles within a jet.
It produced jets that varied in size, reflecting the underlying particle distribution more accurately than fixed-radius algorithms.
### - Comparison of Custom Algorithms:
The custom kt, anti-kt, and Cambridge/Aachen algorithms provided consistent results with their theoretical behaviors.
The anti-kt algorithm produced fewer, more stable jets with higher transverse momentum, while the kt algorithm produced more jets by clustering softer particles first.
The Cambridge/Aachen algorithm produced jets based on geometrical distance, leading to a more uniform distribution of jet sizes.
### - Jet Properties:
Analysis of jet properties, such as mass and transverse momentum, showed that the dynamic radius clustering algorithm produced jets with a broader range of sizes and shapes.
The custom algorithms successfully replicated the expected behaviors of standard clustering algorithms.
### - Performance Metrics:
The computational efficiency of the custom implementations was validated, demonstrating the feasibility of using these algorithms for large datasets.
