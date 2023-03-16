Model Building Steps {c}

  resources {cm:2023-03-14} {c}
    create .ipynb {cm:2023-03-14}
    add lib {cm:2023-03-14}
    add df {cm:2023-03-14}
  
  eda
    des {cm:2023-03-14}
    info {cm:2023-03-14}
    na {cm:2023-03-14}
    Visualiztion {cm:2023-03-15}
    correlation(meatmap) {cm:2023-03-16}
    find duplicate value {cm:2023-03-16}
    find outlier {cm:2023-03-16}
    rename column {cm:2023-03-16}

  model building
    create normal model {cm:2023-03-16}
    use samarry() {cm:2023-03-16}
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