+++
title = 'How to learn a new language like a child'
date = '2025-12-22'
draft = false
+++

Hi there!

I hope you’re having a happy holiday season and spending time with your loved ones.

I’m writing in from the Bay Area, where I’ve been spending quality time with friends and family over the last few weeks. As the year winds down, I’ve been doing a bit of zooming out and reflecting.

But let’s save the deep stuff for another time.

For a while, I’ve been putting off announcing a project I’ve been working on.

Partly because I haven’t had energy to work on it between all the traveling. Partly because I didn’t want to become publicly accountable.

The time for procrastination is now over!

---

## Learn languages like a child to reach native-level fluency

Have you been learning a foreign language for a while? Years even?

The first six months of your language learning journey are usually pretty awesome. Going from being unable to understand _anything_ to reading restaurant menus and asking for directions feels like you’re fast forwarding the first 10 years of childhood.

Then, you hit a plateau. _The intermediate plateau._

The intermediate plateau is when you can more or less get by in your target language for daily life. However, when you try to have conversations about more specialized topics: politics, economy, work, literature, pop culture… things become unintelligible again. You struggle to connect with native speakers of your target language.

I’ve hit this plateau more than once. First, I’m talking with a friend about what we want to eat for dinner. Then, we start talking about inflation and cost of living, and suddenly I’m like a phone with shitty signal, breaking up as soon as I try to say something important.

Why does this happen?

The intermediate plateau is primarily a vocabulary challenge. The 2000 most frequently used words in a language make up 80-90% of the words used in daily conversations. But native speakers know closer to **20,000-35,000** words. Which means the gap between going from “conversational” to “fluent and natural across multiple contexts” is HUGE.

The solution? _\*cue cheesy drumroll\*_

Read **native texts** across a **variety of topics**, which helps you acquire the next 20,000+ words to achieve native-like fluency.

---

## Introducing Soryun, the app that helps you read native books

Soryun is built on a couple key learning principles:

- **Motivation from doing something real:** People stick with learning when it helps them do something they actually care about, such as reading a book they enjoy.
- **Comprehensible input:** Learning is most effective (and fun!) when consuming content that’s mostly understandable, but slightly above your current level.
- **Context-driven acquisition:** New words are best learned by repeatedly encountering them in different contexts, giving a more well-rounded understanding of usage than any dictionary can provide.
- **Reading is the highest-leverage content:** An average novel has 70,000-100,000 words, while an average movie has 7,500-20,000 words. Reading is a much more time-efficient way of acquiring vocabulary you haven’t seen before.

**Key features**

- **Immersive e-reader** to make reading delightful, accessible, and effortless
- **In-line dictionary** to seamlessly look up the meaning of new words
- **Integrated flashcards** using a spaced repetition algorithm to maximize new vocab retention

**Stretch features**

- **Personalized content discovery** to find your next read at just the right level of difficulty
- **Learning analytics** to keep track of vocabulary you’ve learned and estimate your current level of proficiency

---

## Devlog #1: Initial progress on building the darn thing

Thank you for humoring my pitch earlier. This next part is for the builders.

So far I’ve got my MVP prototyped in Figma with the basic layout and user journey mapped out. I think it’s okay, but probably not the most elegant, memorable, or frictionless design.

![figma mockup of app](figma-mockup-soryun.png)

<center> <small> The core flow: reading → vocab lookup → vocab review </small> </center>

However, it felt good enough for me to get started on the next big challenge. Coding the darn thing. It’s been a long while since I last worked on a complex coding project, and the app development landscape has changed a lot.

For starters, the tech stack has refreshed:

- **Next.js** is the go-to front-end and back-end development framework now, instead of React + Node.js / Express.
- **Supabase** is the database + backend services platform now, instead of Firebase or hacking together a bunch of different services.
- **Vercel** is the go-to deployment platform, instead of Heroku, Netlify, Firebase etc.

I’ve been spending a lot of time familiarizing with these new frameworks / services, on top of refreshing my old knowledge. It’s been interesting but also frustrating at times.

I really wish I could take whatever idea I have and just make it happen. Alas, when I attempted to one-shot vibe code this project, I realized quickly that AI is currently incapable of making a production-ready app that doesn’t look like a GUI from the 2000s. At best, AI has been helpful for building out small chunks of the app at a time, moving things along when I’m not quite sure where to start, but still requiring substantial review.

So far, I’ve managed to set up basic routing, authentication, and a connection between the front-end to my database.

![app screenshot in dev](soryun-in-dev.png)

<center> <small> Screengrab from actual app in development </small> </center>

Now, I’m working through the gnarly details of modeling the data relationships between different objects (e.g. user and their books), building the UI for adding and viewing that data (e.g. uploading and viewing books), and processing data before storing it for future use (e.g. extracting book metadata like titles, covers, author name).

I’m currently stuck on the processing step 🙃

---

## The future of my newsletter

I know this week’s issue wasn’t my typical reflection + observational musings, but I figured I’d mix back in some craft-related updates every once in a while. The vast majority of my future writings will continue to be my life updates and reflections, but I’ll probably mix in a few more devlogs here and there.

If you prefer one type of content over the other, let me know!

That’s all for now. Hope you have a lovely Christmas this coming week! 🎄

Cheers,
Tim
