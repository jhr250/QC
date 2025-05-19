# QC
CSE 6990 Quantum Computing and Communications

Example Programs

Environment Used

WSL2 / Ubuntu – necessary to utilize Aer GPU in Windows
Conda environment using Python 3.11
Qiskit 1.2.0
Qiskit Aer GPU 0.15.1

During initial experiments, memory swapping was excessive and hindering performance. To address this issue, a .wslconfig file was created to override the defaults. The allocated physical
RAM was rasied to 96 GB for the Ubuntu environment and a 1 TB swap file was allocated on an NVMe SSD drive dedicated to temporary files. This enabled most of the experiements to
complete without crashing.
• memory=96GB
• processors=24
• swap=1024GB
• swapFile=E:
wsl-swap.vhdx
