# Contribution Brief

The Contribution Brief is required reasoning, not required formatting. Public contributions should preserve its substance in the native style of the target surface.

Work through it before writing code for anything non-trivial: a fix, a feature, a specification or conformance change, a test vector. A typo or a one-line documentation fix does not need it.

## Fields

**Problem.** What is wrong or missing, in a sentence or two.

**Evidence.** What shows it: a file and line, a commit, a reproduction, a failing case.

**Consequence.** What goes wrong because of it. A false pass, an interoperability failure, an ambiguity, a security or governance gap.

**Smallest repair.** The minimum change that fixes that exact problem.

**Boundary.** What the change does not establish or solve.

**Validation.** What shows the repair works. Where it applies, also show the failure without it.

**Ownership.** Whether someone is already working on this, or owns the area.

## Workflow

Find the problem, write the brief, try to disprove it, implement, validate, then write the public text.

Read the actual source before claiming a defect or a fix. A report of a problem, including one from another agent or tool, is a lead to check against the source.

If the scope grows, update the brief before the code.

Keep the Boundary through to the public text. A pull request or comment should not claim more than the brief supports.

Check ownership before implementing. A correct fix in a lane someone else already owns still collides with their work.
