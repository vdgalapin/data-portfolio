---
layout: default
title: Item Performance & Inventory Management
download: "/downloads/item_performance_and_management.zip"
---

<div style="margin: 10px 0px 10px 0px;">
    <a class="download-btn" href="{{ page.download | relative_url }}" download>Download</a>
</div>
<div class="flex-container">
    <div class="flex-left" style = "overflow-y: scroll;">
        <embed  src="{{ '/assets/pdf/sales_item_analysis.pdf' | relative_url }}" width="100%" height="600px">
    </div>
    <div class="flex-right">
        <h1>Item Performance & Inventory Management System</h1>
        <p>This system helps the warehouse understand which products are profitable, which ones sell fast, and which ones cause waste or extra cost.</p>
        <h2>1. ABC Analysis (Sales Value Ranking)</h2>
        <ul>
            <li>
                <b>A Items</b> – highest sales value
            </li>
            <li>
                <b>B Items</b> – medium value
            </li>
            <li>
                <b>C Items</b> – lowest value
            </li>
        </ul>
        <h2>2. FSN Analysis (Movement Speed)</h2>
        <ul>
            <li>
                <b>F (Fast-Moving)</b> – sells often
            </li>
            <li>
                <b>S (Slow-Moving)</b> – sells sometimes
            </li>
            <li>
                <b>N (Non-Moving)</b> – rarely sells
            </li>
        </ul>
        <h2>3. Combined ABC × FSN</h2>
        <ul>
            <li>
                <b>AF</b> – high value + fast selling
            </li>
            <li>
                <b>BS / CS</b> – slow-moving items that need attention
            </li>
            <li>
                <b>CN</b> – low value + not selling
            </li>
        </ul>                
        <h2>4. Reorder Analysis</h2>
        <ul>
            <li>
                <b>Order Now</b> – stock will run out soon
            </li>
            <li>
                <b>Monitor Stock</b> – stock decreasing
            </li>
            <li>
                <b>Sufficient Stock</b> – 15+ days inventory
            </li>
            <li>
                <b>No Need to Order</b> – fresh stock available
            </li>
            <li>
                <b>Error</b> – invalid or negative inventory
            </li>
        </ul>
        <h2>5. Over-Purchase Detection</h2>
        <ul>
            <li>
                <b>High Risk</b> – purchased far more than demand
            </li>
            <li>
                <b>Moderate Risk</b> – slightly over-purchased
            </li>
            <li>
                <b>Low Risk</b> – purchasing matches demand
            </li>
        </ul>
        <h2>6. Expiration Tracking</h2>
        <ul>
            <li>Valid</li>
            <li>Near Expiry</li>
            <li>Expired (Still in Stock)</li>
            <li>Sold Out</li>
        </ul>
        <h2>7. Catch-Weight Adjustment</h2>
        <ul>
            <li>If catch-weight = yes → quantity already in weight</li>
            <li>If catch-weight = no → convert cases × avg weight</li>
        </ul>
    </div>
</div>
