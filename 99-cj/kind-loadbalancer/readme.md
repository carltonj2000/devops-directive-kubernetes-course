# KinD Load Balancer Test

I did not get this working as of 8/28/24 9 PM.
I could not get the KinD Load Balancer working in the section 04
Service chapter.
So I created this chapter to see if I could run the example
provide on https://github.com/kubernetes-sigs/cloud-provider-kind

- Run Task 00/01 to setup/delete cluster if not already setup
- Make sure to run 03 to setup the node balancer before running 04
- Delete 04 before stopping 03 on the shell or kind hangs on deletion
