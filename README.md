# Training-Collection

This repository works as a parent for the other modules
in the epics-training organization,
which are linked as git submodules.

For a given training course, it contains a branch
under the slug (short name) of that course.
Checking out this repository using that slug branch
will create all training modules for the training course
in the versions that were used at the event.

That check-out action
is intended to be run by the `bootstrap_...` script. See
https://github.com/epics-training/training-vm/blob/main/doc/creating-vm-from-scratch.md#get-and-run-the-bootstrap-script

## Valid training event slugs

| Slug               | Training                                          |
| ----               | --------                                          |
| 2024-spring-pohang | EPICS Collab. Meeting April 2024 in Pohang        |
| 2024-fall-oakridge | EPICS Collab. Meeting September 2024 in Oak Ridge |
