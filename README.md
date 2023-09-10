# Feasibility Testing

## Getting Started

1. Fork and clone this repository.

1. Answer the questions below by editing this readme. Leave the questions and prompts, and answer in between them. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

1. Where applicable, add screenshots, photos, and links.

## Instructions

You will check the feasibility of two app ideas and determine a better option for a 2-day hack-a-thon project.

The hack-a-thon starts on a Friday. You spend 2 hours meeting your group, coming up with ideas, and planning.

The expectation is for everyone to code from 9am to 9pm Saturday and from 9am to 6pm on Sunday, with presentations from 6pm to 9pm on Sunday.

## Idea One: Save the change

Concept: Saving money is challenging, but what if you could do it in small ways daily?

A user will round up the amount spent for every purchase made and put the change into a savings account. For now, the user must manually enter the amounts in the app. But eventually, connecting to banks and credit cards to automate the process would be the next step.

- What technologies are needed?

> react(.js or react native), a banking api, a database(like sql...), an authentification, a server(to run db and other processes)

- Would you have to learn a new technology?

> Yes, sql,rust and python (or java, r...some other programming languages)

- What would MVP look like (use user stories)

> as a user..., 
> i can deposite, 
> and transfer money, 
> also login to draw, 
> can see changes in their bank account

- What are the app milestones

> 1. fetch to the bank api.
> 2. create an authentification.
> 3. password encryption.
> 4. checking their account number & account routing number
> 5. save a data to db.
> 6. transfer money.


- What other things need to be considered about this app?

> app design, 
> a device to run the app,
> a user friendness,

- Is this app idea feasible for a hack-a-thon?

> Yes

- Can you adapt this idea to make it more feasible for the timeline?

> if we have a bigger team, yes.

- How could you encourage users to interact with this app regularly?

> push notifications.

- How could people misuse this application?

> stealing people' personal data.

- Are there any safety issues with this application?

> cyber security relate issues

> **Note**: For a hack-a-thon, imagine you are a team of 4 people, so try to plan the milestones knowing that multiple people are contributing.

## Idea Two: Random Chat app

Concept: People are busy and lonely; what if they could get on a chat app, select a topic, and be randomly matched with someone who wants to discuss the same thing?

A person logs in and selects a topic (houseplants, the weather, the meaning of life) and a mood (cheery, argumentative, silly, etc.). They are matched with another person and can do either text or voice chat. At the end of the conversation, users rate their discussion.

It is anonymous; no pictures, real names, or locations are shared. Once the connection ends, there is no way to connect with that person again (unless they get matched again, randomly).

- What technologies are needed?

> a database (like sql).
> an authentification.
> react(.js or react native)
> a server(to run db and other processes)
> end-to-end encryption
> if we want this app simultaneously, probably some socket programming.

- Would you have to learn a new technology?

> Yes, sql,rust and python (or java...some other programming languages), network layout.

- What would MVP look like (use user stories)

> who want to be annonemous.
> can choose login or not.
> giving less personal info to the server as possible.

- What are the app milestones

> CRUD forums
> socket programming
> end to end encryption
> db
> ui/ux design for pages & app

- What other things need to be considered about this app

> target audience, server population, 

- Is this app idea feasible for a hack-a-thon?

> yes.

- Can you adapt this idea to make it more feasible for the timeline?

> yes.

- How could you encourage users to interact with this app regularly?

> annonemous system to write/read stuffs(giving less info as possible). rating. 

- How could people misuse this application?

> bunch of automatic tools to destroy servers.
> 

- Are there any safety issues with this application?

> community standard.
> filtering an ip (or mac address).
