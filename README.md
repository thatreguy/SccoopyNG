# SccoopyNG
ScoopyNG — The VMware detection tool

ScoopyNG combines the detection tricks of Scoopy Doo and Jerry as well as some new techniques to determine if a current OS is running inside a VMware Virtual Machine (VM) or on a native system.

ScoopyNG is able to detect VMware even if "anti-detection-mechanisms" are deployed.


FAQ — Interpretation of results
Q: How do I know if it's indeed a VMware Virtual Machine?

A: If one or more of the test results state that VMware is detected.

Q: Do all the tests have to state that it's VMware?

A: No, it is sufficient that one test result says that VMware is detected.


Sample results
Sample 1: native, Windows Vista SP1 32bit, Intel(R) Core(TM)2 Duo CPU

Sample 2: VM, Windows Vista SP1 32bit, Intel(R) Core(TM)2 Duo CPU, VMware Workstation 6.0.4 build-93057, without anti-detection-mechanisms

Sample 3: VM, Windows Vista SP1 32bit, Intel(R) Core(TM)2 Duo CPU, VMware Workstation 6.0.4 build-93057, with anti-detection-mechanisms

Citations
The tool is cited in various academic journals (e.g. [here](https://scholar.google.de/scholar?q=scoopyng) or [here](https://scholar.google.de/scholar?q=trapkit.de/research/vmm)) and [books](https://www.google.com/search?tbm=bks&q=scoopyng)


