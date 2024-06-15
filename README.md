# SAM Scheduler - Enhanced CFS Interactivity

SAM Scheduler is an enhancement to the Completely Fair Scheduler (CFS) used in Linux. By integrating an interactivity scoring mechanism inspired by the ULE scheduler, SAM aims to improve the interactivity and performance of both single-threaded and multi-threaded applications.

## Features

- **Interactivity Scoring Mechanism**: Inspired by ULE, this mechanism assigns scores to tasks based on their type of process, ensuring more responsive task scheduling.
- **Enhanced CFS**: Builds upon the existing Completely Fair Scheduler, adding a layer of scoring to better manage batch tasks.
- **Performance Optimization**: Designed to enhance the performance of single-threaded and multi-threaded applications through improved scheduling decisions.

## Benchmarking and Performance Evaluation

Extensive benchmarking was conducted to ensure that SAM Scheduler provides tangible improvements across various applications. These benchmarks focused on evaluating the scheduler's performance in both single-threaded and multi-threaded scenarios, providing valuable insights into performance optimization strategies.

### Benchmark Result Graphs

The following graphs illustrate the performance improvements achieved by SAM Scheduler compared to the standard CFS:

- **Relative performance of sam on UnixBench compared to CFS. The y-axis shows relative performance gain/drop**:
  
  ![Single-Threaded Performance](https://github.com/ManojN22/SAM-Enhancing-the-responsiveness-of-the-Linux-CFS-scheduler-C-/blob/main/performance%20(1).png)
  
- **Relative performance of sam on Phoronix compared to CFS. The y-axis shows relative performance gain/drop**:
  
  ![Multi-Threaded Performance](https://github.com/ManojN22/SAM-Enhancing-the-responsiveness-of-the-Linux-CFS-scheduler-C-/blob/main/performance2%20(1).png)
  
