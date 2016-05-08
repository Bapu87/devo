# Avenue Code CookBook Challenge


Your task is to create a cookbook such that it manages the state of a node that will...

(1) Manage a web server(tomcat, apache, jetty your choice) installed and started at port 8080
(2) Have a WAR file deployed to that web server
(3) Write meaningful unit and integration tests and be able to run in test kitchen

Keep in mind, an evaluator will check out your repository and should be able to run test kitchen against your cookbook and see that the war file is deployed and running.



Requirements
------------
The war file can be reached at </files/default/java-chef-test.war>
The test page for the WAR file should be:


http://<host>:8080/java-artifact-chef-test/chef/ping

Tests should show that this page is reachable and is specific to the content the test page sends back.


The default recipe for this cookbook should make all this happen.



## Delivery Instructions

1. You must provide his BitBucket username. A free BitBucket account can be created at http://bitbucket.org
1. The recruiter will give you read permission to a repository named **devops-challenge**, at https://bitbucket.org/ac-recruitment/java-challenge
1. You must fork this repository into a private repository on your own account and push your code in there.
1. Once finished, you must give the user **ac-recruitment** read permission on your repository so that you can be evaluated. Then, please contact back your recruiter and he will get an engineer to evaluate your test.
1. After you are evaluated, the recruiter will remove your read permission from the original repository.

## Format

* This assessment must be delivered within 2 hours.
* You must be prepared to walk an evaluator through all the created artifacts including tests
    * Mention anything that was asked but not delivered and why, and any additional comments.
* Any questions, please send an email to **recruitment.engineering@avenuecode.com**

Thank you,
The AvenueCode Recruiting Team
