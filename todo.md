Model Building Steps

  resources {c} {cm:2023-03-23}
    create .ipynb
    add lib
    add df
  
  eda {c}
    des
    info
    na
    Visualiztion
    correlation(meatmap)
    find duplicate value
    find outlier
    rename column

  model building {c}
    create normal model
    use samarry()
    build Simple Linear Regression with co-liner column
    Calculate VIF
    Subset Selection(.aic)

  MODEL VALIDATION TECHNIQUES {c}
    Residual Analysis
      Q-Q plot(.resid)
    Residual plot of Homoscedasticity
      build scatter plot with fitted values and residuals
    Residual VS Regressor {c}
      for all column(R&D Spend,Administration,Marketing Spend) {cm:2023-03-16}

  MODEL DELETION TECHNIQUES {c}
    Cook's Distance
      Cook's distance plot
      Calculate cutoff
      Influence Plot
      drop influencer point
      reset the index
      create new model after droping influener point

  build final model