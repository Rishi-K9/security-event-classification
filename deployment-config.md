
# Deployment Configuration

## Project Name
Security Event Classification

## Project Type
Static CSV dataset and documentation.

## Tools Used
- Google Sheets
- GitHub

## Deployment Method
The classified security event dataset is exported from Google Sheets as a CSV file and uploaded to a public GitHub repository.

## Deployment Steps
1. Prepare the synthetic event dataset in Google Sheets.
2. Review the classifications and reasons.
3. Export the dataset as CSV.
4. Upload the CSV file to GitHub.
5. Verify that the repository and dataset are accessible.

## Validation
- Confirm that all 12 events are present.
- Confirm that every event has a classification.
- Confirm that every event has a documented reason.
- Verify that the CSV file opens correctly.

## Rollback Plan
If an incorrect dataset is uploaded, restore the previous verified CSV version and commit the correction to GitHub.

## Limitations
This project publishes a static dataset. No live application or production service is deployed.
