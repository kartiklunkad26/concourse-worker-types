# concourse-worker-types
Concourse manifest to deploy multiple worker types and assign them to teams

The manifest file here describes the concourse deployment with an additional worker type. 

As you see in the manifest, the groundcrew and baggageclaim jobs in the worker consume & provide baggageclaim variable, and hence had to be disambiguated for the two workers. 

The team property is in the groundcrew job of the new worker type. 

Important Note: You need to create the team before you specify in the manifest. 

