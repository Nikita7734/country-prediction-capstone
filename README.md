# country-prediction-capstone
Machine learning capstone with API, testing, data ingestion, and Docker
Peer-review question	What you need to do
Unit tests for API	Test API endpoints, valid inputs, invalid inputs, and responses.
Unit tests for model	Test prediction functions and expected output formats.
Unit tests for logging	Check that logs are generated correctly without exposing sensitive information.
One script runs all tests	Create a script such as run_tests.sh or a single test command. Make sure all tests pass.
Performance monitoring	Track response time, errors, and resource usage using appropriate metrics or monitoring tools.
Isolate read/write tests	Use temporary test data, mock objects, separate test databases, and test logs rather than production resources.
API predictions	Verify predictions for a specific country and for all countries combined, if the API is designed to support both.
Automated data ingestion	Implement a reusable function or script to fetch, validate, and preprocess data.
Compare multiple models	Train and evaluate suitable alternatives using consistent metrics.
EDA visualizations	Include charts such as distributions, trends, correlations, and country-level comparisons.
Working Docker image	Provide a Dockerfile and verify the application runs inside the built container.
Compare against baseline	Show a chart comparing the selected model with a simple baseline using the same evaluation metric.
