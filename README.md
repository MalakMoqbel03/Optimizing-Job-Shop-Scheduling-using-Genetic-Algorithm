# Optimizing-Job-Shop-Scheduling-using-Genetic-Algorithm
 Project #1: Optimizing Job Shop Scheduling in a Manufacturing Plant
using Genetic Algorithm
Due date: May, 11, 2024
Late submission: 20% per day.
Teams: This project is intended for teams of 2 students. You can work with students
from any section
Consider a manufacturing plant with several machines such as cutting machines,
drilling machines, and assembly stations. Each product requires a sequence of
operations on these machines. The scheduling problem here is to determine the optimal
sequence and timing for each product to minimize the overall production time or
maximize throughput while considering machine capacities and job dependencies. This
project aims to develop a genetic algorithm to optimize job shop scheduling in a
manufacturing plant setting.
Requirements:
- Implement a system for job shop scheduling using genetic algorithm. The system
takes as input a list of jobs and the number of available machines (Assume each
machine can run only one job at any moment). The job is defined as a sequence of
operations, where each operation is specified by a machine to perform this task
and the required processing time. The sequence of operations for a given task has
to be performed in order. Here is a sample of the input to the system
Job_1: M1[10] -> M2[5] -> M4[12]
Job_2: M2[7] -> M3[15] -> M1[8]
Here Job_1 must start at machine M1 and requires 10 time units to finish the
first phase, then it requires 5 time units at M2 and ends with 12 time units at
M4. Whereas Job_2 starts at M2 and needs 7 time units, and so on.
- To test the system, the user should be able to specify the number of machines and
the list of jobs with their operation sequences. You can use any format for the
input and you do not need to stick with the format presented in the previous
sample.
- The output of the system is a schedule for each machine that depicts the start
and end time for each process and to which job it belongs. You can use Gantt
Chart for this purpose
