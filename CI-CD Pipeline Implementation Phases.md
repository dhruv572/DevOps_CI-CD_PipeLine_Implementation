CI-CD PROJECT
1. Phase - 1 
  1. Create seperate network environments - {for privacy, isolation, security}
  2. Create and manage VPC
  3. Create and manage Security Group and its inbound (incoming) rules.
  4. Create instances (3 instances for our Kubernetes cluster)
  5. Create kubernetes cluster - to deploy application [scan it for vulnerabilities]
  6. Create multiple VMs - sonarqube, Nexus, jenkins, Monitoring

2. Phase - 2
  1. Create git repo [should be private]
  2. Push our source code
  3. Now whatever we pushed, make it visible

3. Phase -3 
  1. Actual CI-CD pipeline implementation
  2. Take security measures alongwith
  3. After this Deployment is done
  4. Implement mail notifications

4. Phase – 4
  1. Setup monitoring tools {done on 2 levels – system level (cpu, ram) & website level (traffic)}
