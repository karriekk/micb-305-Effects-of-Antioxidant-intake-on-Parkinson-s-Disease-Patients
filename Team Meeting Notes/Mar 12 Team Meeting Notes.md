## Data Analysis
- Aim 4
  - Use CLR, which accounts for very small changes to avoid losing small significant changes instead of only looking at large changes (a function under phyloseq package)
  - Example:
    - Taxa for now instead of functional pathways (for instance we have 5 taxa that we’ve identified as interesting --> use subset function to select just those columns --> pull out the OUT table from phyloseq and use pseudocount to add a fake number to everything to avoid mathematical impossibilities such as log0 and also to normalize things using the pseudo count) and then use the CLR function)
    - Steps:
      1. Use subset_taxa() to pull out strains of interest
      2. Extract ASV table from this subset
      3. Add pseudocount to avoid log0
      4. Calculate CLR using clr(asv_table) and then create compositional score by summing
      5. Merge with metadata to create final table of data
<img width="321" height="324" alt="Screenshot 2026-03-12 at 21 42 04" src="https://github.com/user-attachments/assets/f14527af-046d-425a-8556-aee80762b53f" />

lm(MoCA ~ DAI, data=df) - forget about the microbiome itself and just to see what comes out of it
lm(MoCA ~ hybrid_score, data=df) 
Spearman correlation matrices for intake score, MoCA, and microbial score
Consider about putting in co-variants 
<img width="258" height="125" alt="Screenshot 2026-03-12 at 21 42 29" src="https://github.com/user-attachments/assets/3ed5f46d-8b44-407f-a7ad-3f145b5e1168" />

- One person does alpha and beta diversity analysis is sufficient

## Final Manuscript
- Work on the discussion together because this is where we talk about the all the analyses and results to ensure that we're not missing anything and also because it involves the most research
- Look at the grading rubric to see how points are allocated (biggest sections are results, figures, and discussion; title is 3 marks - will include more general descriptions of our results)
- Data analysis should be done by Match 26th to have a comprehensive picture so that we can troubleshoot during next week's team meeting 
- Assign people to read over the writing to make it more cohesive (check spelling!!!)
- Can start working on the intro and method sections of the final manuscript right now
