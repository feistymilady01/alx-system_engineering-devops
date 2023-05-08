# Postmortem
Duration of the outage: 3 hours, from 10:00 AM to 1:00 PM EST.
- *Impact: The  website was down for all users during the outage period, resulting in a loss of sales and a negative impact on customer satisfaction.*

- Root cause: The outage was caused by a hardware failure in one of the servers hosting the website.

 - Timeline:
 1. 10:00 AM: The outage was first detected when the monitoring system alerted the DevOps team of a high number of failed requests.
 2. 10:05 AM: The DevOps team investigated the issue and found that the website was not responding to any requests.
 3. 10:10 AM: The team assumed that the issue was related to a software bug and started debugging the code.
 4. 11:00 AM: After an hour of debugging, the team realized that the issue was not related to the software and started investigating the infrastructure.
 5. 11:30 AM: The team identified that one of the servers hosting the website was not responding and suspected a hardware failure.
 6. 11:45 AM: The team contacted the infrastructure team to replace the faulty hardware.
 7. 12:30 PM: The infrastructure team replaced the faulty hardware and the website started responding to requests.
 8. 1:00 PM: The website was fully restored and operational. --
- Root Cause and Resolution:
The root cause of the outage was a hardware failure in one of the servers hosting the website. The faulty hardware was replaced by the infrastructure team, and the website was restored to normal functioning.

- Corrective and Preventative Measures:
To prevent similar incidents in the future, the following tasks will be implemented:

Improve the monitoring system to detect hardware failures more quickly.
Implement redundancy for critical hardware components to minimize downtime.
Regularly perform hardware maintenance and replace aging components proactively.
In conclusion, the outage was caused by a hardware failure that took longer to identify due to initial assumption that it was related to software. The corrective and preventative measures will be implemented to prevent future incidents and minimize downtime.
