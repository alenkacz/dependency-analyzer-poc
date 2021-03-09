# Dependency Analyzer POC

Proof of concept for a Dependency Analyzing CLI for Kubernetes.

## Installation

1. Clone the project and run `go install` in the project directory to install the CLI.
2. Run `git clone https://github.com/kubernetes/kubernetes.git` and `cd` into the project directory.
3. Run `depcost analyzeDeps`.
4. You'll see the output in the `analysis.json` file.

## Design Doc

To see definitions of terms and future goals have a look at the [design document](https://docs.google.com/document/d/1HbHQ2IJa3eIyLFgB6agFdtp_DzAWRabUUkeqUxb0tn4/edit?usp=sharing).

## References

1. https://hackmd.io/@XYdYH0X5SYC3DUYFF5Wylg/rJimEo--u
2. https://medium.com/rungo/executing-shell-commands-script-files-and-executables-in-go-894814f1c0f7
3. https://www.geeksforgeeks.org/longest-path-in-a-directed-acyclic-graph-dynamic-programming/
