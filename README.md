# ML Engineering Challenge
Design and implement a machine learning-based system architecture for VIN decoding. The system should be able to handle high volumes of VIN decoding requests and return decoded information such as make, model, year, body, and transmission types.

## Requirements
Specifically, the solution should include:
- A project to train the model with instructions on how to run it from the command line.
- A project containing an inference API that uses a trained model. The API can be local or cloud-based, but it should be easy for us to set up based on the provided instructions.
- A diagram of how the actual production system might look for such a service. We will discuss it during the interview.

Optionally, the solution may touch on (can be discussed instead of implemented):
- A database system to store decoded VIN information and enable fast queries
- A really simple monitoring and logging system to track system performance and identify issues

Additionally, write down your approach to the problem, the implementation process. Last, but not least, discuss any limitations or potential issues with the system and recommendations for future improvements.

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
- Code should be shared with [@jarutis](https://github.com/jarutis) as a collaborator on a private repository when it is ready for a review
- Any explanations should be written either in README.md, within the code as comments or a jupyter notebook. 
