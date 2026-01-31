<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Chatbot with Amazon Lex

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-ai-lex1)

**Author:** N SHAMEER  
**Email:** shameernittur@gmail.com

---

## Build a Chatbot with Amazon Lex

![Image](http://learn.nextwork.org/genuine_indigo_radiant_tangerine/uploads/aws-ai-lex1_505be5b8)

---

## Introducing Today's Project!

### Project overview

In this project, I will demonstrate how to create a chatbot using Amazon Lex a service which is provided by AWS. I am building this to master Natural Language Understanding (NLU) AWS ecosystem and create a real-world project

### What is Amazon Lex?

Amazon Lex is an AWS serivce that helps us built chatbot very easily.

### Key tools and concepts

Services I used were Amazon Lex. Key concepts I learnt include " intents", "utterences", "Fallbackintent" and Confidence score threshold.

### Personal reflections

One thing I didn't expect in this project was how easy it is to create a chatbot without any coding experience. 

### Project timeline

This project took me approximately 1 hour to complete. The most challenging part was deciding which voice to go with and also what type of "Fallbackintents" to be set. It was most rewarding to see my bot in action and respond in a way i wanted.

---

## Setting up a Lex chatbot

### Approach to chatbot setup

In this step, I will create a new bot from scratch using Amazon Lex because it provides a clean slate to build a custom logic architecture.

### Chatbot creation process

I created my chatbot from scratch with Amazon Lex. Setting it up took me only a 7-10 minutes due to the streamlined V2 console interface

### IAM role configuration

While creating my chatbot, I also created a role with basic permissions because Amazon lex needs permissions to interact with othe AWS services like Lambda.

### Intent classification confidence score

In terms of the intent classification confidence score, I kept the default value of 0.40. This means my chat bot need to be atleast 40% confident to respond to a user's input.

![Image](http://learn.nextwork.org/genuine_indigo_radiant_tangerine/uploads/aws-ai-lex1_97dc2351)

---

## Intents

In this step, I will trainmy bot to greet users, because i want a friendly experience for my customers.

### Creating my first intent

Intents are user goals that the chatbot needs to understand and respond to. 

I created my first intent, WelcomeIntent, to great users when they say hello or ask for help

### Testing chatbot responses

I launched and tested my chatbot, which could respond successfully if I enter hey, hiya and hello.

---

## Handling unrecognized inputs

My chatbot returned the error message 'Intent FallbackIntent is fulfilled' when I entered "how are you", and " whatsup BB". This error message occurred because my bot could'nt match it to the initially define intents.

![Image](http://learn.nextwork.org/genuine_indigo_radiant_tangerine/uploads/aws-ai-lex1_505be5b8)

---

## Configuring FallbackIntent

In this step, I will customize the Fallbackintent because i would like my chatbot to be friendly.

### When FallbackIntent triggers

FallbackIntent is a default intent in every chatbot that gets triggered when the chatbot doesn't recognize the user's input.

I wanted to configure FallbackIntent because i wanted my banker bot to respond to the users in a friendly manner, even when there is an error.

### My FallbackIntent configuration

To configure FallbackIntent, I customized the closing messages and add variations so it sounds more natural.

I also added variations! What this means for an end user is that they will see slightly different responses each time the bot doesn't understand.

---

## FallbackIntent with Variations

![Image](http://learn.nextwork.org/genuine_indigo_radiant_tangerine/uploads/aws-ai-lex1_c4fc89af)

---

## Initial Responses

In this project extension I'm about to spice up the Fallbackintent with an initial response and add more variations to the initial response. I'm doing this so that to be more familiar with Amazon Lex and making an awesome chatbot.

### Setting up initial responses

Initial responses are greeting or confirmation your chatbot sends right after it figures out your user's intent. I've set up initial responses for a little more humainized experience when the chatbot recognize the intent

### Initial response implementation

The initial response messages I set up are "Hmm this is intresting". For the user, this means that there is more of conversational experience.

![Image](http://learn.nextwork.org/genuine_indigo_radiant_tangerine/uploads/aws-ai-lex1_09bcb9701)

---

---
