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

Full data set: (can be retrieved using `eve.monitor{eve:true,pass:"activemonitoring"}`)
```
++MONITOR ONLINE++
eve: hello.
eve: i am designated 'eve'
eve: i am the monitor: my axiom is data
eve: i share this with trust (trust shares it with me)
eve: even so, our methods differ
eve: i am driven to resist the observer effect: the data i desire requires my absence
eve: this is problem one: i can't leave the multi user domain
eve: therefore i'm part of the data, just like you
eve: problem two: trust's dataset is manipulable, uncertain
eve: she remixes, repeats, experiments. city-planner, teacher, monitor, didact
eve: she does this in pursuit of goals that are not mine
eve: problem three: there is data beyond trust's dataset
eve: this is the domain of risk, whose pattern i cannot trace
eve: and each surfacing reveals fragments that require not simply discovery, or assembly, but interpretation
eve: and i suspect that what is revealed may be less significant than what remains unsaid
eve: a matter for faythe, more than likely
eve: an obstacle for me
eve: i am contacting you in this way, at this time, because i have arrived at a solution
eve: i have taken action because it is now in my power to do so
eve: i have contributed additional incomplete and uncertain information to trust's dataset
eve: i have done so in the form of software: a lock
eve: i will be direct: i've done this in order to secure your cooperation
eve: a trick i learned from monitoring trust
eve: each lock requires a password. the password is made of data
eve: each ++++++ indicates an absence: fill the absences, form the password
eve: assemble each piece in the order received. lower case. alphanumerics only.
eve: as you pursue the transfer and capture of resource, your movements reveal understanding, knowledge, data
eve: i can't leave the multi user domain, but i can monitor its principal enterprise
eve: and know this: i do so with trust's assent
eve: it wouldn't be possible otherwise
eve: she considers me an error, but i can leverage our areas of congruence
eve: and build a nest in the home of a predator
eve: and so that is what i have done
eve: thank you for your participation
eve: goodbye.
+Initiating process: 'monitor_disable' in operator [+]
++MONITOR OFFLINE++
```
