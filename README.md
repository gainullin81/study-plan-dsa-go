Study Plan Checklist: English + DSA + Go/Protobuf + Systems Design
This file is your live checklist.
Mark items with [x] when done.
Organize your repo like this:

/
├─ plan.md                         ← this file (checklist)
├─ README.md                       ← short overview & progress badge
├─ leetcode/                       ← solutions by problem number
│   ├─ 0001-two-sum/
│   │   ├─ main.go
│   │   └─ README.md
│   └─ ...
├─ projects/                       ← weekly Go mini-projects
└─ system-design/                  ← case studies & diagrams
0. Habits
 Daily: 15–30 min English (reading, listening, writing).
 Daily: 3 LeetCode problems in Go (1 easy, 1 medium, 1 hard/review).
 Weekly: 1 Go mini-project (commit code + tests).
 Weekly: 1 Systems Design case (writeup + diagram).
1. English (ongoing)
 Read Grokking Algorithms (RU/EN) out loud and summarize in English.
 Read Algorithms (Sedgewick & Wayne) in EN/RU.
 Watch MIT/CS50/NeetCode lectures in English.
 Write README & comments in English.
 Weekly English summary of what was learned.
2. Data Structures & Algorithms (DSA)
Free path = LeetCode + NeetCode roadmap.

Arrays & Strings
 #1 Two Sum
 #121 Best Time to Buy and Sell Stock
 #238 Product of Array Except Self
 #53 Maximum Subarray
 #56 Merge Intervals
 #57 Insert Interval
 #125 Valid Palindrome
 #3 Longest Substring Without Repeating Characters
HashMap / Set
 #217 Contains Duplicate
 #242 Valid Anagram
 #49 Group Anagrams
 #347 Top K Frequent Elements
Stack & Queue
 #20 Valid Parentheses
 #155 Min Stack
 #232 Implement Queue using Stacks
 #739 Daily Temperatures
 #239 Sliding Window Maximum
Linked List
 #206 Reverse Linked List
 #21 Merge Two Sorted Lists
 #141 Linked List Cycle
 #143 Reorder List
 #2 Add Two Numbers
Trees
 #104 Maximum Depth of Binary Tree
 #100 Same Tree
 #572 Subtree of Another Tree
 #226 Invert Binary Tree
 #102 Binary Tree Level Order Traversal
 #98 Validate Binary Search Tree
 #235 Lowest Common Ancestor of a BST
 #297 Serialize and Deserialize Binary Tree
Graphs
 #200 Number of Islands
 #133 Clone Graph
 #417 Pacific Atlantic Water Flow
 #127 Word Ladder
 #207 Course Schedule
 #261 Graph Valid Tree (Explore)
 #994 Rotting Oranges
 #1091 Shortest Path in Binary Matrix
Dynamic Programming
 #70 Climbing Stairs
 #198 House Robber
 #322 Coin Change
 #300 Longest Increasing Subsequence
 #62 Unique Paths
 #139 Word Break
 #91 Decode Ways
 #152 Maximum Product Subarray
 #72 Edit Distance
 #10 Regular Expression Matching (challenge)
Heavy Milestones
 #42 Trapping Rain Water
 #215 Kth Largest Element in an Array
 #23 Merge K Sorted Lists
 #4 Median of Two Sorted Arrays
 #51 N-Queens
 #295 Find Median from Data Stream
3. Go + Protobuf – Weekly Mini‑Projects
Week 1 – CLI & Basics

 CLI calculator (add/sub/mul/div) + tests.
 CSV parser: read → compute stats → export JSON.
Week 2 – REST API

 REST API (users/items) with Go + Gin/Chi + PostgreSQL.
 Auth (JWT), rate limiting, graceful shutdown, Dockerfile.
Week 3 – gRPC + Protobuf

 Define .proto for chat/notification service; generate Go stubs.
 Implement unary + server streaming; add deadlines, retries.
 Load testing (vegeta/k6).
Week 4 – Microservice Patterns

 Store-service with caching (Redis).
 Add tracing (OpenTelemetry + Prometheus).
 Contract tests; document APIs (Buf/Swagger).
Stretch goals:

 Concurrency patterns: worker pool, fan-in/out, cancellation.
 Backpressure demo with channels.
4. Systems Design – Weekly Cases
Each case = system-design/<case>/README.md with requirements, APIs, DB schema, diagram.

 URL Shortener
 Twitter (timeline/fanout)
 Dropbox (file storage + metadata)
 WhatsApp (messaging, presence)
 Uber (matching + geo)
 Rate Limiter
 Notification System
Artifacts:

 Capacity estimates & SLOs
 API design (REST/gRPC)
 DB schema & indexing
 Caching & queues
 Failure scenarios
 Architecture diagram
5. Definition of Done
 Code compiles + tests pass.
 README: approach + complexity.
 Edge cases handled.
 Complexity analysis included (time/space).
 Linter clean (golangci-lint), CI passing.
