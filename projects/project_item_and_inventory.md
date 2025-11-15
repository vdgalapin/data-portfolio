---
layout: default
title: Item Performance & Inventory Management
download: "/downloads/item_performance_and_management.zip"
---

<style>
.flex-container {
    display: flex;
    flex-direction: row;
    gap: 25px;
}

.flex-left, .flex-right {
    flex: 1;
}

@media(max-width: 900px) {
    .flex-container {
        flex-direction: column;
    }
}
</style>

<div class="flex-container">

<div class="flex-left">

<a class="download-btn" href="{{ page.download | relative_url }}" download>Download</a>

<br><br>

<embed src="{{ '/assets/pdf/sales_item_analysis.pdf' | relative_url }}" width="100%" height="600px">

</div>

<div class="flex-right">

<h1>Item Performance & Inventory Management System</h1>

<p>This system helps the warehouse understand which products are profitable, which ones sell fast, and which ones cause waste or extra cost.</p>

<h2>1. ABC Analysis (Sales Value Ranking)</h2>
<ul>
<li><b>A Items</b> – highest sales value</li>
<li><b>B Items</b> – medium value</li>
<li><b>C Items</b> – lowest value</li>
</ul>

<h2>2. FSN Analysis (Movement Speed)</h2>
<ul>
<li><b>F (Fast-Moving)</b> – sells often</li>
<li><b>S (Slow-Moving)</b> – sells sometimes</li>
<li><b>N (Non-Moving)</b> – rarely sells</li>
</ul>

<h2>3. Combined ABC × FSN</h2>
<ul>
<li><b>AF</b> – high value + fast selling</li>
<li><b>BS / CS</b> – slow-moving items that need attention</li>
<li><b>CN</b> – low value + not selling</li>
</ul>


</div>

</div>
