<h2>Initial Data Exploration</h2>

<p>
This project begins with an exploratory analysis of YouTube Analytics data from the
<strong>DarkBrickProductions</strong> channel. The goal of this initial step is to understand
how total watch time is distributed across different geographic regions.
</p>

<h3>Watch Time by Geography (Raw View)</h3>

<p>
The figure below displays total watch time (in hours) aggregated by geography using the
raw exported analytics data.
</p>

<img width="1734" height="894" alt="e02c3d81-fbfc-4db5-9d2a-831d505a1769" src="https://github.com/user-attachments/assets/33006ddc-75fc-48b5-b03b-5416404f2b51" />


<p>
This visualization highlights a key challenge in the raw data: a small number of categories
(notably the <em>United States</em> and the aggregate <em>Total</em> category) dominate overall
watch time. As a result, watch time values for other regions are compressed near zero,
making meaningful comparisons difficult.
</p>

<h3>Analytical Implications</h3>

<p>
Rather than treating this as a final result, this plot serves an important diagnostic purpose.
It reveals that the data contains highly imbalanced categories and aggregate values that
obscure regional patterns.
</p>

<p>
Based on this insight, subsequent steps in the analysis focus on:
</p>

<ul>
  <li>Removing aggregate categories (e.g., <em>Total</em>) that distort comparisons</li>
  <li>Focusing on the highest-contributing geographies</li>
  <li>Re-visualizing summarized metrics (means and variability) for improved interpretability</li>
</ul>

<p>
This iterative approach reflects standard exploratory data analysis (EDA) practice, where
early visualizations guide data cleaning, transformation, and refinement.
</p>
