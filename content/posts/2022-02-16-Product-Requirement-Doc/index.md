---
title: Product Documentation Series - Product Requirement Document
author: Damilola Ajiboye
date: 2022-02-16
hero: ./images/hero.png
excerpt: Most projects fail due to a lack of requirement gathering and proper requirement documentation. Here is how you can avoid this pitfall.

---

# What is a Product Requirement Document?

The awkward truth is that most projects fail due to a lack of requirement gathering and proper requirement documentation. Product teams sometimes end up working in circles trying to build a product that was never understood or clearly communicated. This not only produce an unfit product but a massive waste of time and resources that could have been channeled to building compelling products. 

This problem is what a Product Requirement Document mitigates. A PRD highlights and communicates idea/project details like the why, and what and informs teams on the different contexts around an idea.

While a [statement of work](https://plan.io/blog/scope-of-work/) or [project plan](https://plan.io/blog/project-proposals/) will dig into the specifics of *how* you’re going to build a product, the PRD is more focused on *what* is being made.

According to Marty Cagan, the purpose of the product requirements document (PRD) is to clearly and unambiguously articulate the product’s purpose, features, functionality, and
behavior. 

# Why do you need a PRD?

PRD serves as a compass, providing a clear path toward a product's purpose while creating a shared understanding among business and technical teams. 

It is the “landing page” for what you’re trying to build as you will always refer to it to get context around the project even during the development stage. Having something that is the central go-to location saves your team members time in accessing this information and gives them a concise view every time they need it.

# What are some PRD best practices?

- **Keep requirements lean:**

Treat your PRD *like* “a one-pager” in terms of length. This does not mean that you should try to fit it into a page. It might not work.  No executive/stakeholder wants to read another lengthy document, they have a lot to deal with already. You can achieve a lean requirement document by including only important information that needs to be on the document and adding other addons as links, embeds, or addendum.

For instance, it helps to link (reference) resources like your user interface design and customer interviews rather than displaying them on the document. The whole point of a PRD is to be able to take your audience on a journey of what the product/feature is about and be able to make sense of it. Try to make the journey short.

- **Make requirement gathering a teamwork**

The most important aspect of all this is getting everyone involved. It helps to carry alongside major key stakeholders like Engineering and Design who will be important in building out the product. Share the page with your team and get feedback before pitching the idea to other stakeholders. 

Seek feedback, comment, questions, and encourage others to contribute to it. You should be wary of your idea if no one is sharing feedback or making comments. It could be that your idea is vague and no one understands or they think it’s mediocre.

Collaborative requirement gathering is especially important for distributed teams who don't often get a chance to discuss projects in person.

- **Stay Agile while creating your PRD**

Remember to be agile in your evolution of requirements for a project. It's okay to update user stories as the team builds, ships, and gets feedback. Always ensure to validate your ideas through product discovery and market insight and ship only features/products that your users need even if this means shipping fewer features.

Treating PRD as a static document is an easy trap that a lot of PMs (including myself) fall into. Since your user's needs will keep evolving, your product must always be repositioned to meet them at the point of their needs. This should also translate to your requirement document. Be comfortable making updates on the PRD and ensure to update your team on the new development.

# What you should include in your PRD

This is not an exhaustive list and you can come up with your list based on the problem you are trying to solve and the complexities involved. But the list below shows a general template to follow.

- **Objectives / The problem:**

This is essentially the “who”, “what”, and “why” of the product or feature that is being built. It is important to clearly articulate this as it helps other audiences of the document see if there’s a need for the product at all and if it is a priority. 

*Remember that the PRD is to help get your idea across to team members and serve as a reference point all through the process. Since this is the reason, then you need to prove these facts.*

- **Success Metrics**

What does success look like - How do we know we have solved this problem? Did we achieve what we set out to solve? How do we know? Answer these questions and write them down in this section.

This criterion becomes incredibly important throughout the project because it helps you make decisions and prioritize. Does feature X increase the chances of achieving the goal you set? If not, reprioritize it.

Ideally, this should be a specific metric, with a defined goal, that can be easily measured. It should directly connect to your team’s KPIs and be based on the size of the opportunity, and the value it will add to the users. 

- **Assumptions**

This could be technical, business, or user-related assumptions. 

- **Product Features**

These are the functionalities or features that will make up the product. With a proper definition of success, it becomes easy to prioritize features with high priorities (the ones that help us achieve our goal the most), to the ones with lower priorities. Listing this out also helps to convey the idea from a product perspective to the stakeholders. Ideally, this should be supported with user interface designs or sketches of the features.

- **Constraints / Dependencies**

These are two different things that need to be highlighted. Constraints could be having an intermediary between the app and the customer (Think of a food delivery product, there’s the app, the rider, and the customer). In this instance, the user’s delight is largely tied to the rider’s service. This intermediary relationship is a constraint for such products in delivering delightful service to customers. 

Dependencies can come in form of licensing, regulatory compliance, and partnerships. Basically, the things that are needed for you to run the business/build the feature.

- **UI Design**

This does not necessarily need to be a high-fidelity design. In fact, it’s best that it is a sketch. This is to avoid investing too much effort in designing a product that you have not validated or gotten approvals from your stakeholders. In the designs, be sure to show the features and how it blends into the existing product (for existing products). A good way to support your design is to include a user flow - what the user journey will look like.

- **Open Questions**

In this section, list out questions that you don’t have the answers to. This helps to drive involvement and deliberation on the idea while pitching it. It also shows that you are able to think of trade-offs about the product. It is also fine not to have all the answers but be sure to lean on stakeholders who are domain experts to help you out.

- **Out of Scope**

This can include features that your idea is not and future ideas that can be further built into it.

# PRD Example.

For a more practical approach, we’ll use our usual food delivery startup Byke (Remember Byke from the [previous article](https://www.damilolaa.xyz/product-documentation-series-product-strategy#:~:text=To%20explain%20clearly%2C%20we%20will%20consider%20a%20hypothetical%20example%20of%20a%20grocery%20delivery%20startup%20called%20Byke%20and%20walk%20through%20a%20product%20strategy%20approach%20for%20the%20company%20at%20the%20Pre%20Product/Market%2DFit%20stage%2C%20Product/Market%2DFit%20stage%2C%20Growth/Expansion%20stage%2C%20and%20the%20Maturity%20stage.)?) to come up with a requirement document for the merchant dashboard.

Byke is planning to expand its services and has tasked the Product team to conduct product and customer discovery and suggest other services that they can venture into. 

The Product team in their research figured out the following (in order of priority)

- Restaurants struggle with fulfilling orders.
- Managing inventory is a pain.
- Restaurants cannot track sales and end up losing money in the process.
- Scaling a restaurant business is as difficult as running a startup.

Based on the result of their research, the team is proposing that Byke builds a restaurant operating system solution (think [Toast](http://toasttab.com), [Orda](http://orda.africa),) alongside its existing service to help restaurants owners run a seamless business. 

The embedded PRD below shows the Product team’s first attempt at presenting the idea to stakeholders.

<figure class="video_container" style="text-align: center">
 <iframe src="https://coda.io/embed/jspxQJ6XAt/_sut2b?viewMode=embedplay" width="900" height="500"  allow="fullscreen"></iframe><figcaption>Byke's Product Requirement Document</figcaption>
</figure>

<br/> <br/>

At the end of this review session, each team is well informed about the product, and the problem it plans to solve. The respective teams are also able to provide context to the open questions that the Product team has and clear some of the uncertainties that have been encountered in the product scoping and brainstorming.

In scenarios where there are feedbacks that require further implementation, the Product team should prioritize them and ensure that a proper alignment and approval is gotten while this is still a priority to everyone.

# Closing thoughts

While there will always be user problems to solve, PRDs are there to ensure that you are able to clearly communicate the solution to your audience and be in a better position to solve your user's problem. 

There is really no fixed method to creating a compelling Product Requirement Document but understanding your user’s need, rallying your team around it will be helpful in pitching, defending your PRD successfully, and aligning stakeholders to it. 

<hr/>

Thanks to [Desiree Craig](https://ng.linkedin.com/in/desiree-craig) for reading drafts of this.

<hr/>

# Additional Resources

[My favorite product management templates - Lenny Rachitsky](https://www.lennysnewsletter.com/p/my-favorite-templates-issue-37)

[Figma's approach to modern PRDs](https://coda.io/@yuhki/figmas-approach-to-product-requirement-docs)

[Free product requirements document (PRD) templates](https://nira.com/templates/product-requirements-document-templates/)