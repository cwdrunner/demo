##### Creation notes for demo

###### Objective
Learn the capabilities of GCP as a CI/CD pipeline in order to have discussions around future direction.

###### Process
1. Watch a few overview tutorials and do some basic labs.
2. Collect information about the state of the current CI/CT process
3. Build a Java/Spring boot demo service using Gradle and GCP Cloud Build and Cloud Run
4. Identify issuse that would need to be addressed to move more towards GCP. 

###### Learnings
1. Our code base is Broadcom hosted Github. How can GCP monitor code changes from external
2. Artifactory is also locally hosted. Pushing and retrieving artifacts requires a secure connection
3. The base permissions given Devs in GCP can not create GCP projects or modify permissions. Someone with higher privs would need to set these up or they would need to be granted
4. Sometimes when you hit the permissions issues it's not clear if it is a bug or not
5. Overall the process for a master build is pretty straightforward. 
6. GCP is pretty powerful and has some nice features when compared to AWS.
    
    a. The project feature is great for grouping resources
    b. The Dashboards are clear and useful
    c. The Cloud shell feature is really useful and east to learn 


###### Future Opportunities 
1. Still need to get Artifactory calls to work. The Artifactory Cloud product doesn't have a free tier to try.
2. Expand the demo to feature branches.
3. Add semantic versioning
4. Manage AAI infrastructure for feature branches using Terraform







Process from 

https://cloud.google.com/run

https://cloud.google.com/run/docs/continuous-deployment-with-cloud-build

Region info from 

https://cloud.google.com/compute/docs/regions-zones

Artifactory can be integrated but requires access to a repo.

https://github.com/GoogleCloudPlatform/cloud-builders-community/tree/master/jfrog

https://cloud.google.com/blog/products/application-development/integrating-google-cloud-build-with-jfrog-artifactory


References

https://cloud.google.com/cloud-build/docs/build-config

https://cloud.google.com/blog/products/application-development/integrating-google-cloud-build-with-jfrog-artifactory

https://cloud.google.com/cloud-build/docs/view-build-results

https://spring.io/guides/gs/spring-boot-docker/


