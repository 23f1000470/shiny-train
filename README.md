# Matrix Build with Artifacts (ef55641)

This repository demonstrates a GitHub Actions matrix build that uploads artifacts.

Contact: 23f1000470@ds.study.iitm.ac.in

Workflow:
- .github/workflows/matrix-build.yml — creates parallel matrix jobs for Node.js 14/16/18.
- Each job uploads an artifact named `build-ef55641-v<node>` (e.g. `build-ef55641-v14`).
