---
title: "FastNet: Machine Learning Weather Prediction"
excerpt: "Graph neural network models for global weather forecasting, developed with the Met Office"
collection: portfolio
---

As a Research Associate at the Alan Turing Institute, I work on [FastNet](https://www.turing.ac.uk/research/research-projects/fastnet), a machine learning weather prediction model developed jointly by the Turing and the [Met Office](https://www.metoffice.gov.uk) as part of the AI4NWP (Artificial Intelligence for Numerical Weather Prediction) programme. The project aims to transform UK weather forecasting by combining AI models with traditional physics-based forecasting. The model takes its name from the Fastnet sea area in the Shipping Forecast.

## Project Highlights

- **Global Forecasting with GNNs**: FastNet is a graph neural network (GNN) that produces global weather forecasts and is benchmarked against established numerical weather prediction methods.
- **Physical Consistency**: We design loss functions, including a spherical harmonic loss, horizontal gradient terms and improved wind representation, so that forecasts are not only accurate but also physically realistic.
- **Cross-Institution Collaboration**: The Turing leads AI model design and cloud scaling, while the Met Office contributes meteorological expertise and forecast evaluation metrics.
- **Next Steps**: Building on its global results, the project is moving towards high-resolution regional forecasts for the UK.

## Technical Details

- **Machine Learning Methods**: Graph neural networks, physics-informed loss design and spherical harmonic representations.
- **Data**: Trained on the ERA5 reanalysis dataset, which combines satellite, ship and surface observations.

## Publications

- [Technical overview and architecture of the FastNet Machine Learning weather prediction model, version 1.0](https://arxiv.org/abs/2509.17658) (arXiv, 2025)
- [FastNet: Improving the physical consistency of machine-learning weather prediction models through loss function design](https://arxiv.org/abs/2509.17601) (arXiv, 2025)
