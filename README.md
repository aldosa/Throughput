# Throughput
A TCP/IP and UDP throughtput analyzer written in .NET

It is finally time to start writing this... A throughput analyzer with customizable mocks for analyzing networks. The goal is to write a utility that can help troubleshoot local networks. In addition to randomly generating packets and content I would like this program to have ways to mock port scans as well as diagnose selected errors, such as HTML error conditions, etc.

## Features

- The program will include a circular buffer to replay error triggers
- Can be integrated with traffic analyzers such as WireShark to investigate failure points
- Useful for IoT devices as well as full-fledged distributed networs

