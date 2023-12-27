# Web Application/System

> This project is part of the practices given in the "Web Applications/Web Systems" subject.
> 
> **Authors**: Almudena Gómez-Sancha, Luis Egui, Notkero Gómez, Óscar Otero, Patricia Plata, Iván Hernández.
>
> EasyRent is a business dedicated to online car rental. We do not require a physical office, so all interactions with customers will be through the website. EasyRent will allow customers to search for cars according to the location they want for a certain number of days, months, or hours. In addition, customers can configure the delivery and return of the vehicle at specific locations, without the need for them to coincide or simply by leaving the car parked on the street, within permitted limits, and closing the rental from their mobile phone. Regarding the selection of the vehicle, EasyRent allows filtering by vehicle model, fuel type, category, gearbox, number of seats, or accessories 

## How to Collaborate

#### Requirements:

It is necessary to use [pre-commit](https://github.com/pre-commit/pre-commit) for the use of the code formatting tool [Prettier](https://prettier.io/) before commits.

#### Installation:

1. Install `pre-commit`

- To do this, it is necessary to have [pip](https://pypi.org/project/pip/) installed 
- Linux: `pip install pre-commit`

2. If it does not exist, create the .pre-commit-config.yaml file with the [Prettier](https://prettier.io/) configuration in the project's root directory (obtained from [here](https://prettier.io/docs/en/precommit.html)).
3. Located in the project directory (pointing to [this Github](https://github.com/Missionpage/sw-practices) repository), install the configuration described in the aforementioned file by executing: 

- `pre-commit install`

* If `pre-commit` has not been added to the environment variables (PATH), it can be added before running the previous command, or it can be executed as follows: `/home/<user>/.local/bin/pre-commit install`

#### Steps to Implement
1. Create a new branch with **main** as the base where you will have to upload everything you do.
2. When everything you wanted has been implemented in the new branch, create a **pull request** to the develop branch and in the description, put: "Closes #(issue number that was done)".
3. (Optional) Assign someone to review the PR.
4. Fill in all the other options provided: who took care of the code, which milestone it is, which project it corresponds to, etc.
