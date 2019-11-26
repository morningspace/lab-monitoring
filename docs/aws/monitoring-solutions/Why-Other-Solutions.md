# Why Other Solutions?

---

CloudWatch is pretty good for infrastructure monitoring such as network traffic, memory consumption, CPU utilization and disk I/O information. It is also able to collect detailed system-level metrics from EC2 instances or your on-premises servers by deploying its unified agent. It even allows you to push custom metrics from your applications or services using its agent with the StatsD and collectd protocols.

For small and medium size businesses, CloudWatch will work quite well. But for enterprise, CloudWatch may not be enough.

## Why solutions other than CloudWatch?

* **Application Specific Monitoring**

If you want a combination view of your cloud workloads and extend your infrastructure to on-premises servers, look at things from the user’s perspective by monitoring your application from end to end, then you may need other solutions.

Of course, CloudWatch supports application specific monitoring by using its agent and custom metrics, but it requires you to write your own code to capture data from applications and push to CloudWatch.

To monitor application service specific matters, so called Application Performance Monitoring or APM, such as Dynatrace, AppDynamics, New Relic, which can also seamlessly integrate with Amazon. That is exactly what you need.

Typically, these tools pull in CloudWatch data from Amazon and supplement that with monitoring data provided by vendor specific programs, e.g. agents or extensions, that can give more metrics out of the box and tie into applications like Apache, Nginx, MongoDB, MySQL, etc. So, you can unify monitoring, alerts, and incidents in a single dashboard to gain full control and visibility across your entire cloud and on-premises IT infrastructure.

* **Better usage experience**

CloudWatch can monitor lots of metrics from many different AWS services with its highly customizable dashboards, but it's easy to be lost with too much flexibility. If that's the case, then you may need other solutions.

Some monitoring tools can present the data in a much different way that is more understandable and actionable than CloudWatch's representation. Other monitoring tools, e.g. those solutions are SaaS-based, can monitor your AWS resources with very little efforts: dashboards out of the box, while adding custom checks/alerts remained quickly and easily. Just provide your read-only AWS credentials and the tools will take care of all the rest.

Those tools often make data collecting easier too. You don't have to install an agent for every server that you want to monitor, whether it is hosted locally or in cloud like AWS, so called agent-less solution. Or, just simple installation and configuration that replaces an entire 3rd-party host monitoring stack, where you have to provision the server, set it up, configure the firewall rules to allow it to talk to your servers, and worry about disk space, CPU, etc.

* **Deep Insights into Application**

Some monitoring tools can have deep insights into your applications by leveraging techniques such as machine learning. They can, for example, automatically discover and create health checks for everything found in your environment, automatically detect anomalies, analyze business impact, and figure out root cause across users, applications, and infrastructure.

* **Multi-could Enablement**

If your business uses a combination of datacenter and cloud workloads to run business services, even from cloud other than Amazon, then you may need other solutions.

Many monitoring tools in the market do not bind with Amazon soly, they usually also support other cloud such as Azure, Google compute, etc.

## AWS Marketplace Integration

Instead of competing with Amazon CloudWatch, market leaders such as Dynatrace, AppDynamics, NewRelic are all closely partner with Amazon. They all can be found in [AWS Marketplace](https://aws.amazon.com/marketplace/).

![](../images/awsmp-logo.png)

Customers can subscribe their products in AWS Marketplace and pay for usage through their AWS bill, just one click to deploy.

## Resources

* [What AWS monitoring tool is better: DataDog, CloudWatch, New Relic?](https://www.quora.com/What-AWS-monitoring-tool-is-better-DataDog-CloudWatch-New-Relic)
* [What are the best options for monitoring Amazon cloud servers, other than CloudWatch?](https://www.quora.com/What-are-the-best-options-for-monitoring-Amazon-cloud-servers-other-than-CloudWatch)
* [What is the difference between AWS CloudWatch monitoring and monitoring tools?](https://www.quora.com/What-is-the-difference-between-AWS-CloudWatch-monitoring-and-monitoring-tools)
* [What is the tool most folks use to monitor their AWS EC2 instances?](https://www.quora.com/What-is-the-tool-most-folks-use-to-monitor-their-AWS-EC2-instances)
* [Is Amazon CloudWatch good enough to monitor/manage applications deployed in AWS?](https://www.quora.com/Is-Amazon-CloudWatch-good-enough-to-monitor-manage-applications-deployed-in-AWS)
* [What are some alternatives to AWS CloudWatch?](https://www.quora.com/What-are-some-alternatives-to-AWS-CloudWatch)
* [Can AWS CloudWatch provide centralized logging similar to an ELK stack? What are the limitations of just using CloudWatch?](https://www.quora.com/Can-AWS-CloudWatch-provide-centralized-logging-similar-to-an-ELK-stack-What-are-the-limitations-of-just-using-CloudWatch)
