---
title: "Errors and Exception Handling"
metaTitle: "Errors and exception handling | WP"
metaDescription: "Proactive monitoring and log analysis of potential and occurred errors to provide graceful recovery and diagnostic capability for support teams."
published: true
metaTags:
  - Plan
  - Errors and Exception Handling
  - Winning Product
  - Technology Mastery
---


## Why
Regardless of how well you test a product, you must anticipate and prepare for unhandled errors in production. This is due to unplanned user behavior, missed test scenario, or data incompatibility. Good products should recover from errors and keep development/support teams informed with all necessary information to trace and help the users.

There are three levels if the issues your product should tackle.
1. Validations failures: Issues that can  be avoided through validations and checks (e.g., user inputs)
2. Handled Exceptions: Issues that are tackled through Exceptions to recover gracefully (e.g. Third-party service not available)
3. Unhandled Errors: Issues that are not anticipated and does not get handled in exception handling. (e.g Unplanned special character in data causing a data exchange protocol failure)

Your product requires the capability to detect, especially the type 3 above (Unhandled Errors). You should not rely on already frustrated users to take screenshots or send you error codes. Error handling must be automated and proactive to respond. 


## How
- Build a high-importance culture towards production errors. Every error should be brought to the limelight and dealt with immediately. 
- Follow a standard process on how errors are captured, communicated, and fixed. Document this process and keep all stakeholders informed.
- Make use of automation tools to capture, monitor, and report production errors. Increase the visibility within the organization (through dashboards, etc.) to ensure errors do not go unnoticed. 
- Enable your application to log diagnostic information on product health to an easily accessible location. Make sure that the logs a fresh and relevant. Thereafter, proactively analyze this information to find any anomalies.
- Set up your tooling in a way that it does not only capture a stack trace but contextual information such as release version, account id, data status, etc. to make identification of the error cause easier.
- Proactively respond to users if they had faced an error. Assist users in recovering any potential losses they have incurred through your support organization. 
- Audit the information exposed to an error condition. Hackers may use information exposed to get internal details.


### References/further readings
Error monitoring tools
 - [Sentry](https://sentry.io/)
 - [AirBrake](https://airbrake.io/)
 - [BugsNag](https://www.bugsnag.com/)
 - [Rollbar](https://rollbar.com/)
 - [TrackJS](https://trackjs.com/)
 - [RAYGUN](https://raygun.com/)
 - [Azure App Insights](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview)

[How to handle exceptions](https://raygun.com/blog/errors-and-exceptions/)
