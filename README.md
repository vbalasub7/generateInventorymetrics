# generateInventorymetrics
Generate Inventory Metrics workflows

The purpose of the lambda function (zip file found in the same location) is to populate Inventory minimum and maximum levels by Product, and Locations. The output is currently written to a S3 bucket (handle available within the function) which can redirected to your AWS Supply Chain S3 bucket.

NOTE: This lamdba funtion like others can be scheduled to run at a specific time window with recurring frequency using Amazon Eventbridge service.

Reference can be found:
https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-run-lambda-schedule.html
