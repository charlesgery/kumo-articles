---
published: true
title: 'You thought serverless was green? Here is how to really make it sustainable! 🌱'
cover_image: 'http://www.nasa.gov/sites/default/files/thumbnails/image/as17-148-22727_lrg.jpg'
description: 'Description of the article'
tags: greenit, aws, sustainability, serverless
series:
canonical_url:
---

**Serverless is an amazing way to do cloud computing.** It removes the hassle of managing the infrastructure of your app and lets you focus on what really matters: delivering value.

Moreover, in regular cloud computing, **lots of resources are idle**. Servers are often running without any task to do. People don’t optimize the capacity of their servers relative to the workload they really have. With serverless, cloud providers have a way to **share resources between clients and optimize their use**. Your serverless app will scale easily and will only be running when your users need it. For instance, AWS will launch Lambda functions instances and run their code only when required.

![Lambda lifecycle](./assets/lambda-lifecycle.png 'Lambda lifecycle')

Because of that, **serverless is often considered greener than traditional applications in the cloud**.

## Is your serverless application perfectly sustainable?

Going serverless is considered a sustainable solution to develop applications. **This is not a reason to be complacent**. You can certainly take action to improve the sustainability of your application.

> \*“Never settle for average.” ― **Steve Jobs\***

There are **many sustainability mistakes you can make** when developing a serverless application. For instance, you can:

- Forget using lifecycles for your data stored in S3,
- Have servers far from your end-users,
- Use a database service that is not suited to your needs...

In his [article](https://dev.to/kumo/monitor-the-co2-emissions-of-your-aws-application-with-cloud-carbon-footprint-2hjm), our colleague Thomas provides you with a **simple way to monitor your carbon emissions** using [Cloud Carbon Footprint](https://www.cloudcarbonfootprint.org/). Monitoring your emissions is a first step to avoid bad sustainability patterns. This way you can see and control the evolution of your emissions as your application evolves and be aware if one of your features pollutes abnormally.

![Cloud carbon footprint dashboard](./assets/ccf-dashboard.png 'Cloud carbon footprint dashboard')

## You can make your serverless application even greener!

Monitoring your emissions is great, but we wanted to take the next step and **find actionable ways to reduce our emissions.** We read the [AWS Sustainability Pillar](https://docs.aws.amazon.com/wellarchitected/latest/sustainability-pillar/sustainability-pillar.html) for you and **listed concrete actions** to implement the good practices it describes.

**We developed a sustainability audit for your AWS serverless applications that lists these actions**. Within **10 minutes**, you will be able to fill in the whole form and **receive a score out of 100**. After filling out the audit, you will be **provided with a list of recommendations** that will help you make your application more sustainable.

After taking the recommended actions, you should see your application emissions lower in your carbon monitoring dashboard! 🥳

There’s more, by performing this audit and taking the associated actions, you will **make your application much more sober**, which can also **improve the performance and monthly cost** of your application.

The instructions and the audit are available **[here](https://www.notion.so/Sustainability-Audit-EN-Version-a36847289fd64339a60e40bc5aa63092)**.

![Audit screenshot](./assets/audit-screenshot.png 'Audit screenshot')

If you have any questions or feedback to improve the audit, feel free to reach out to us !

_Juliette Fournier & Charles Géry are software engineers at Kumo, serverless expertise by [Theodo](https://www.theodo.fr/)_
