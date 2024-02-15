0x18. Webstack monitoring

In the fields of information technology and systems management, application performance management (APM) is the monitoring and management of the performance and availability of software applications. APM strives to detect and diagnose complex application performance problems to maintain an expected level of service. APM is "the translation of IT metrics into business meaning ([i.e.] value)."[1]

Measuring application performance
Two sets of performance metrics are closely monitored. The first set of performance metrics defines the performance experienced by end-users of the application. One example of performance is average response times under peak load. The components of the set include load and response times:

The load is the volume of transactions processed by the application, e.g., transactions per second, requests per second, pages per second. Without being loaded by computer-based demands (e.g. searches, calculations, transmissions), most applications are fast enough, which is why programmers may not catch performance problems during development.
The response times are the times required for an application to respond to a user's actions at such a load.[2]
The second set of performance metrics measures the computational resources used by the application for the load, indicating whether there is adequate capacity to support the load, as well as possible locations of a performance bottleneck. Measurement of these quantities establishes an empirical performance baseline for the application. The baseline can then be used to detect changes in performance. Changes in performance can be correlated with external events and subsequently used to predict future changes in application performance.[3]

The use of APM is common for Web applications, which lends itself best to the more detailed monitoring techniques.[4] In addition to measuring response time for a user, response times for components of a Web application can also be monitored to help pinpoint causes of delay. There also exist HTTP appliances that can decode transaction-specific response times at the Web server layer of the application.
