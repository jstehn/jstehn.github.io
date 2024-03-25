---
title: "Doing Good, Avoiding Harm: Your Guide to Ethical AI and Tech"
date: 2024-03-23T16:47:59-07:00
draft: true
---

The incredible potential of AI and data science is undeniable. But as data professionals with the power to shape the future,  we must also confront the ethical implications of our work. To ensure technology truly serves humanity, we need a deep understanding of core ethical principles.

My experience developing data ethics resources for UC Berkeley’s College of Computing, Data Science, and Society and their Human Contexts and Ethics program, coupled with real-world case studies (like working with data on vulnerable populations in San Francisco or building a data science product at a startup) has fueled my passion for this topic. In this six-part blog series,  I'll share insights gleaned from leading experts and organizations to help you navigate the complex world of AI ethics.

Whether you're a tech professional seeking greater clarity, or a concerned citizen who wants to understand these issues, this series will equip you to tackle the big questions: How do we design AI systems that do good and avoid harm? How do we balance innovation with protecting fundamental human values?

If you sense the importance of AI ethics but feel unequipped to navigate its complexities, this blog is for you. I hope to empower you to ask informed questions, engage in meaningful discussions, and ensure that AI serves the best interests of society.

Let's dive in, starting with the foundational principle: Do good, avoid harm.


# Do good, avoid harm

