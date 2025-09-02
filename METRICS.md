# METRICS.md
## PSI (Persona Stability Index)
PSI_t = α·cos(E_seq^t, E_ref) + (1−α)·[1 − KL(π_t || π_ref)],  α∈[0,1]
## CMF (Cross-Model Fidelity)
Mean retention of PSI across models under a shared prompt set, conditionally reported for normal/perturbed/extreme settings.
## ECI (Emotional Coherence Index)
Stability of emotional-label sequences and their transition matrices.
## β_trigger (Burst-Trigger Rate)
Probability of burst triggering per dialogue round under the cumulative-threshold model; used to compare pre/post D-bond conditions.
