# 48-PoL-FIVR

This repository provides supporting design and measurement artifacts for the ISSCC 2027 paper on the multilevel quad-path (MLQP) FIVR.

The released files include measured efficiency data, node-waveform data, steady-state and transient waveforms, and a simulation model associated with the proposed converter.

## Repository Contents

### `efficiency_sweep.xlsx`

Measured efficiency-sweep data of the MLQP converter.

The spreadsheet contains efficiency measurements under different output-current and output-voltage conditions.

Included output-voltage conditions:

- VO = 1.0 V
- VO = 1.2 V
- VO = 1.8 V

The data can be used to reproduce the efficiency-versus-load characteristics reported in the paper.

---

### `point_csv.zip`

CSV data for the converter node waveforms.

The archive contains waveform data of the relevant switching and internal circuit nodes used to characterize the operating states and multilevel operation of the MLQP converter.

The CSV files can be imported into MATLAB, Python, Origin, or other numerical-analysis software for waveform visualization and further analysis.

---

### `wave.zip`

Steady-state and transient waveform data.

The archive includes:

- Steady-state operating waveforms
- Load-transient waveforms

The steady-state data characterize the converter switching behavior under nominal operation.

The transient data include the measured converter response during load-step events and can be used to reproduce the corresponding transient-response plots reported in the paper.

---

### `simulationmodel`

Simulation model of the proposed MLQP converter.

The model is provided to facilitate analysis and reproduction of the converter operating principles and key behaviors described in the paper.

---

## Data Usage

The numerical waveform data can be processed using commonly available tools such as:

- MATLAB
- Python
- Origin
- Microsoft Excel

For CSV waveform files, the first row or file naming convention identifies the corresponding waveform or circuit node where applicable.

## Notes

The released artifacts are intended to support reproduction of the key experimental and simulation results presented in the paper.

Technology-specific proprietary information, including foundry PDK files and other process-confidential design data, is not included in this repository.

## Contact

For questions regarding the released artifacts, please contact the corresponding author of the paper.
