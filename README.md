Central point to link documentation

## Onboarding documentation
The BOSH Director has three different main categories of tasks:
* synchronous tasks: block until they get a response
* asynchronous tasks: return a task id and execute the actual task asynchronously in the background
* tasks which involve the IaaS/CPI: asynchronous tasks which call the external CPI binary to interact with the IaaS layer

Here is a more detailed description of the individual task categories by example. They build on each other, each description assumes you have read the previous.

[deployments workflow](./onboarding-material/bosh-deployments-flow/README.md) -- focuses on interaction between CLI, director, and the database

[instances workflow](./onboarding-material/bosh-instances-flow/README.md) -- focuses on interaction between director, worker, and agent

[upload stemcell workflow](./onboarding-material/bosh-upload-stemcell-flow/README.md) -- focuses on interaction between director and CPI