This is one of the most consistent principles that you will find in most published ethical guidelines. In fact, it is the first in [Google AI Principles](https://ai.google/responsibility/principles/). It is the hippocratic oath of data science, however defining good or harm becomes incredibly nebulous. These concepts are subjective and depend on cultural and societal values. What constitutes benefit for one group may be detrimental to another (Example: facial recognition helps law enforcement but may contribute to discriminatory surveillance). It will be useful in our journey to explore ethical frameworks that help inform what is good and what is harmful.


## Ethical frameworks

First, we must have an understanding of how each of us defines good. Here, we can look at three large branches of moral philosophy frameworks: Consequentialism, deontology, and virtue ethics. Each one has its own wisdom and its own pitfalls.


### Consequentialism

In consequentialism, the morality of an action is judged solely by its consequences. Good consequences equal an ethical action. Utilitarianism is a common form, aiming to maximize the overall good or happiness. This is one of the most attractive moral philosophies for data scientists as it is often easy to define some metric to maximize or minimize. It is an adaptable philosophy that focuses on practical outcomes.

This framework shines when outcomes are consistent, the good is largely quantifiable, and when looking at large scale problems. For example, it is very good for public health interventions. During the COVID-19 pandemic, analyzing data on transmission rates, risk factors, and the effectiveness of non-pharmaceutical interventions played a crucial role in many policy decisions. A consequentialist approach can help in the distribution of a limited resource to maximize positive outcomes which makes it well suited for crisis response like disaster relief or triage.

However, consequentialism falls short in some major ways. First, it pretends that the world is consistent enough to predict outcomes. In reality, it is impossible to foresee all the potential consequences and ripple effects of an action. Consequentialism provides little guidance on how to operate when the exact outcomes are unclear. Additionally, there are no objective measurements of goodness. Is a single life more valuable than the ability of a person to live comfortably and escape poverty? What about a family? How about the wellbeing of thousands of people? We already passively make these calculations. According to the CDC, [Road traffic crashes are a leading cause of death](https://www.cdc.gov/injury/features/global-road-safety/index.html) in the United States for people ages 1–54. Collectively, we have decided the gains we receive to have vehicles outweigh the [over 44,000 lives estimated to be lost](https://injuryfacts.nsc.org/motor-vehicle/overview/preliminary-estimates/) last year. Some values are difficult or impossible to quantify. Consequentialism struggles to make decisions when values cannot be compared on a single scale.

Second, under consequentialism, it is quite easy to justify “bad” means for “good” ends. If all you are judging an action by is the outcomes, then all means become available to you as long as the outcome is good enough. Lying, stealing, or even harming individuals might be rationalized if they lead to a greater overall benefit. We see that, with sufficient mental gymnastics, any belief and behavior can be justified. Additionally, engaging in this unethical behavior for outcomes erodes trust in institutions that rely on a consequentialist basis.

Consequentialism naturally prioritizes the majority. If one is attempting to maximize overall good, the needs and rights of minorities or individuals may be sacrificed for the sake of the benefits gained by the majority group. For example, Native land in the United States has long [bore the burden of containing our nuclear waste](https://inkstickmedia.com/how-native-land-became-a-target-for-nuclear-waste/). In a consequentialist view, these lands are less dense in population and harm the minority population who often lack political or economic power. The majority population does not have to live with the waste anymore and you have maximized “good.” Purely consequentialist reasoning can lead to viewing people as a means to an end rather than individuals with inherent worth.

Let’s see how consequentialism works out in data science contexts. The classic 'trolley problem' forced into reality: Should a self-driving car prioritize the safety of its passengers or minimize overall casualties in an unavoidable accident? A consequentialist approach focuses on the outcomes of each choice. Should a streaming service recommend content it knows the user enjoys, even if it might be addictive or unhealthy in the long run? Consequentialists weigh the short-term pleasure against potential negative long-term impacts. During a pandemic, should limited medical resources go to those with the highest chance of survival or those that play the most 'essential' roles in society? Consequentialism helps analyze different ways of maximizing overall good.


### Deontology

In deontology, often referred to as duty ethics, actions are judged by their adherence to universal moral rules, regardless of the consequences. They are often based on ideas like human rights, honesty, and duty. It seeks to address some of the disadvantages of consequentialism. It prevents actions that use people purely as a means to an end. It prevents the tyranny of the majority and upholds human dignity. It provides consistency in decision-making and gives moral clarity by reducing confusion in morally complex situations by using clear-cut guidelines.

In some illustrative examples, a deontologist might argue that a doctor has a duty to prioritize the patient’s well-being and autonomy even if a treatment might result in negative consequences for the patient or the doctor. 

A deontological framework does not do well in the inevitable clashes of rules and duties that are opposed to each other. Imagine a doctor who feels obligated to reveal life-threatening test results to a patient, even if it might severely damage the patient's emotional state. Here, the principle of honesty conflicts with the duty to avoid causing harm. A deontologist must consider how to weigh these ethical obligations.

However, deontology comes with its own shortcomings. First, it leads to inevitable clashes. What does one do if moral duties conflict? What is the culture which creates the duties? How do you define good in this case?

The most common place to find the deontological framework used is in law and justice. It holds that the rule of law is important and that upholding the process and rights is paramount regardless of outcomes. While this creates an illusion of fairness, blindly following the law without questioning its morality can perpetuate unjust systems. For example, judges may be [obligated to enforce laws they deem unethical or disproportionately harsh](https://www.npr.org/2017/06/01/531004316/a-federal-judge-says-mandatory-minimum-sentences-often-dont-fit-the-crime).

It is often rigid and inflexible. It also disregards consequences. In a deontological framework, one has a moral obligation to keep a promise, even if breaking it results in a better outcome for others. The father of deontology is [Immanuel Kant](https://www.britannica.com/topic/deontological-ethics), who referred to telling the truth as a perfect duty; a duty which one must always do. Now, there is [a lot of nuance](https://academic.oup.com/book/5430/chapter-abstract/148272683?redirectedFrom=fulltext) in what Kant refers to here, but for simplicity let’s say that we agree with this as a basic tenet of morality. Imagine a murderer comes to your door and is seeking your friend whom you have hidden in the attic. The murderer asks you for the location of your friend. Under the rigidness of a purely deontological framework, you cannot lie to save your friend.

We can see deontology manifest to create good data science practices already. Do users have an absolute right to know how their data is used, even if it hinders a company's ability to innovate or provide services? For a deontologist, protecting individual rights often takes precedence over exploiting potential benefits. Is it ever right to exploit known psychological vulnerabilities to sell products, regardless of whether the product itself is beneficial? A deontologist might argue this always violates the principle of treating people with respect. Even if it could be shown to reduce crime, does the use of algorithms in criminal sentencing violate inherent rights to a fair trial? Deontology focuses on upholding justice processes regardless of the outcome.


### Virtue Ethics

Virtue ethics shifts the focus from specific actions to who we want to be as data scientists. It asks, "What kind of person should I be?" rather than "What specific actions are right or wrong?" Instead of focusing on the duties that one must perform, it seeks to cultivate particular virtues such as honesty, compassion, and fairness over one’s life through learning, practice, and self-reflection.

Unfortunately, while virtue ethics may produce a great person, it is also the most hand-wavy of the three frameworks we are looking at today. Unlike a rule-based system, virtue ethics provides less concrete guidance for specific ethical dilemmas. Virtues are different across cultures and historical periods, and they often change. It also can create concerns about inclusivity as the virtues that one person might hold as unassailable are culturally insignificant to others.  Virtue ethics can neglect systemic issues by focusing on individual character as it can downplay the role of external factors that influence behavior like poverty or inequality.

Virtue ethics often focuses on what an individual might do rather than what we can do collectively. This may seem to be a weakness, but it also provides some major strength for data scientists. Should a data scientist speak up if they see potential bias or harm in a project, even at personal risk? Virtue ethics emphasizes courage as essential for taking ethical action. How can data scientists cultivate awareness and empathy to recognize potential biases in datasets or model design? Virtue ethics focuses on building character traits to proactively address ethical concerns. When a project doesn't deliver the intended results, should the data scientist sugarcoat the outcome – or is honesty a key virtue? Virtue ethics emphasizes truth-telling and integrity even when it's difficult.


## How do I use this as a data scientist?

As you might have guessed, there is no right framework to operate under. Each one is fantastic for some reasons and utterly fails in other situations. It’s important to understand the strengths and weaknesses of each framework and adapt your own understanding of “good” by utilizing them all. Know when to prioritize: recognize that no single framework is perfect. Deontology offers clarity on fundamental rights, consequentialism keeps outcomes in sight, virtue ethics focuses on character.

In order to define “good” and “harm,” one has to have that “ethical toolbox” to pull from. Whose good are we talking about? Is it good for the company? The good of the customer? Society? Employees? How can you balance these conflicting perspectives? Your own cultural background shapes your perception of benefit and harm. How can you actively seek out diverse perspectives?  How do you deal with unpredictability and long term uncertainty?  What is an acceptable risk? How can you incorporate social and human flourishing metrics into your assessment of benefits? When you have a better understanding of _how _you decide what is good, you are much more likely to come to a conclusion that reduces harm.  When you put more thought into how you’re defining good, you’re much better able to consider how to measure it.

Being an ethical data scientist is about continuously asking hard questions, embracing uncertainty, and actively working to minimize harm while aiming for beneficial impacts.


## Where do we go from here?

This is just the first step on our journey to building a future powered by ethical AI! Over the next five posts, we'll tackle each core principle in detail, arming you with a practical "ethical toolbox" to navigate these issues. We'll explore real-world case studies, unpack tricky problems, and demystify the jargon.

Imagine: You're at a dinner party, and the conversation turns to AI. You confidently chime in, not just informed, but empowered to ask insightful questions and propose solutions.

Because here's the truth: Everyone has a role to play in shaping responsible AI. Whether you're an everyday user, a developer, a CEO, or a data scientist, your voice matters. This series will equip you to be an active participant in the conversation, influencing the future of technology for the better.

So, buckle up and get ready to dive into the fascinating world of AI ethics! Let's make the future bright.

This post was made with the assistance of Google Gemini. I use it as an editing and organizational tool after sharing my notes with it, however the ideas, concepts, and construction of the information is my own. I am disclosing this information in keeping with my own virtue of honesty and disclosure. 😊
