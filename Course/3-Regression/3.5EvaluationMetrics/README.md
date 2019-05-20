REGRESSION EVALUATION METRICS
	      							         ₙ
	MAE (Mean Absolute Error) 		=  1/n   Σ | yᵢ - ŷ |
		  								    ᶦ⁼¹
         							         ₙ
	MSE (Mean Square Error)			=  1/n   Σ (yᵢ - ŷ )²    =   1/n * RSS
										    ᶦ⁼¹
							
	RMSE (Root Mean Square Error)	=  √MSE

	  									ₙ
	RSS (Residual sum of squares)	=	Σ (yᵢ - ŷᵢ)²
									   ᶦ⁼¹

	  									ₙ
	TSS (Total sum of squares)		=	Σ (yᵢ - ȳ)²
									   ᶦ⁼¹

	   									ₙ
										Σ | yᵢ - ŷᵢ |			
									   ᶦ⁼¹		
	RAE (Relative Absolute Error)	=  --------------	
									    ₙ
										Σ | yᵢ - ȳ |			
									   ᶦ⁼¹	

	       								ₙ
										Σ (yᵢ - ŷᵢ)²			
									   ᶦ⁼¹						RSS
	RSE (Relative Square Error)		=  --------------    = 	  --------
									    ₙ						TSS
										Σ (yᵢ - ȳ)²
									   ᶦ⁼¹	
	
	R² Score  = (Variation(mean) - Variation(Fitted Line)) / Variation(mean) 
			  = (TSS  			 - RSS) 				   / TSS  
			  = 1 - RSS/TSS  
			  = 1 - RSE
	It represents how close the data values are to the fitted regression line.			
	R-squared values, like 0.73, can be translated into percentages by simply multiplying them by 100. An R-squared value of 0.73 means that there is a 73% reduction in variation around a fitted line compared to the mean. If R-squared was 1, then there would be a 100% reduction and if R-squared = 0, there would be a 0% reduction.


	                            ( n - 1 )
    Adj R²    = 1 - (1 - R²) -----------------
                              ( n - p - 1 )
