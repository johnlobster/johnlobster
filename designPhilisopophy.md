# Web design

When you hire a freelancer, you want the best, most experienced people who will turn your ideas into reality

After spending most of my life coding and learning more languages than I have fingers and toes, I am starting to understand what "experience" should bring and want to describe my "philosophy" for coding and web design

> Everything I do must provide a benefit for my customer

Programming is easy - *don't laugh* - but only if 
- You're the only programmer
- You know exactly what you want and don't keep changing your mind
- It's a small project, with only a few users
- Mistakes are not going to create a disaster
- It doesn't matter too much how quickly the work gets done
- You won't have to come back and change it at a later date
- There are no legal requirements, such as data security or accessability

As a project increases in size, complexity and duration, more and more structure is needed to be able to get high quality, a predictable delivery schedule and meet the customer's needs. By structure, I mean things like
- version control
- documentation (code and app architecture)
- Code libraries
- CSS frameworks, such as Bootstrap, 
- Front end frameworks, such as React, Angular, Vue and Backbone
- Front end/back end communication, such as Rest and GraphQL
- Backend frameworks, such as Node/Express, Ruby on rails
- Back end databases, security and backup
- Testing and deployment frameworks, devOps, Google cloud, Azure, AWS, Netlify
- Data frameworks, such as WordPress, Drupal, JAMStack

> The reason to use tools, frameworks and methodologies is so that the project will meet the customer's expectations. Any particular framework should not be a goal or requirement in itself

### Problems with web design

In addition to common Software Engineering problems, web design has its own issues, such as
- HTML, CSS and Javascript are not perfect. Without experience of their limitations, it's very easy to make mistakes
- There are many different browsers, such as Chrome, Safari, Firefox, Samsung internet and Microsoft Edge. There are some slight differences in how they treat HTML, CSS and Javascript. Many users don't have the latest version of their browser, so the latest features may or may not work
- Users have very different devices, with different sized screens and huge differences in the speed of access to the internet. Apple, Android, Windows and Mac users are used to different User interfaces
- Everything is asynchronous, there are multiple users, multiple button presses, delays when accessing backend services and screens refresh whilst user interactions are still being processed
- Users are increasingly impatient. If a web site doesn't respond within a few seconds, they will move on
- Web sites need to be updated continually to stay relevant and rank high in searches (SEO)
- Security and personal data protection. As technology becomes an essential part of life to more and more people, the return on investment for criminals becomes greater

There are solutions to all these problems - so many solutions that it is hard to pick the right one. It is far more important to understand how a project is impacted by a problem, than to spend a lot of time identifying the optimal solution 

By Software Engineering problems I mean things that are not specific to web design, or even not specific to software
- Identifying user requirements and adjusting to changes 
- Managing risks from introducing new technology
- Managing multiple programmers and designers on a project
- Managing complexity - for extreme examples, consider a Boeing 787, a Microprocessor or a global supply chain management system
- Managing external suppliers. For example, being able to get rapid support for a framework bug
- Managing quality (as perceived by the end user)
- Managing schedule and changes in user needs over time (life cycle)
- Managing all the issues and problems, but still making a profit

There are solutions to all these problems, some of which have been used by Engineers for hundreds of years. Many traditional solutions are not relevant for small software projects

Training as an Engineer brings not just problem solving skills, but a desire to use data to justify a particular solution. This is not always possible in software, but the work by UX people should be a shining example to the rest of us

I have presented a lot of bullet points in this section. Each one can and has been expanded on and used to create PhD theses and management consultancy careers

I do have some very strong opinions on some solutions, but this isn't the place for essays on why I hold those opinions, and yes, it is still all about the customer. For a taster, there would have to be extraordinary reasons why I would choose Javascript instead of Typescript ...

### Agile 

"Agile" is a very hot buzzword and a "must have" on a resume. I'm normally very cynical about things like that, but Agile to me is a breath of fresh air and something from the Software world that could impact other branches of Engineering

> The Agile approach defines a close and flexible relationship with the customer

Although the customer is the most important person, Agile also implies changes to how teams are managed

> Results are more important than blindly following traditional Engineering processes. Teams must be flexible
>
> Continual interaction with the customer is needed, teams must respond rapidly to change

Please note that Agile cannot be used as an excuse for unclear project definition. The more clearly a project is defined, the fewer hours it will take to build, the less it will cost and the happier the customer will be

The Agile "manifesto" itself has four points (my wording)
1. Individuals and how they interact should drive how a project is done
2. Working Software is more important than full (end user) documentation
3. Customer collaboration is more important than negotiating a bulletproof contract
4. Responding to change is more important than meeting abstract deadlines

Equally, the manifesto must not be used as an excuse to reduce code quality, apply inconsistent methodologies or stop communicating

This is all my interpretation, please [read the original](https://agilemanifesto.org/)

The concept of Agile leads to a number of other development concepts, and complete frameworks. The most well known frameworks are Scrum and Extreme Programming (XP).

### Making choices

As a customer, you have a huge amount of choice in selecting a freelancer. Equally, developers have a huge amount of choices in the tools and methodologies that they use. 

The choices made for a small task, such as upgrading a small website to be mobile friendly, are different from the choices that would be made for a complex tasks, such as a FinTech app that has high security, meets government standards from multiple nations and guarantees keeping user data intact for 100 years

An experienced developer must be able to understand a customer's needs and explain how each technical choice benefits the customer

------------------------

### Frameworks (Appendix)

I've added my opinion on Javascript frameworks, as it is a subject that developers spend a lot of time discussing

<table>
<tr>
  <td>PlayStation</td>
  <td>XBox</td>
  <td>PC</td>
</tr>
<tr>
  <td>React</td>
  <td>Angular</td>
  <td>Vue</td>
</tr>
</table>

If you spend any time online, you will hear arguments over the products in the first line. Developers can be equally passionate, eloquent and entrenched when it comes to Javascript frameworks

A Javascript front end framework, and there are many, addresses key needs for program structure, such as
- Encapsulate HTML, Javascript and CSS for a "component" into a single place. This is essential for managing complexity. For the customer, this means code that is written more quickly, can be changed more quickly in the future and will have fewer bugs
- create a consistent hierarchy, with explicit data and control sharing between different levels. For the customer, this means faster development of complex projects
- manage asynchronous behavior by creating formal, consistent connections between actions and their effects. For the customer, this means fewer bugs and faster development of complex projects
- a development environment that enables rapid iteration. For the customer, this means faster development
- a consistent build mechanism. For the customer, this means releases are quicker and more consistent in quality, despite any growth in code size and complexity

As with anything else on the web, frameworks change continuously. Any technical comparison between frameworks is usually out of date within three months as new features and libraries get added

As you may have realized, I can only make sense of "web technologies" by relating them back to the customer. In my opinion, there is a huge difference between using a framework and not using one and the differences between  frameworks is very small in comparison

I find it hard to think of legitimate reasons to favor one framework over another. Here is all that I can come up with
- The customer already has an existing website with a specific framework and it is more time efficient to modify that than start from scratch. Cost to customer is reduced.
- The development team already has a similar project to the one the customer wants and can copy it, reducing the customer's cost


