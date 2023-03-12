Model Building Steps

  resources
    create .ipynb
    add lib
    add df
  
  eda
    des
    info
    na
    Visualiztion
    correlation(meatmap)
    find duplicate value
    find outlier
    rename column

  model building
    create normal model
    use samarry()
    build Simple Linear Regression with co-liner column
    Calculate VIF
    Subset Selection(.aic)

  MODEL VALIDATION TECHNIQUES
    Residual Analysis
      Q-Q plot(.resid)
    Residual plot of Homoscedasticity
      build scatter plot with fitted values and residuals
    Residual VS Regressor {c}
      for all column(R&D Spend,Administration,Marketing Spend)

  MODEL DELETION TECHNIQUES
    Cook's Distance
      Cook's distance plot
      Calculate cutoff
      Influence Plot
      drop influencer point
      reset the index
      create new model after droping influener point

  build final model