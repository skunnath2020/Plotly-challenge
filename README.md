# Belly Button Biodiversity
Plot.ly assignment <br>


![Bacteria by wiki](images/bacteria_ec.jpg)

This assignment, creates an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The most common bacteria found in the Belly-Button of participants in this study were:<br> 
         * Staphylococcus<br>
         * Corynebacterium<br>
         * Streptococcus<br>
         * Pseudomonas<br>
         * Prevotella

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Step 1: Plotly

1. Use the D3 library to read in `samples.json`.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use `sample_values` as the values for the bar chart.

* Use `otu_ids` as the labels for the bar chart.

* Use `otu_labels` as the hovertext for the chart.

  ![bar Chart](images/hw01.PNG)
3. Create a bubble chart that displays each sample.

* Use `otu_ids` for the x values.

* Use `sample_values` for the y values.

* Use `sample_values` for the marker size.

* Use `otu_ids` for the marker colors.

* Use `otu_labels` for the text values.
 
![Bubble Chart](images/bubble_charts1443.PNG)

4. Display the sample metadata, i.e., an individual's demographic information.<br>

![demographics](images/hw03.png)

5. Display each key-value pair from the metadata JSON object somewhere on the page.
Using the drop-down, OTU's can be selected that display the charts corresponding to the selected OTU.<br>

![dropdown](images/dropdown.PNG)

