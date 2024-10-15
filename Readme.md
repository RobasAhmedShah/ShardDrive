<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ShardDrive Project Proposal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f4f4f4;
        }
        h1, h2 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .emoji {
            font-size: 1.5em;
            margin-right: 10px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: left;
        }
        th {
            background-color: #3498db;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        .ascii-art {
            font-family: monospace;
            white-space: pre;
            background-color: #ecf0f1;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .section {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .team-member {
            display: inline-block;
            background-color: #3498db;
            color: white;
            padding: 5px 10px;
            margin: 5px;
            border-radius: 20px;
        }
        #toc {
            background-color: #ecf0f1;
            padding: 15px;
            border-radius: 5px;
        }
        #toc ul {
            list-style-type: none;
            padding-left: 20px;
        }
        #toc a {
            color: #2980b9;
            text-decoration: none;
        }
        #toc a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1><span class="emoji">📂</span> Project Proposal: ShardDrive</h1>
    
    <img src="https://github.com/RobasAhmedShah/ShardDrive/blob/main/logo.jpeg?raw=true" alt="logo" width="400">
    
    <div id="toc" class="section">
        <h2>Table of Contents</h2>
        <ul>
            <li><a href="#project-title">Project Title</a></li>
            <li><a href="#project-team">Project Team</a></li>
            <li><a href="#project-summary">Project Summary</a></li>
            <li><a href="#project-objectives">Project Objectives</a></li>
            <li><a href="#project-scope">Project Scope</a></li>
            <li><a href="#project-deliverables">Project Deliverables</a></li>
            <li><a href="#technical-components">Technical Components</a></li>
            <li><a href="#methodology">Methodology</a></li>
            <li><a href="#expected-outcomes">Expected Outcomes</a></li>
        </ul>
    </div>
    
    <div id="project-title" class="section">
        <h2><span class="emoji">🚀</span> Project Title</h2>
        <p>ShardDrive: A Distributed File Backup and Recovery System with Parallel Processing</p>
    </div>
    
    <div id="project-team" class="section">
        <h2><span class="emoji">👥</span> Project Team</h2>
        <p>Team Members:</p>
        <div class="team-member">Robas Ahmed Shah</div>
        <div class="team-member">Huzaifa Siraj</div>
    </div>
    
    <div id="project-summary" class="section">
        <h2><span class="emoji">📝</span> Project Summary</h2>
        <p>ShardDrive aims to revolutionize file backup and recovery by developing a distributed system using parallel processing techniques. It will efficiently handle large files by splitting them into smaller shards and distributing these across different nodes in a network.</p>
        <div class="ascii-art">
   📁 Large File
       |
   🔪 Sharding
       |
 🔀 Distribution
 /     |     \
