---
layout: default
title: Warehouse Operation Performance and Errors
download: "/downloads/warehouse_operations.zip"
---

<div style="margin: 10px 0px 10px 0px;">
    <a class="download-btn" href="{{ page.download | relative_url }}" download>Download</a>
</div>
<div class="flex-container">
    <div class="flex-left" style = "overflow-y: scroll;">
        <embed  src="{{ '/assets/pdf/warehouse_operations_analysis.pdf' | relative_url }}" width="100%" height="600px">
    </div>
    <div class="flex-right">
        <h1>Warehouse Operations & Error Tracking Dashboard</h1>
        <p>
            I created a warehouse operations dataset using Python and turned it into a full Power BI dashboard. 
            The goal is to understand where time is being wasted, which zones slow people down, and what causes errors during daily tasks.
        </p>
        <h2>1. Task Duration (Travel vs Handle Time)</h2>
        <p>
            Every task has two parts: getting to the location (travel time) and doing the work there (handle time).  
            The dashboard shows which zones take longer and what factors affect speed such as equipment, task type, or workload.
        </p>
        <h2>2. Zone Traffic</h2>
        <p>
            This shows how busy each zone is and helps identify areas that may cause slowdowns because of congestion or long walking distance.
        </p>
        <h2>3. Equipment & Shift Performance</h2>
        <p>
            Tasks are broken down by equipment used and by shift (day, swing, night) to see when the warehouse is most efficient and where improvements are needed.
        </p>
        <h2>4. Line Count & Task Mix</h2>
        <p>
            Shows how many lines each task has and the overall task distribution (pick, putaway, cycle count, replenishment).  
            This helps understand workload complexity.
        </p>
        <h2>5. Error Tracking</h2>
        <p>
            The error dashboard shows the total errors, the type of errors, and where they happened.  
            This helps spot problem zones, items, or employees so the warehouse can reduce mistakes and rework.
        </p>
        <h2>6. Drilldown for Details</h2>
        <p>
            A detailed view shows each task with errors, including task type, zone, employee, and error type, making it easier to investigate issues.
        </p>
        <h2>7. Main Goal</h2>
        <p>
            The overall goal of this dashboard is to highlight bottlenecks, reduce labor waste, and give the warehouse a clear view of how daily operations perform.
        </p>
    </div>
</div>
