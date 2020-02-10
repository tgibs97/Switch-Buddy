# Switch Buddy

An Augmented Reality application that plays advertisements on product cases in real-time.
[![Watch the video](https://i.imgur.com/rxnG3ep.png)](https://www.youtube.com/watch?v=5fvQ0rBS5qc&feature=youtu.be)

## Inspiration

All current smart switches on the market, save for one, require complete removal of your current light switch and electrical installation of the smart light switch. The one smart light switch that does not require installation is not compatible with other smart home devices like Amazon Echo or Google Home. So we set out to build a smart light switch that requires zero installation and works with other smart devices.

## What it does

Connects your light switch to a smart home environment.

## How we built it

We used a Particle Photon microprocessor, which communicates to Amazon Echo, to trigger a servo which flips a light switch. The casing of the Switch Buddy has magnets which allow it to just snap onto existing light switches.

## Challenges
The communication or "handshake" between the Photon and Echo proved to be a challenge due to lack of documentation available. This was solved by using a service called IFTTT to handle the "handshake".

## Project Accomplishments 

...

## License
[MIT](https://choosealicense.com/licenses/mit/)
