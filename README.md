# TESDA AI/ML Accelerator

**Data Science and AI Capacity Building for the TESDA ICT Office**

| | |
|---|---|
| **Duration** | Three (3) months (mid-September – late November 2026) |
| **Cohort** | 25 TESDA ICT Office personnel |
| **Proponents** | DepEd (E-CAIR), SEAMEO INNOTECH, TESDA |
| **Format** | Hands-on, project-based across three sessions |

---

## Notebooks

Each lab is guided: one idea per cell, exercises between `### START CODE HERE ###` and
`### END CODE HERE ###` with `assert`-based ✅ checks, ❓ question cells, and 🎛️ play-around
cells. Open a notebook in Colab with its badge; the first cell installs what it needs.

**Start here:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/00_Introduction.ipynb) **Introduction** – what the series builds, the datasets, and how the labs work.

**Commands primer:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_commands_primer.ipynb) **Commands primer** – a quick tour of the pandas and geopandas commands used across Day 1 and Day 2.

### Session 2 – Intermediate Applied Geospatial Analysis

From raw data to an analysis-ready, PSGC-aligned feature table, plus spatial feature engineering
and spatial statistics for the center-recommendation and gap-analysis models.

**Day 1 – Data integration & preprocessing**

| Topic | Open in Colab |
|-------|---------------|
| Data Sources (CSV, SQL, GeoJSON, SHP) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D1_00_data_sources.ipynb) |
| OSM Road Network | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D1_01_osm_road_network.ipynb) |
| Administrative Boundaries | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D1_02_admin_boundaries.ipynb) |
| Institutions and Coordinate Checks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D1_03_institutions_and_coordinate_audit.ipynb) |
| Point, Heat, and Density Maps | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D1_04_visualization.ipynb) |
| Advanced: Earth Engine, Raster to Table (Optional) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D1_05_advanced_gee.ipynb) |
| Centers on a Road Network and Program Access | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D1_06_linking_datasets.ipynb) |

**Day 2 – Spatial feature engineering & spatial statistics**

| Topic | Open in Colab |
|-------|---------------|
| Feature Table (One Row per Center) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D2_00_feature_table.ipynb) |
| Center Recommendation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D2_01_center_recommendation.ipynb) |
| Gap Analysis (Accessibility, 2SFCA, Moran's I) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D2_02_gap_analysis.ipynb) |
| Assessor Workload | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cair-philippines/tesda-ai-ml-accelerator/blob/main/notebooks/S2_D2_03_assessor_workload.ipynb) |

The Day 3 team activity notebooks are released as the course progresses.

---

## Quick Start

```bash
pip install -r requirements.txt
jupyter notebook
```

---

**Education Center for AI Research (E-CAIR)**
