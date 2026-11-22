# Note on this fork

**This is not original work of this account.** It is an unmodified copy (fork) of

> **[eduardcaballero/Risk_and_Time_Preferences_Tasks](https://github.com/eduardcaballero/Risk_and_Time_Preferences_Tasks)**
> — oTree code by **Eduard Caballero**.

The copy exists only so that working papers by Ferley Rincón can cite a stable, citable snapshot of
the code that was used in the field. All credit for the code belongs to its author. No file of the
original code and no commit of its history has been modified in this fork; the only file added is
this note.

## What the code is

A collection of oTree tasks used in experiments run in Colombia between 2020 and 2022:

| Apps | Task |
|---|---|
| `ctb`, `ctb_2`, `ctb_r` | Convex time budget (time preferences) |
| `mpl`, `mpl_2`, `hl` | Multiple price list and Holt–Laury (risk preferences) |
| `bret` | Bomb risk elicitation task |
| `dm`, `sgg` | Dictator game and social value tasks |
| `torneo`, `icl`, `tarea`, `results`, `resultados` | Tournament with mobility and productivity, including Felix Holzmeister's ICL task |
| `home`, `home_2` | Entry and consent |

The `icl` app is the **Imaginary Coin Letter (ICL) task of Felix Holzmeister**; credit for it
belongs to him, not to this account or to the fork's upstream author.

## Which papers use which part, and which version actually ran

- **Mobility and productivity in a dual labour market** (field work: 20–23 September and
  10–25 November 2021, 18 sessions). **This repository is where that experiment actually ran.** The
  field version is commit `ebe8e52` (10 November 2021). The copy in
  [ferleyrincon/tournament](https://github.com/ferleyrincon/tournament) matches that commit (it only
  drops a duplicated class and adds two unused templates), so `tournament` is the replication
  package and this repository holds the original history, including the intermediate versions used
  in sessions 1 to 6.
- **Time preferences (TP4)**. The current tip of this repository matches the **pilot of 16 December
  2020**, *not* the field version of August–September 2021. The August 2021 data contain
  `PCI1`/`PCI2`, `incorrect_attempts`, `tran1`–`tran5`, `prueba_pago` and the apps `pcd_bret` and
  `bret_ejemplo`, which exist in no commit of this repository. That field version has not been
  found.

<!-- TODO (Ferley): pedir a Eduard Caballero (o a MyDiaz) el código de agosto-septiembre de 2021 de
     las tareas de preferencias temporales, o buscarlo en el servidor de Heroku que se usó. -->

## Snapshot

Fork point: commit `ac4a784` ("borrar «contracts», «allocations»", 21 February 2022), the tip of the
original `master`.

## Where to report issues or send improvements

Open issues and pull requests in the original repository,
**https://github.com/eduardcaballero/Risk_and_Time_Preferences_Tasks**, not here.

## Licence

Whatever licence the original repository carries applies to all of its files. This note is the only
file added by this account and is released under the MIT licence.
