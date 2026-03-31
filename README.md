# ICML2026 Rebuttal Supplementary Figures

This repository contains supplementary figures referenced in our rebuttal responses.

## Figures                                                                                                  
                                                                                                               
  ### Figure: ValTest_analysis_comparison.pdf                                                                  
  Description: Top-20 Rank Preservation. Fraction of configurations ranked in the top-20 by validation error   
  that are also in the top-20 by test error. Datasets where PBGI underperforms (red) have significantly lower  
  rank preservation (0–35%) compared to well-performing datasets (green), indicating that the best validation  
  configurations do not correspond to the best test configurations.                                            
                                                                                                               
  ### Figure: Rebuttal_ValVsTest_PoorDatasets.pdf                                                              
  Description: Cost-Adjusted Regret: Validation vs Test (λ=10⁻⁴). Comparison of stopping rule performance on   
  datasets with poor PBGI performance. Top row: validation-based regret shows PBGI/LogEIPC (orange) often      
  achieving near-hindsight-optimal performance. Bottom row: test-based regret shows PBGI/LogEIPC performing    
  substantially worse than hindsight, confirming that the validation signal does not transfer to test          
  performance on these datasets.                                                                               
                                                                                                               
  ### Figure: Rebuttal_WindowSize_AvgBarPlot_periodic.pdf                                                      
  Description: Effect of Polyak Window Size on Stopping Behavior (8D Periodic Cost, λ=0.01). Average stopping  
  time and cost-adjusted regret across 50 seeds for four acquisition functions (PBGI(0.01), LogEIPC, TS, LCB)  
  with window sizes [1, 5, 10, 20]. Shows how smoothing the stopping criterion affects the trade-off between   
  stopping time and regret.                                                                                    
                                                                                                               
  ### Figure: Rebuttal_WindowSize_AvgBarPlot_uniform.pdf                                                       
  Description: Effect of Polyak Window Size on Stopping Behavior (8D Uniform Cost, λ=0.01). Same analysis as   
  periodic cost. Note: For Thompson Sampling with larger windows (10, 20), the stopping rule never triggers    
  within 500 iterations for most seeds, resulting in stopping time = 499.                                      
                                                                                                               
  ### Figure: Rebuttal_WindowSize_AvgBarPlot_linear.pdf                                                        
  Description: Effect of Polyak Window Size on Stopping Behavior (8D Linear Cost, λ=0.01). Same analysis as    
  periodic cost. Demonstrates consistent patterns across different cost structures.                            
                                                                                                               
  ### Figure: Rebuttal_WindowSize_PBGI_001.pdf                                                                 
  Description: Single-Seed Visualization: PBGI(0.01) Acquisition with PBGI/LogEIPC Stopping (8D Periodic,      
  Seed=0). Four panels showing the effect of Polyak averaging (window sizes 1, 5, 10, 20) on the stopping      
  criterion. Each panel displays the raw and smoothed LogEIPC values, stopping threshold log(λ), stopping      
  iteration, and cost-adjusted regret at stopping.                                                             
                                                                                                               
  ### Figure: Rebuttal_WindowSize_LogEIPC.pdf                                                                  
  Description: Single-Seed Visualization: LogEIPC Acquisition with PBGI/LogEIPC Stopping (8D Periodic, Seed=0).
   Same format as PBGI figure, showing how LogEIPC sampling affects the stopping rule behavior across different
   window sizes.                                                                                               
                                                                                                               
  ### Figure: Rebuttal_WindowSize_TS.pdf                                                                       
  Description: Single-Seed Visualization: Thompson Sampling Acquisition with PBGI/LogEIPC Stopping (8D         
  Periodic, Seed=0). Same format as PBGI figure. Thompson Sampling exhibits higher variance in the stopping    
  criterion, demonstrating why larger smoothing windows may be beneficial.                                     
                                                                                                               
  ### Figure: Rebuttal_WindowSize_UCB.pdf                                                                      
  Description: Single-Seed Visualization: UCB Acquisition with PBGI/LogEIPC Stopping (8D Periodic, Seed=0).    
  Same format as PBGI figure. UCB shows rapid early stopping due to aggressive exploration leading to quick    
  convergence of the stopping criterion.


## Notes

- These figures are provided to support our responses to reviewer comments.
- Please refer to the rebuttal text for full context and discussion.
- All figures are best viewed at full resolution.
