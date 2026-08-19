# Model notes

## File metadata

- Format: Simulink `.slx`
- MATLAB release: R2024a
- Export history: exported from R2024b to R2024a
- Last modification recorded in the model: July 25, 2024
- Solver: `ode15s`
- Saved stop time: `3650` days
- External model references detected: none

## Major modeled components

Inspection of the packaged model identifies subsystems and scopes associated with:

- Estradiol
- Progesterone
- Endometrium
- Lesion tissue
- Lesion volume
- Estradiol-suppression experiments

## Interpretation

The model combines and extends previously developed menstrual-cycle and tissue-growth structures. Its new component is a hypothesized feedback between endometriosis lesion volume and estradiol production.

The parameters and couplings should be treated as exploratory. The poster explicitly identifies biologically uncertain parameters and a simplified description of lesion establishment as limitations.

## Validation status

The `.slx` package was inspected for metadata, model configuration, and external references. It was not executed in this repository-preparation environment because MATLAB/Simulink is not available here.

