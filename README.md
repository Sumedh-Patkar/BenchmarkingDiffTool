# FACTs (Framework for Analysis and Comparison of Tests)

This project was developed during my Internship at Marvell Semiconductor (now known as [Marvell Technology Inc](https://www.marvell.com/))  
Although known as _BenchmarkingDiffTool_ in its initial days, this project was renamed to **FACTs**

![image](https://raw.githubusercontent.com/Sumedh-Patkar/BenchmarkingDiffTool/master/static/images/FACTs_Transparent.png)

## Brief Description

TODO: A brief description about the project

## Features
1. View Cloud and HPC Benchmark results
2. **Best of All Graph:** A graph of best results for each Processor SKU on the homepage
3. **For Marketing and Sales Team:** View Best Results for Each Benchmark for all Processor SKU families
4. **For Engineering Team:** View best results based on context specific CPU filters
5. Download graphs as CSV, PNG
6. Download *tailored* XSLX reports by applying 14 filters to a large database 

## Walkthrough

- TODO: Mention each page details, along with respective screenshots

## Technical Details

- TODO: Write details about backend, Database, frontend, data processing

### Fun Facts about FACTs
- I completely designed and developed the project, independently, from scratch
- We were facing bottlenecks in the database queries after the scale of our graphs increased
    - We tried parallely sending the queries using multiprocessor module in python
    - We tried processing 2D lists parallely, which improved the rendering performance for certain graphs (especially the heatmaps)
    - When parallel queries didn't work, we redesigned the queries which improved the performance by 25x 🚀🚀, which thrilled us 🤩
- One of the names that we considered for the project was BAPAT (Benchmarking And Performance Analysis Tool), an homage to Mr. Rahul Bapat in the benchmarking team!
- The UI went through several changes, transforming itself from very basic to nearly industry standard. The link to view the history of the UI will be published soon in another markdown.
