## AWS SSM

AWS Systems Manager Agent (SSM Agent) is Amazon software that runs on Amazon Elastic Compute Cloud (Amazon EC2) instances, edge devices, on-premises servers, and virtual machines (VMs). SSM Agent makes it possible for Systems Manager to update, manage, and configure these resources.


## python poetry 



## project/app/api folder structure ?
billing-subscription$ tree -a
.
└── lambdas
    └── api
        ├── Makefile
        ├── poetry.lock
        ├── pyproject.toml
        ├── src
        │   ├── api_objects.py
        │   ├── app.py
        │   ├── .chalice
        │   │   └── config.json
        │   ├── context.py
        │   ├── endpoints.py
        │   ├── post_processors.py
        │   └── pre_processors.py
        └── tests
            ├── api
            │   └── test_billing_subscription_endpoints.py
            ├── conftest.py
            └── test-data
                └── tests-api-objects.sql

7 directories, 13 files
# here , billing_subscription is eg of an api .