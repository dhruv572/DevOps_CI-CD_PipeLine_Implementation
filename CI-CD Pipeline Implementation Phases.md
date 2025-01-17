CI-CD PROJECT
-Phase - 1 
  -Create seperate network environments - {for privacy, isolation, security}
  -Create and manage VPC
  -Create and manage Security Group and its inbound (incoming) rules.
  -Create instances (3 instances for our Kubernetes cluster)
  -Create kubernetes cluster - to deploy application [scan it for vulnerabilities]
  -Create multiple VMs - sonarqube, Nexus, jenkins, Monitoring

-Phase - 2
  -Create git repo [should be private]
  -Push our source code
  -Now whatever we pushed, make it visible

-Phase -3 
  -Actual CI-CD pipeline implementation
  -Take security measures alongwith
  -After this Deployment is done
  -Implement mail notifications

-Phase – 4
  -Setup monitoring tools {done on 2 levels – system level (cpu, ram) & website level (traffic)}
