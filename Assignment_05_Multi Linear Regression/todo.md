50_startups

  resources {cm:2023-03-11} {c}
    create Q1_50_startups.ipynb {cm:2023-03-11}
    add lib {cm:2023-03-11}
    add df {cm:2023-03-11}
  
  eda {cm:2023-03-11} {c}
    des {cm:2023-03-11}
    info {cm:2023-03-11}
    na {cm:2023-03-11}
    Visualiztion {cm:2023-03-11}
    correlation(meatmap) {cm:2023-03-11}
    find duplicate value {cm:2023-03-11}
    find outlier {cm:2023-03-11}
    rename column {cm:2023-03-11}

  model building
    create normal model
    use samarry()
    build Simple Linear Regression with co-liner column
    Calculate VIF
    Subset Selection(.aic)

  MODEL VALIDATION TECHNIQUES {c}
    Residual Analysis {c}
      Q-Q plot(.resid)
    Residual plot of Homoscedasticity
      build scatter plot with fitted values and residuals
    Residual VS Regressor
      for all column(R&D Spend,Administration,Marketing Spend)

  MODEL DELETION TECHNIQUES {c}
    Cook's Distance {c}
      Cook's distance plot
      Calculate cutoff
      Influence Plot
    Influence Plot {c}
      drop influencer point
      reset the index
      create new model after droping influener point

  build final model