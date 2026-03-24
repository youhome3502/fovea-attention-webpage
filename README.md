# Fovea Attention Research - Webpage

Interactive documentation for the Fovea Attention research project.

## Results

- **Best Model**: M14 RL (84.80% test accuracy)
- **Improvement**: +24.8% over ResNet baseline
- **Architecture**: Fovea-inspired visual perception with RL-based gaze control

## Contents

- `docs/` - GitHub Pages website (index.html)
- `vis/` - Visualizations and charts

## View

Visit: https://youhome3502.github.io/fovea-attention-webpage/

## Build

```bash
# Regenerate visualizations
cd fovea-attention
python visualize_all.py

# Copy to webpage repo
cp -r docs/ vis/ ../fovea-attention-webpage/
```
