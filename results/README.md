# Cluster Activation and Peak Ground Displacement CSV Files

This folder contains CSV files describing the timing of cluster activations and their associated peak ground displacement values.

## File contents

Each CSV file contains event-level information for one cluster or one analysis period.

Typical columns include:

| Column | Description |

|---|---|

| `time` | Time of cluster activation |

| `cluster_id` | Identifier of the activated cluster |

| `peak_ground_displacement` | Maximum ground displacement associated with the activation |

| `station` | Station name or code, if available |

| `component` | Seismic component, if available |

## Description

Each row corresponds to one detected cluster activation. The activation time indicates when the cluster was observed, while the peak ground displacement represents the maximum displacement measured during the corresponding signal window.

## Notes

- Time values should be interpreted in the timezone or reference system used during preprocessing.

- Peak ground displacement units should follow the processing convention used in the analysis, for example meters, millimeters, or counts if not converted.

- Missing values indicate unavailable or unreliable measurements.

## Usage
