# sample-upload-server

A customer asked me how to upload a file from a Control Plane workload (where a user remotes into its shell) to the developer's laptop. While there are many methods to do so. I decided to use the Control Plane wormhole agent functionality to demonstrate how this can be done. An agent lets the workload reach into private network endpoints. In this case, the developer's laptop is behind a firewall (not exposed to the internet).

The main.go file contains the server-side code that we run on the developer's laptop.
This video illustrates how to set up the agent, identity and give a workload (ubuntu in this case) the identity, in order to have it be able to reach the developer's laptop (wherever it may be) using the agent:

https://vimeo.com/840734329/521a3f8270?share=copy

