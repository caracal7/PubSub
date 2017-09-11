# PubSub
A lightweight es6 PubSub class. (Singleton module version)

forked from devinle/PubSub

## Usage
`import PS from './PubSub.js'; // Import the PubSub singleton`


`PS.on('event', callback); // Create a new event with a custom callback`

`PS.trigger('event', {data}); // Trigger an event, and pass optional data`

`PS.off('event', callback); // Remove an existing event and callback`

`PS.off('event'); // Remove the entire event and all attached callbacks`
