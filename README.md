## Project: 2023_Oral_metageome_pilot
Pilot sequencing of oral samples microbiome. Explore basic stats.

- data: 2023-03-22
- anaisys made by: Kateryna Pantiukh
- main question: How many reads from oral microbiome samples need to be generated to be sufficient for different tasks?

Samples set: 32 samples
- 10 samples - health
- 10 samples - high adenoma risk 
- 10 samples - tumor (+ 1 sample from polip)
- 1 sample - negative control

Initialy it was generated in average 36 mln reads per sample (mediana)

After keeping only reads wich are not mapped to human genome (GRCh38), approximately 9,6% reads left (median = 3,3 mln reads)

![Ststs1](https://user-images.githubusercontent.com/15068419/226907124-ebf8b936-1bed-4ee0-a34b-13149c38dc39.png)

De observed quite wide distribution for Reads left percentage.
(from 1,6% to 96,6%). 

This made prediction for final reads number quite uncertant. 

![Ststs3](https://user-images.githubusercontent.com/15068419/226910308-2573ffe6-9590-44d9-b7d6-a875593467d7.png)

We dont see significant differences for Reads left percentage inbetween helthy, high risk and tumor samples.

The possible reasons for the level of Reads left percentage shoud be investigated.
It could be: eating status before sampling, for example.
