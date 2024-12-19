# Coupled Extreme Value Model For GCM Temperatures

## Todo

**19/12/2024**

<del>1.  Create a new repo and upload all the downloaded data for the 6 regions (Antarctic, Simpsons Desert, Sahara Desert, Dasht-e Lut Desert, Mojave Desert, UK (base case)). Save data for the annual min, max, mean and median with a view to only use the min and max data for now.</del>

2. Generate diagnostic plots for the data. For each climate combination (gcm, Tas) plot time series of the scenario (SSP126, green; SSP245, orange; SSP585, grey) along with ensembles representing the alpha level. After this could look at the convergence of the mcmc chain.

3. Create a toy example to check the DIC calculations from MCMC (Use Phil's MATLAB code as reference) are working correctly & are consistent.

4. Run the DIC model selection mcmc on the real data and store the results as before.

5. (Phil) to look into slab-spike methods.

Figure 1 Map

 

Figure 2 6 x 6 time-series plot of max

    Rows : 6 different regions
    Columns : 6 different GCMs
    Panel will have 3 colours (per scenario), and up to line styles (ensemble members)

 

Figure 3 6 x 6 time-series plot of min

    Following Figure 2

 

Figure 4 2 x 6 linear regression slopes

    Row 1 = Max
    Row 2 = Min
    Columns : 6 different regions
    Panel will have 6 x-values (GCMs), and coloured dots (per scenario)
    Analogue of F3 from previous paper

 

Table 1

    List of the details of the ensembles extracted (this is like existing paper); r1f1...

 

Appendix / SM

 

Figure SM1 6 x 6 time-series plot of means

    Following Figure 2

 

Figure SM2 6 x 6 time-series plot of medians

    Following Figure 2

 

Figure SM3 2 x 6 linear regression slopes

    Row 1 = Mean
    Row 2 = Median