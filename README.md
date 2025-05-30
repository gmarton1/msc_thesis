Abstract:

  In financial markets, accurate estimation of systematic risk is essential for in-formed decision-making and portfolio construction. A key measure of such risk is the beta coefficient, traditionally estimated using Ordinary Least Squares (OLS) regression over a rolling   window of past returns. However, OLS-based beta estimates are limited by their assumptions of linearity and temporal stability. This study compares two deep learning architectures—Long Short-Term Memory (LSTM) networks and Gated Recurrent Units (GRU)—to evaluate which more accurately approximates time-varying beta as calculated by the industry-standard OLS model. BP plc (formerly known as British Petroleum plc), a major UK-listed energy company, is used as a representative case study. A custom dataset is constructed by combining dai-ly financial market data with lower-frequency macroeconomic indicators. A 252-day rolling OLS regression serves as the benchmark method for estimat-ing beta, while LSTM and GRU models are trained on historical data to pre-dict out-of-sample beta values for 2024. Results show that the LSTM model most accurately approximates the benchmark OLS beta estimates, outper-forming the GRU model in aligning with this standard measure of systematic risk. This suggests that LSTM networks are especially effective at learning the underlying macro-financial patterns that drive systematic risk. The main contribution of this is an empirical benchmark that evaluates standard deep learning architectures against the prevailing OLS approach for beta estima-tion. It offers new evidence on the feasibility of using AI models to approx-imate market risk in a transparent, controlled setting. 
  
Raw data obained from:

  BP share price: https://bp.com/
  
  Brent oil futures: https://uk.investing.com/
  
  FTSE 100: https://uk.investing.com/
  
  GDP: https://www.ons.gov.uk/
  
  Inflation: https://www.ons.gov.uk/
  
  Interest rate: https://www.bankofengland.co.uk/
  
  UK 10 year bond yield: https://uk.investing.com/
  
  VIX: https://uk.investing.com/
