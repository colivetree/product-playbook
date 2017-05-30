# Dark Launch

## Intro
Launching features / making changes on live products is risky, reasonably often brings down an entire company´s infrastructure and hurts revenue and growth, both directly and by affecting their relationships of trust with their users and partners. Facebook famously moved from their "Move Fast and Break Things" motto to the less catchy "Move Fast with Stable Infra" to account for the need to keep things running for their customers, while iterating fast to deliver value. The alternative would be analysis paralysis and severe risk aversion. Dark Launching is one of the many available techniques to mitigate technical risk before releasing a feature to real customers. It's based on asynchronously loading a feature or service in a production environment, running it as if it were visible for customers, while still keeping it "in the dark" / invisible to users.

## When to Run
When a risky change (by nature of their criticality or number of customers affected) needs to be released and there is a significant chance it could impact customers. When performing major service surgery, infrastructural changes, critical element changes, redesigns or launching major features.

## Why to Run
It ensures the necessary metrics, behaviours and functionality are in place before releasing a feature to people, who will be less forgiving and tolerant of flaws and failures.

## Roles
* Developer Team
* Product and Engineering Management

## How to Run
* 1) Define key metrics and functionality to monitor - set up live dashboards for the team
* 2) Determine how to asynchronously load the new service / feature while making it invisible to users
* 3) Roll-out on a traffic ramp-up procedure, starting at a very low % of traffic and monitor both control and variant metrics
* 4) Keep monitoring metrics and fixing forward until you can verify there's no breaking change in functionality so it can be safely released

## Tips and Resources
* https://www.quora.com/What-is-a-dark-launch-in-terms-of-continuous-delivery-of-software
* http://blog.launchdarkly.com/why-leading-companies-dark-launch/

## Related plays:
