# 🚀 Adaptive Hybrid Parallel Web Health Monitoring System
# Introduction
In modern computing, systems are required to process large volumes of data efficiently. Traditional sequential programming is often insufficient for handling high workloads due to its linear execution model. Parallel programming addresses this limitation by enabling multiple operations to be executed simultaneously.
# 📌 Project Overview
This project is developed as part of a Parallel Programming assignment using Python. The system monitors the status of a large number of URLs and demonstrates the performance differences between:
   •Sequential Programming
   •Concurrent Programming (Threading)
   •Parallel Programming (Multiprocessing)
   •The application is designed with dynamic resource scalling, response time measurement and result classification, making it more advanced and efficient than basic URL checkers.
# 🎯 Objectives
   •  To implement sequential, concurrent and parallel programming techniques
   •	To process a large-scale dataset
   •	To compare execution performance between different approaches
   •	To demonstrate efficient workload distribution
   •	To analyze response time and classify results
# 🏗️ System Design
The system consists of the following components:
   • URL Generator: Generates 5000 test URLs
   • URL Loader: Reads URLs from a file
   • URL Checker: Sends HTTP requests and records responses
   •Execution Modules:
      •Sequential
      •Threading 
      • Multiprocessing
   •Performance Analyzer
# ▶️ How to Run
Step 1: Generate URLs
python generate_urls.py
This will create:
urls.txt
Example code:
Step 2: Run the Main Program
python main.py
Example code:
# 🖥️ Program Menu
===== URL STATUS CHECKER =====                                                                
1. Sequential                                                                                
2. Threading (Dynamic)                                                                       
3. Multiprocessing (Dynamic)                                                                   
4. Run All (Compare)
5. Exit
# 📊 Sample Output
# ⚡ Performance Analysis
# 🎥 Demonstration Video
# 🧩 Challenges Faced
Handling large datasets efficiently
Avoiding timeout errors
Optimizing thread and process usage
Ensuring fair performance comparison
# 💡 Conclusion
This project successfully demonstrates how parallel and concurrent programming significantly improve performance compared to sequential execution.
Dynamic scalling further enhances effieciency by adapting to workload size and system resources.

