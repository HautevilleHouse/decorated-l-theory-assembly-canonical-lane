# Decorated L-Theory Assembly via Decoration-Persistence
## Canonical Lane (defined term): the manifold-constrained local-to-global architecture (`DLA1-DLA8`)

**Author:** HautevilleHouse  
**Date:** March 13, 2026  
**Status:** Admissible-class theorem manuscript

---

## Abstract

This manuscript develops a canonical-lane closure architecture for the target problem: proving persistence of decorated assembly invariants through an admissible assembly closure architecture..

The proof program is organized as eight steps `DLA1-DLA8` with executable closure gates `DLA_G1`, `DLA_G2`, `DLA_G3`, `DLA_G4`, `DLA_G5`, `DLA_G6`, and `DLA_GM`.

## 1. Target Statement and Scope

### 1.1 Target statement

The target statement is: persistence of the decorated assembly package in the declared admissible class.

### 1.2 Local claim boundary

- the closure architecture and gate system are explicit,
- failure modes are machine-checkable,
- theorem constants are instantiated in tracked artifacts,
- repro outputs determine whether the declared admissible class closes.

## 2. Canonical Objects

Let `u_tau = (L_tau, A_tau, D_tau, N_tau, O_tau)` denote the admissible state of L-theoretic packets, assembly data, defect ledgers, normalization parameters, and endpoint observables.

Strict closure margin:

`M_DLA = min(kappa_assembly, sigma_decoration, kappa_compact, rho_rigidity, decoration_lock) - eps_coh`.

## 3. Closure Gates

- `DLA_G1`: `kappa_assembly`
- `DLA_G2`: `sigma_decoration`
- `DLA_G3`: `kappa_compact`
- `DLA_G4`: `rho_rigidity`
- `DLA_G5`: `decoration_lock`
- `DLA_G6`: `eps_coh`
- `DLA_GM`: final strict margin

## 4. Reproducibility

Run `bash repro/run_repro.sh` and inspect `repro/certificate_runtime.json`.
