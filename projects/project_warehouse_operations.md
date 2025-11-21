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
        <!-- <embed  src="{{ '/assets/pdf/warehouse_operations_analysis.pdf' | relative_url }}" width="100%" height="600px"> -->
        <iframe 
        src="{{ '/assets/pdf/warehouse_operations_analysis.pdf' | absolute_url }}" 
        style="width:100%; height:650px;" 
        frameborder="0">
        </iframe>

    </div>
    <div class="flex-right">
        <h2>Warehouse Operations & Error Tracking Dashboard</h2>
        <p>
            I created a warehouse operations dataset using Python and turned it into a full Power BI dashboard. 
            The goal is to understand where time is being wasted, which zones slow people down, and what causes errors during daily tasks.
        </p>
        <h3>1. Task Duration (Travel vs Handle Time)</h3>
        <p>
            Every task has two parts: getting to the location (travel time) and doing the work there (handle time).  
            The dashboard shows which zones take longer and what factors affect speed such as equipment, task type, or workload.
        </p>
        <h3>2. Zone Traffic</h3>
        <p>
            This shows how busy each zone is and helps identify areas that may cause slowdowns because of congestion or long walking distance.
        </p>
        <h3>3. Equipment & Shift Performance</h3>
        <p>
            Tasks are broken down by equipment used and by shift (day, swing, night) to see when the warehouse is most efficient and where improvements are needed.
        </p>
        <h3>4. Line Count & Task Mix</h3>
        <p>
            Shows how many lines each task has and the overall task distribution (pick, putaway, cycle count, replenishment).  
            This helps understand workload complexity.
        </p>
        <h3>5. Error Tracking</h3>
        <p>
            The error dashboard shows the total errors, the type of errors, and where they happened.  
            This helps spot problem zones, items, or employees so the warehouse can reduce mistakes and rework.
        </p>
        <h3>6. Drilldown for Details</h3>
        <p>
            A detailed view shows each task with errors, including task type, zone, employee, and error type, making it easier to investigate issues.
        </p>
        <h3>7. Main Goal</h3>
        <p>
            The overall goal of this dashboard is to highlight bottlenecks, reduce labor waste, and give the warehouse a clear view of how daily operations perform.
        </p>
    </div>
</div>
