# Topology Movement Mapping

This project analyzes urban movement patterns and spatial relationships in Seoul using data visualization techniques.

## Dataset Structure

- **movements**: Movement data between administrative districts (dong) of Seoul citizens downloaded from Seoul Open Data Plaza (Raw datasets are not uploaded to this repository due to their large file sizes. Only processed datasets are includ)
- **boundaries**: Administrative boundary data. Currently includes administrative districts (dong)
- **centers**: Urban centers designated in Seoul MasterPlan 2040 (2040 서울도시기본계획)

## Project Structure

```
├── datasets/
│   ├── movements/
│   │   ├── raw/
│   │   └── processed/
│   ├── boundaries/
│   │   └── neighborhood/
│   │       ├── raw/
│   │       └── processed/
│   └── centers/
│       ├── raw/
│       └── processed/
└── data-visualization/
    └── topology-movement-mapping/    # React + TypeScript Vite project
```
