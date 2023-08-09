# aws-online-checkout-workflow-terraform
├── main.tf
├── modules
│   ├── api-gateway
│   │   ├── main.tf
│   │   ├── outputs.tf
│   │   └── variables.tf
│   ├── dynamodb
│   │   ├── main.tf
│   │   ├── outputs.tf
│   │   └── variables.tf
│   ├── event-source
│   │   ├── main.tf
│   │   ├── outputs.tf
│   │   └── variables.tf
│   ├── lambda
│   │   ├── main.tf
│   │   ├── outputs.tf
│   │   └── variables.tf
│   ├── lambda-layer
│   │   ├── main.tf
│   │   ├── outputs.tf
│   │   └── variables.tf
│   ├── sns
│   │   ├── main.tf
│   │   ├── outputs.tf
│   │   └── variables.tf
│   ├── sqs
│   │   ├── main.tf
│   │   ├── outputs.tf
│   │   └── variables.tf
│   └── step-function
│       ├── main.tf
│       ├── outputs.tf
│       └── variables.tf
├── outputs.tf
├── src
│   ├── create_order
│   │   ├── lambda.zip
│   │   └── lambda_function.py
│   ├── handle_orders_comms
│   │   ├── lambda.zip
│   │   └── lambda_function.py
│   ├── handle_orders_shipment
│   │   ├── lambda.zip
│   │   └── lambda_function.py
│   ├── layers
│   │   └── python_checkout.zip
│   ├── process_payment
│   │   ├── lambda.zip
│   │   └── lambda_function.py
│   ├── rest-api
│   │   └── open-api.yaml
│   ├── revert_payment
│   │   ├── lambda.zip
│   │   └── lambda_function.py
│   ├── update_inventory
│   │   ├── lambda.zip
│   │   └── lambda_function.py
│   └── update_order
│       ├── lambda.zip
│       └── lambda_function.py
├── statemachines
│   └── statemachine.asl.json
├── terraform.tfstate
├── terraform.tfstate.backup
└── variables.tf
