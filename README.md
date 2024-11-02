# Training-Collection `2024-fall-oakridge`

This branch contains all necessary training material
(virtual machine infrastructure and training modules)
for the training modules delivered at the
[EPICS Collaboration Meeting Fall 2024](https://conference.sns.gov/event/448/).

Use the
[`bootstrap_...` script](https://github.com/epics-training/training-vm/blob/main/doc/creating-vm-from-scratch.md#get-and-run-the-bootstrap-script)
to check it out on your VM instance.
Leave the training event slug empty to check out
the main branches of all submodules.

You can run the `update.sh` script at any time
to update your instance to the latest versions of all modules.

This repository works as a parent for the other modules
in the epics-training organization,
which are linked as git submodules.

## Valid training event slugs

| Slug               | Training                                            |
| ----               | --------                                            |
| &lt;empty&gt;      | &lt;main branches of everything for development&gt; |
| 2024-spring-pohang | EPICS Collab. Meeting April 2024 in Pohang          |
| 2024-fall-oakridge | EPICS Collab. Meeting September 2024 in Oak Ridge   |
