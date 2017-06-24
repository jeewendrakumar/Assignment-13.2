What kind of logic can we apply in Relay’s fragment? Can we have for loop or if case?


Relay containers are higher-order components — Relay.createContainer is a function that takes a React component as input and returns a new component as output. This means that the container can manage data fetching and resolution logic without interfering with the state of the inner component.

There are two aspects to composing components in Relay:

Composing the view logic, and
Composing the data descriptions.

Yes we can have loops or if cases
