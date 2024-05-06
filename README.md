# payment-spliter-atharv-gtb4cec
# Payment Splitter Contract

## Overview
The Payment Splitter Contract is a smart contract designed to facilitate the splitting of payments among a group of recipients. It allows the deployment of a contract that sets up a predefined group of recipients who will receive payments.

## Features
- **Initialization:** The contract can be initialized with a list of stakeholders to split the payments.
- **Payment Splitting:** It enables the splitting of an amount between the saved stakeholders.

## Error Handling
The contract defines a set of error codes to handle various scenarios:
- `AlreadyInitialized`: Indicates that the contract has already been initialized.
- `Conversion`: Represents errors related to conversion operations.
- `AdminKeyExpected`: Indicates that an admin key was expected but not found.
- `InvalidAmount`: Denotes that the amount to split is invalid.
- `NoStakeholders`: Indicates that no stakeholders were provided during initialization.
- `NotInitialized`: Denotes that the contract has not been initialized.
- `TokenKeyExpected`: Indicates that a token key was expected but not found.
- `PaymentSplitExpected`: Denotes that a payment split was expected but not found.

## Usage
### Initialization
To initialize the contract, use the `init` function providing the admin address, token address, and list of stakeholders.

### Splitting Payments
Once initialized, payments can be split among the stakeholders using the `split` function by specifying the amount to split.

## Testing
The contract includes test cases to ensure its functionality and error handling are working as expected.

## License
This project is licensed under the [insert license type] License.

## Contributors
- [Contributor 1](link-to-profile)
- [Contributor 2](link-to-profile)
- [Contributor 3](link-to-profile)

## Contact
For any inquiries or feedback, please contact [maintainer's name](maintainer's email).
