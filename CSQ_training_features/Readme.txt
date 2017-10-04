
f_mQ: CSQ training features (all features)
bin: edge vector for histograms
True_labels: 1 = true occupancy, 0 = false occupancy

Folder Bayesian: contains the alpha/beta parameters used for classification
alpha_1: hyperparameters for Dirichlet prior (body occupancy) (NOTE THAT alpha_0 is uniform - not included). 
beta_1: hyperparameters for Dirichlet (body occupancy) 
beta_0: hyperparameters for Dirichlet (empty environment) 
Q: vector of quantized attenuations 
v_0: CSQ deviations (excess attenuations) for empty environment 
v_1: CSQ deviations (excess attenuations) for occupied environment 
v_sim_1: CSQ simulated deviations for occupied environment (xt_nom,yt_nom): nominal simulated position of the subject
