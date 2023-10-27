# Serverlesspresso AWS Application

Welcome to the Serverlesspresso AWS application, a showcase of cutting-edge AWS services and event-driven architecture. Developed during the AWS and GOTO EDA Day in Nashville 2023, this application seamlessly handles coffee orders using QR codes, allowing patrons to place orders via their mobile phones. Here, we present an overview of two key components: the Serverlesspresso Order Processing Workflow and the Serverlesspresso Order Management State Machine.

## Serverlesspresso Order Processing Workflow

### Shop Status Check
- Ensures an optimal experience by determining if the coffee shop is open and ready to process orders.

### Order Capacity Management
- Efficiently manages order capacity to prevent overwhelming the coffee shop.

### Order Progress Tracking
- Tracks the entire order process, from initiation to fulfillment, ensuring smooth operations.

### Error and Timeout Handling
- Gracefully manages scenarios where customers or baristas fail to act, maintaining system responsiveness.

### Event Notifications
- Emits detailed events at each stage, facilitating integration with external systems and monitoring setups.

## Serverlesspresso Order Management State Machine

### Dynamic Order Decision Routing
- Routes order actions like making, completing, canceling, or unmaking orders based on input.

### Order Record Management
- Updates order records in DynamoDB to ensure data consistency with each action.

### Comprehensive Event Notifications
- Utilizes EventBridge to emit detailed events, keeping all system components informed about order processing.

### Robust Error Handling
- Leverages AWS Lambda and DynamoDB service integrations for reliability, featuring retries and effective error navigation.

This Serverlesspresso AWS application exemplifies the power of AWS services, including Step Functions, EventBridge, and DynamoDB, in creating a seamless and efficient event-driven architecture for coffee order management. Experience the future of coffee ordering with Serverlesspresso!
