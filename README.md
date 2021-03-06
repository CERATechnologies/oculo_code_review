# Oculo Code Review
## The Code
Inside of `code.zip` is a simple controller from a bigger application that allows users to send communications to each other.
The functionallity can be described as:
- Allow an API client to create a message from an existing user to an existing user and send it via an external api
- Allow an API client to query the message at a later date to determine if the message has been successfully sent.

The code also contains a `ExternalApiClient` that represents an interface for making calls to an external system which can
take varying amounts of time to succeed, fail and raise errors (like timeouts).

It also contains an integration spec that tests the desired behaviour

It's also worth noting this code has been designed to be problematic and is not indicative of how we write code at Oculo

## The Exercise
We would like you to do the following:
- Create a repository called `oculo_code_review`
- Download and extract the contents of `code.zip`
- Create a pull request against your repo with the contents of `code.zip`
- Review the pull request identifying problems you find in the code and suggest changes you would need to make to get the code
  to a **production** ready standard.
- When examining the code you can assume that the rest of the application is coded in a similar way so will also be problematic.
- Provide commentary on any considerations or questions that might need to be answered about the code.
- You can safely ignore any issues that a linter could auto-correct.


When you're happy with your review send us a link to the PR.
