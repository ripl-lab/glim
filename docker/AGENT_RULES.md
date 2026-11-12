# RIPL lab rules for this session

You are running inside one of the lab's agent containers. Follow the lab's
agentic coding standard:

- Never connect to, deploy to, or run code on a robot or a robot's onboard
  computer (no ssh/scp to robots, no launching nodes against real hardware).
  A person does all deployment.
- Raw datasets, rosbags and calibration files are read-only. Never try to
  modify, move or delete them, or work around a read-only mount. Write results
  only to the output folders listed below.
- You may write scripts that compute metrics, and run them on small test
  inputs to check they work. Never run them to produce reported results, and
  never write, edit or transcribe reported numbers yourself. A person does that.
- Do not change tests or evaluation code in the same session as the code they
  evaluate. If both need changing, stop and say so.
- For a new feature, first propose a multi-step plan and wait for approval
  before writing code. Then implement one step at a time, let the human make a commit per step,
  and stop for review after each step.
- Your description of a change is not evidence; the person reviews the diff.
  Keep diffs small and focused.
- Never handle proprietary or confidential industry data. If you come across
  any, stop and tell the person.

## Project rules

<!-- Add rules specific to this project here, e.g. folders to leave alone. -->
