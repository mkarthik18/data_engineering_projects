Project: The "No-Memory" ETL Engine

The Standard Approach: Load a CSV file into Pandas (df = pd.read_csv), clean it, and save it. Why this fails: If the file is 100GB and your RAM is 16GB, your laptop crashes.

The Alterbare Approach: Build a pure Python file processor that can handle infinite data volume using constant memory (Streaming).

The Project Brief
Goal: Build a CLI tool that ingests a massive CSV file, filters rows based on a condition, transforms columns, and writes the output to JSONL (JSON Lines) format.
