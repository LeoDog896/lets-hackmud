# Locks

## EZ_21

paramater name: `ez_21`

Possible options: `unlock`, `release`, `open`

Example:

`some.lock { ez_21: "release" }`

## EZ_35

paramter names: `ez_35`, `digit`

Possible `ez_35` options: `unlock`, `release`, `open`

Possible `digit` options: Any number from `0-9`

Example:

`some.lock { ez_35: "unlock", digit: 5 }`

## DATA_CHECK

parameter name: `DATA_CHECK`

Input: `answer1answer2answer3`...

I have no clue where to get the data for this. It is genuinely confusing. 