💎    💎    💎
Shard1 Shard2 Shard3
        </div>
        <p>OpenMP will be utilized to parallelize the process of file sharding and recovery, enhancing performance by distributing work across multiple processors.</p>
    </div>
    
    <div id="project-objectives" class="section">
        <h2><span class="emoji">🎯</span> Project Objectives</h2>
        <ol>
            <li><span class="emoji">🏗️</span> Implement ShardDrive's distributed file storage system</li>
            <li><span class="emoji">⚡</span> Use parallel processing (OpenMP) for optimization</li>
            <li><span class="emoji">🔄</span> Enable redundancy and fault tolerance</li>
            <li><span class="emoji">🔐</span> Implement a robust shard recovery system</li>
            <li><span class="emoji">📈</span> Support scalability for growing storage needs</li>
        </ol>
    </div>
    
    <div id="project-scope" class="section">
        <h2><span class="emoji">🔍</span> Project Scope</h2>
        <p>ShardDrive's scope includes:</p>
        <table>
            <tr>
                <th>Feature</th>
                <th>Description</th>
            </tr>
            <tr>
                <td><span class="emoji">💎</span> File Sharding</td>
                <td>Split large files into smaller shards</td>
            </tr>
            <tr>
                <td><span class="emoji">⚡</span> Parallel Processing</td>
                <td>Use OpenMP for improved performance</td>
            </tr>
            <tr>
                <td><span class="emoji">🔄</span> Redundancy and Recovery</td>
                <td>Fault tolerance and data recovery</td>
            </tr>
            <tr>
                <td><span class="emoji">🌐</span> Networking</td>
                <td>Support for multiple ShardDrive nodes</td>
            </tr>
        </table>
    </div>
    
    <div id="project-deliverables" class="section">
        <h2><span class="emoji">📦</span> Project Deliverables</h2>
        <ol>
            <li><span class="emoji">🏗️</span> ShardDrive Distributed Backup System</li>
            <li><span class="emoji">🔄</span> Shard Recovery Mechanism</li>
            <li><span class="emoji">⚡</span> Parallel Processing Implementation</li>
            <li><span class="emoji">🛡️</span> Fault Tolerance and Redundancy</li>
            <li><span class="emoji">🌐</span> ShardDrive Network Support</li>
        </ol>
    </div>
    
    <div id="technical-components" class="section">
        <h2><span class="emoji">🔧</span> Technical Components</h2>
        <h3>OpenMP (Parallel Processing)</h3>
        <div class="ascii-art">
 ┌─────────────┐
 │  ShardDrive │
 │  ┌───┐ ┌───┐│
 │  │CPU│ │CPU││
 │  └───┘ └───┘│
 │  ┌───┐ ┌───┐│
 │  │CPU│ │CPU││
 │  └───┘ └───┘│
 └─────────────┘
        </div>
        <h3>ShardDrive Networking</h3>
        <div class="ascii-art">
    ┌───┐       ┌───┐
    │ A ├───────┤ B │
    └─┬─┘       └─┬─┘
      │           │
    ┌─┴─┐       ┌─┴─┐
    │ C ├───────┤ D │
    └───┘       └───┘
  ShardDrive Nodes
        </div>
        <h3>Shard Management</h3>
        <div class="ascii-art">
 ┌───────────┐
 │ Metadata  │
 ├───────────┤
 │ Shard 1   │
 │ Shard 2   │
 │ Shard 3   │
 │ ...       │
 └───────────┘
        </div>
    </div>
    
    <div id="methodology" class="section">
        <h2><span class="emoji">📊</span> Methodology</h2>
        <h3>1. Research and Design <span class="emoji">📚</span></h3>
        <ul>
            <li>Study existing distributed systems</li>
            <li>Design ShardDrive architecture</li>
        </ul>
        <h3>2. Implementation <span class="emoji">💻</span></h3>
        <ul>
            <li>Develop sharding module</li>
            <li>Implement OpenMP for parallel processing</li>
            <li>Build ShardDrive networking protocols</li>
            <li>Create shard redundancy mechanisms</li>
        </ul>
        <h3>3. Testing <span class="emoji">🧪</span></h3>
        <ul>
            <li>Large file handling in ShardDrive</li>
            <li>Failure scenario testing</li>
            <li>Performance evaluation</li>
            <li>Cross-node shard retrieval</li>
        </ul>
        <h3>4. Deployment <span class="emoji">🚀</span></h3>
        <ul>
            <li>Test ShardDrive network deployment</li>
            <li>Performance benchmarking</li>
        </ul>
    </div>
    
    <div id="expected-outcomes" class="section">
        <h2><span class="emoji">🏁</span> Expected Outcomes</h2>
        <ol>
            <li><span class="emoji">🏆</span> Functional ShardDrive backup and recovery system</li>
            <li><span class="emoji">🛡️</span> Fault-tolerant system with shard recovery</li>
            <li><span class="emoji">⚡</span> Improved sharding and recovery speed</li>
        </ol>
    </div>
    
    <hr>
    <p>This ShardDrive proposal can be expanded or refined based on the specific needs and requirements of the project as it progresses.</p>
    <img src="https://via.placeholder.com/800x100?text=Thank+You+For+Considering+ShardDrive" alt="ShardDrive Footer">
</body>
</html>
