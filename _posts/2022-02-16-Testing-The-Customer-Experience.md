---
layout: post
title: "Testing The Customer Experience"
summary: "A quality customer experience matters, and it is our job to ensure that quality, and learn how the customers perceive it."
author: DanPetersen
date: "2022-02-16 15:48:00 +0000"
category: ["testing"]
tags: QAP
thumbnail: /assets/img/posts/CustomerExperienceThumbnail.jpg
thumbnail-caption: "Photo by playbookux"
thumbnail-alt: "customer experience"
keywords: customer experience, UI, UX, blog post,
usemathjax: false
permalink: /blog/Testing-The-Customer-Experience/
---

## The Problem
Software quality has shifted so much to ensuring your product “works” and “doesn't break” that oftentimes the customer experience of actually USING the software is overlooked. Automated testing efforts ensure all the buttons call the correct API calls, yet can hardly tell you if the customers find your software workflows confusing or needing tutorials and hand holding from implementation specialists for the customer to find any value from the product.

The metrics can speak for themselves:

![Customer Expereince Metrics](/assets/img/posts/CustomerExperienceMetrics.png)

So what can we, as testers, do to ensure that this becomes a focus for our organization as well to ensure customer experience gets wrapped into our holistic quality strategy?

## Solution - Understanding Marketing Will Make You A Better Tester
Wait, what? I know what you are thinking:
What does marketing have to do with testing the user experience? 
As if we, as testers, didn't already have enough on our plate. 
Testers are not the ones in charge of this stuff anyway.
All valid points, but if our organizations truly care about delivering quality user experiences to our customers, we as QA must understand the messaging we are sending with our product. We are the ones to continue to drive these conversations within the development process to ensure the customers voice is to be heard BEFORE they move to the competition, who did happen to think about it. 
Marketing is about how to connect with the target market, deliver a message, and influence behavior. Sounds like QA can learn similar techniques to connect to the customer and influence the business behavior to focus on end user experience.

## How its Done - The A, B, C, D, E of Marketing 
This is how QA can focus on the customer experience.

### A - Audience
> “100% of customers are people.” - Simon Sinek

In marketing, it is absolutely vital to send your message to your target audience. Understandingly, the same is true in software, if you can't understand your end user, you won't be able to understand how they feel about the quality of the product. There should be no doubt that depending on the people we are serving with our products, that the type of audience we are serving matters. Testers should understand if we are building a product to be used in an emergency room at a hospital, or creating a food kiosk at an airport. Who we are tailoring our product to deeply matters to how they will interpret the quality of said product. 
So how do we properly address the audience? User stories. Dive deep into those user stories and dive deeper around the possibility of personas of who could be that user. It helps to ask a lot of what if’s from your product owners to drive out all the scenarios you should be testing for. It’s also very important to dive into WHO is receiving what VALUE from this feature/functionality. Focusing on PEOPLE who receive the value from the product will keep the testers mind on the perceived quality from the end users perspective. 

### B - Behavioral Objective
> “Well done is better than well said” - Benjamin Franklin

Marketing teams are not out there simply trying to throw words and images around, their main objective is trying to change consumer behaviors. In software, the agreed upon change in behavior that the application delivers is the actual return on investment that the company wants to achieve. What proof allows the company to decide the application is making a meaningful impact? For testers this is aligning the customer experience with the company's overall goals and objectives. Quality is often simply distilled down to what expectations marketing and sales has set for the customer, and the agreed customer acceptance of said expectations once the product is delivered. For me, this is the crux of holistic quality for an organization. For testers, it is critical to have this alignment be understood in the user stories, test plans, and acceptance criteria of our testing efforts.

### C - Content
> “You are what you believe yourself to be.” - Paulo Coelho

One of the main goals of content in a marketing message is to give you a RTB - Reason to Believe. A RTB will give you the inspiration needed to make that purchase, or to convince you to change your current consumer behaviors. A quality customer experience with using a software product gives you that same content. Reports, logs, audit trails, proper documentation, cyber security verifications are all part of the content that testers need to ensure exist within the product. A quality user experience is one where the customer doesn't need another third party reporting service, because that was thought about as part of the feature. Or you wont need a completely detached learning management system to be able to properly figure out how to use the product. Items like these must be considered during the test plan phase or made part of the acceptance criteria of the Epics, Features, and Stories. The customer needs that RTB that the product is meeting all the expectations that were promised from sales and marketing teams. If the product doesn't easily give the consumer all the RTB it will meet expectations set by sales and marketing they will find another product that does give them that RTB.

### D - Delivery
> “Everyone is unique and each experience is different.” - Gloria Steinem

For marketing, finding out the best way to convince the consumer to change their buying habits is about WHERE the target audience will be at in order to best engage them. For software, it's about where our consumer connects with our application. For testers, it's about asking the question, is the attention to the value of the application properly given via that device? Has the same content been properly tailored to maximize customer satisfaction via the different platforms? This is where the quality of the product marries what it is being delivered on. Nowadays it is highly doubtful that your product is only being delivered via one medium (IE Desktop Computer). Most of the planet now consumes applications of any kind on their most mobile and personal devices (smart phones). Consumers expect the application to be usable to the screen size, and constraints within the device they are choosing to access the application. For example mobile screens are smaller, and are typically used in quicker spurts. So, are the main functions easy to read and navigate? Has your team or company thought about accessibility testing? Did you know that there are approximately 300 million people worldwide with colour blindness? (www.colourblindawareeness.org, 2022) Ensuring your product holds value no matter where or who is consuming it will help ensure a quality user experience.

### E - Evaluation
> "What's measured, improves.” - Peter Drucker

Our applications are able to grab a wealth of metrics when properly coded into the application. As part of the planning effort that goes into features and functions of the applications, management and marketing should agree upon what successful adoption of the various parts of our application means. For testers it is about ensuring we are able to use these metrics to identify where customers are gaining value from the product. The 80/20 rule known as the Pareto principle, named after the Italian economist Vilfredo Pareto, states that 80% of the outcomes (company sales) come from 20% of causes (customers). Same thing applies to our applications. Customers oftentimes will find the majority of value of the product from 20% of the features it has available. We should be able to use the collected metrics of use of the product to understand where the majority of use of the product is concentrated on. Based on that, testers should spend the appropriate amount of time focused on those same areas as the consumers do. Knowing that those parts of the application will be increasingly scrutinized, and if compromised will trigger quality of the product to plunge accordingly. 

## Conclusion
Testers are not the only people in the organization responsible for a quality customer experience. It should be a company wide effort to ensure a quality customer experience. Yet, we as testers hold a special place in the organization that helps us be that actionable voice of the consumer BEFORE the product is ultimately judged by the end users. Things we have learned to truly test for the customer experience:
We have learned that who we test for matters. (Audience)
We have learned that aligning our successful test criteria with the business matters. (Behavioral Objective)
We have learned that giving the customers a reason to believe matters. (Content)
We have learned that where, how, and who is consuming the product matters. (Delivery)
We have learned that tracking the value of the product matters. (Evaluation)
As the metrics have pointed out, a quality customer experience matters. It is our job, as testers, to ensure that we understand the customer perspective, and provide a quality customer experience.

