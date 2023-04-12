# ML Engineering Challenge
Design and implement a system architecture for VIN decoding using machine learning. The system should be able to handle high volumes of VIN decoding requests and return decoded information such as make, model, year, body and transmission types.

## Requirements
Specifically, the architecture should include:
- A microservice-based architecture
- A VIN decoding machine learning model integrated into the architecture, which can handle a high volume of requests and provide fast responses
- A service for model training

Optionally, the architecture may touch on (can be discussed instead of implemented):
- A database system to store decoded VIN information and enable fast queries
- An API gateway to manage and route requests to the appropriate services
- A really simple monitoring and logging system to track system performance and identify issues

Additionally, write down your approach to the problem, the implementation process, and the testing and deployment strategies. Last, but not least, discuss any limitations or potential issues with the system and recommendations for future improvements.

## Data
Data can be found [here](data/ml-engineer-challenge-redacted-data.csv)

## Data processing & normalisation
- The data is provided in a CSV file with the following columns:
    - `vin`: VIN number
    - `make`: Make of the vehicle
    - `model`: Model of the vehicle
    - `year`: Year of the vehicle (if available)
    - `body`: Body type of the vehicle (if available)

## Submitting work
- Code should be shared with [@smagu](https://github.com/smagu) as collaborator on private repository when it is ready for a review
- Any explanations should be written either in README.md or within the code as comments

## Hints and suggestions
- We are expecting a scalable system architecture, not a single script