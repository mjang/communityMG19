What to encourage
What to try to avoid (to protect the company)

Basic education on copyright and licenses needed first, including use-license and distribution-license
Can only start on open source stuff once you understand those!
"The GitHub generation" needs different help and support to those from the 90s and 00s
Link what developer does back to what the customer needs, why are we doing this?
Use Left-Pad as an example of why it matters

Open Source selection vs Contribution

Help the right kind of thing to happen
Set constraints, and guidelines

Consider an intro that sets out the philosophy / reasoning, then
followed by some easy to follow steps 

Keep it small

"We need to protect the company, while being a good citizens, and
especially to help grow our community and toolchain comunity"

Where possible, use tooling to help people avoid making mistakes
Otherwise, make rules simple so people can quickly and easily follow

Think about your company, and where it might go, then decide on what kinds
of licenses that you'll OK, which need considering, and what are automatically a No

Define an escallation for harder stuff

"It's not just free stuff from the internet", think "Free as in Puppy"

Consider who will be your lawyers, what they know
But try to avoid using them! They're expensive... Make it easy for Developers to
do the right thing

Have some definitions for things, eg PII, to make sure "I grep'd for PII in the 
code and didn't find it, so we're ok to submit these personal details!"

For management / board:
This specific bit of code / feature / fork - it may be valuable, but is it
valuable enough to pay for the cost of maintaining it? Will we earn enough?

Get quite a few other people to read it before you publish it, get feedback,
make sure it's ready

----------------------

# Resources
 * The TODO group, especially the archives for early stuff
 * Quite a few bigger companies have published policies, though it may have problems and 
   solutions that don't completely apply for small firms

----------------------
 
# Draft Ideas
The aim of this policy is to make it easy to participate in and contribute
to Open Source projects, without accidentally releasing key intelectual
property of the company or it's customers in the process.

We divide contributions up into 4 types, depending roughly on size and impact:
 * Bug Reports
 * Simple fixes
 * Complex fixes and simple features
 * Large features and whole projects
If you are not sure on which category something falls into, please check
with your manager.

Bug Reports:
 (something on checking for existing ones first)
 (something on trying to make a MRE - minimal reproducible example)
 (something on checking logs, stacktraces and files for PII or credentials)
 (something on good bug reports)
 (no permission needed)

Simple Fixes: 
 (something on maintenance benefit of pushing fixes upstream, so we don't
  have to look after them / port them to new versions going forward)
 (something on including unit tests and/or documentation)
 (something on checking logs, stacktraces and files for PII or credentials)
 (no permission needed)

Complex Fixes and Simple Features:
 (will need brief review first, to ensure it's not in an area we feel
  has significant IP we want to keep private)
 (something on checking with community that it's likely to be accepted before
  doing lots of work)
 (something on including unit tests and/or documentation)

Large Features and Whole Projects:
 (review at start and end)
 (decision on license) 
 (decision on where to contribute it to, how to support it, how/if to build
  a community around it)
 (get several people involved)
