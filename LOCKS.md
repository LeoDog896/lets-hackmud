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

## c001

parameter names: `c001`, `color_digit`

Values for `c001`:
- red
- orange
- yellow
- green
- lime
- blue
- cyan
- purple

`color_digit` is simply the length of `c001`, for example `yellow` is `6` and `lime` is `4`

## c002

parameter names: `c002`, `c002_compliment`

Values: (`c002` then `c002_compliment` or vice versa)
- purple <-> lime
- blue   <-> yellow
- cyan   <-> orange
- green  <-> red

## c003

parameter names: `c003`, `c003_triad_1`, `c003_triad_2`

Values:
- purple -> green  -> yellow
- blue   -> lime   -> orange
- cyan   -> yellow -> red
- green  -> orange -> purple
- lime   -> red    -> blue
- yellow -> purple -> cyan
- orange -> blue   -> green
- red    -> cyan   -> lime

## DATA_CHECK

parameter name: `DATA_CHECK`

Input: `answer1answer2answer3`...

I have no clue where to get the data for this. It is genuinely confusing. 
