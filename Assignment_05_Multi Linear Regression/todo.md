50_startups {c}

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

  model building {cm:2023-03-11} {c}
    create normal model {cm:2023-03-11}
    use samarry() {cm:2023-03-11}
    build Simple Linear Regression with co-liner column {cm:2023-03-11}
    Calculate VIF {cm:2023-03-11}
    Subset Selection(.aic) {cm:2023-03-11}

  MODEL VALIDATION TECHNIQUES {c} {cm:2023-03-13}
    Residual Analysis {cm:2023-03-12} {c}
      Q-Q plot(.resid) {cm:2023-03-12}
    Residual plot of Homoscedasticity {cm:2023-03-12} {c}
      build scatter plot with fitted values and residuals {cm:2023-03-12}
    Residual VS Regressor {cm:2023-03-12}
      for all column(R&D Spend,Administration,Marketing Spend) {cm:2023-03-12}

  MODEL DELETION TECHNIQUES {c} {cm:2023-03-13}
    Cook's Distance {cm:2023-03-13}
      Cook's distance plot {cm:2023-03-13}
      Calculate cutoff {cm:2023-03-13}
      Influence Plot
      drop influencer point
      reset the index
      create new model after droping influener point

  build final model {cm:2023-03-13}