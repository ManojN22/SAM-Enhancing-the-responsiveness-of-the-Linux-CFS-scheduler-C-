# SAM Scheduler - Enhanced CFS Interactivity

SAM Scheduler is an innovative enhancement to the Completely Fair Scheduler (CFS) used in Linux. By integrating an interactivity scoring mechanism inspired by the ULE scheduler, SAM aims to improve the interactivity and performance of both single-threaded and multi-threaded applications.

## Features

- **Interactivity Scoring Mechanism**: Inspired by ULE, this mechanism assigns scores to tasks based on their type of process, ensuring more responsive task scheduling.
- **Enhanced CFS**: Builds upon the existing Completely Fair Scheduler, adding a layer of intelligence to better manage interactive tasks.
- **Performance Optimization**: Designed to enhance the performance of single-threaded and multi-threaded applications through improved scheduling decisions.

## Benchmarking and Performance Evaluation

To ensure SAM Scheduler provides tangible improvements on most of application when benchmarks were conducted. These benchmarks focused on evaluating the scheduler's performance in both single-threaded and multi-threaded scenarios, providing insights into performance optimization strategies.

### Benchmark Results

1. **Single-Threaded Applications**:
   - Improved responsiveness and reduced latency.
   - Enhanced user experience through better interactivity management.

2. **Multi-Threaded Applications**:
   - More efficient CPU utilization.
   - Balanced workload distribution, leading to improved throughput.

