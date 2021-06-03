# Binary Statistics
A simple console application to perform binary statistics

Given a series of numbers as input, this application creates a running tally for each bit in the given numbers (in decimal), where +1 for one and -1 for zero.

Example 1:

buildStatistics(1); // 01
buildStatistics(2); // 10
result = 0,0

Example 2:

buildStatistics(1); // 01
buildStatistics(2); // 10
buildStatistics(3); // 11
buildStatistics(3); // 11
buildStatistics(3); // 11
result = -3, -3
