# Laboratory Work No. 4 — TPP

**Topic:** Development of Static and Dynamic Libraries. Implicit and Explicit Linking.

**Group:** FIT-3-17  
**Variant:** 8

## Team Members

**Student A — Duchinsky Vladyslav Stanislavovych**

Task: Regression Analysis.

Functions:
- linearRegression()
- predict()
- rSquared()
- residuals()

**Student B — Verhunenko Daniela Serhiivna**

Task: Anomaly Detection.

Functions:
- zScore()
- iqrOutliers()
- detectOutliers()
- anomalyRate()

## Technologies

- C++20
- CMake
- Microsoft Visual Studio
- Windows x64
- Static Libraries (.lib)
- Dynamic Libraries (.dll)

## Project Structure

### Student A — Regression Analysis

- `RegressionLib/` — library source code
- `App/` — local library test
- `RegressionSDK/` — library SDK package

### Student B — Anomaly Detection

- `AnomalyLib/` — library source code
- `AnomalyApp/` — local library test
- `AnomalySDK/` — library SDK package

### Partner Library Testing

Student A tests the AnomalySDK:

- `AnomalyImplicitClient/`
- `AnomalyExplicitClient/`

Student B tests the RegressionSDK:

- `ImplicitClient/`
- `ExplicitClient/`

## Testing Results

Both libraries were built and tested as static and dynamic libraries.

Regression Analysis:
- Slope: 3.00
- Intercept: 2.00
- Prediction: 20.00
- R-squared: 1.00

Anomaly Detection:
- Z-score: 2.45
- Anomaly rate: 0.14
- Outlier detected: 100

Both implicit and explicit DLL linking tests completed successfully.

## SDK Contracts

The SDK packages contain header files, import libraries, DLL files, and API documentation.

- `RegressionSDK/README.md`
- `AnomalySDK/README.md`

## Conclusion

The project demonstrates the creation and testing of static and dynamic C++ libraries, API contracts, and the use of implicit and explicit DLL linking.