# Build a ML Workflow For Scones Unlimited On Amazon SageMaker

### Project Overview

In this project, my task was to build an image classification model capable of automatically detecting the type of vehicle delivery drivers use, allowing for efficient routing to the correct loading bay and orders. This optimization helps Scones Unlimited(A scone-delivery-focused logistics company) streamline its operations by assigning delivery professionals with bicycles to nearby orders and giving motorcyclists farther away orders.

As a Machine Learning Engineer, my goal was to create a scalable and reliable model. It was essential for the model to scale to meet demand and have safeguards in place to monitor and control for drift or degraded performance, especially when it becomes available to other teams on demand.

Throughout the project, I utilized AWS Sagemaker to build the image classification model distinguishing bicycles from motorcycles. I deployed the model, incorporated AWS Lambda functions to create supporting services, and employed AWS Step Functions to orchestrate the model and services into an event-driven application. By the project's conclusion, I had developed a portfolio-ready demo showcasing my ability to construct and compose scalable, ML-enabled AWS applications.

### Project Steps Overview
1. **Data staging**
2. **Model training and deployment**
3. **Lambdas and step function workflow**
4. **Testing and evaluation**
5. **Optional challenge**
6. **Cleanup cloud resources**
