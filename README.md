# Soil Grain Size Prediction from Images

This project explores whether deep learning can predict cumulative soil grain size distributions from photographs.

The work is based on the Kaggle competition:

**Predicting Soil Grain Size Distributions from Images**

## Project Goals

This project has two objectives:

1. Develop and evaluate machine learning approaches for predicting grain size distributions from soil photographs.
2. Convert the resulting model into a usable AI product with a defined user workflow, requirements, system architecture, and deployed interface.

## ML Development

Planned areas of experimentation include:

- Baseline statistical models
- Transfer learning with pretrained CNNs
- Prediction of grain-size bins vs. cumulative distributions
- Image resolution
- Physical scale normalization using pixels-per-millimeter metadata
- Image augmentation
- Multi-image aggregation
- Alternative architectures
- Loss functions aligned with Earth Mover's Distance
- Model ensembles

## Product Development

After developing the predictive model, the project will explore:

- Photo upload workflow
- Automated image preprocessing
- Model inference
- Multi-photo analysis
- Prediction validation
- Result visualization
- Natural-language explanation
- Agentic workflow orchestration
- Product requirements
- System architecture

## Repository Structure

```text
data/          Competition data - not stored in GitHub
notebooks/     Exploration and experimentation notebooks
src/           Reusable Python code
models/        Trained model checkpoints - not stored in GitHub
submissions/   Kaggle submission files - not stored in GitHub
docs/          Requirements, architecture, and project documentation