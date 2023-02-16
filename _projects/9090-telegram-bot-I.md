---
name: Telegram Bot (I)
tools: [Python]
image: ../assets/projects/telegram_bot/4.jpeg
description: My first real software project
# external_url: https://github.com/YoussefRaafatNasry
---

# Preface
I believe I create one of the most sophisticated and most used telegram bot in Singapore when I released it. Here's somme history of how it started.

# Idea Inception

During the start of the pandemic in 2019, I just finished my year 1 of college and was sitting at home all day. With all that time, I was bored. I do believe that boredom breeds creativity. I had been playing with this idea of a sharing community for the longest period of time. In Singapore, we live so physically close to each other, but we are so socially separated. 

Because we were stuck at home from the pandemic, the problems which that idea of mine was trying to solve became every more prominent. People were unable to have access to regular resources easily. What if we could share the resources we have at home? There came a point where I realized that instead of just fantasizing about that idea, I could put what I've learnt in school thus far to build it out. I decided that it was a worthy project for me to pursue regardless of whether it turns out well or not. There, neighbourly was born.

{% include elements/figure.html image="../assets/projects/telegram_bot/4.jpeg" caption="First logo" %}

# Execution

My plan was to build a telegram bot that will collate requests and pump it to a telegram channel. I got my sister to do a simple logo and poster so that I can put it in the lifts of the HDBs around me. It took me about a month to build the bot in python, connect it to firebase realtime-database and host it on heroku. Once the bot was built, it was time to test it out! This was what it looked like:

{% include elements/figure.html image="../assets/projects/telegram_bot/2.jpeg" caption="First posts on the platform" %}

{% include elements/figure.html image="../assets/projects/telegram_bot/3.jpeg" caption="How to input requests" %}

I remember the first time my sister and I received one of our first orders. It was someone wanting to order [bubble tea](https://t.me/neighbourlySGpendingRd/31) together. We decided to do so and went down to the person's house to collect. It was exhilarating. What was interesting was that the person turns out to be the sister of a friend of my own sister. She never knew that they stayed so close together. This gave me a glimpse at what this platform could potentially become. I started about thinking where else will we be able to use such a telegram bot.

# Mini expansion

The next logical place where I feel this bot will be useful would be my school. Before I could blast a message out to the people in my school, I knew I had to make the bot more scalable. It currently has just 1 bot and just 1 channel. This is essentially 1 write and 1 read channels. This doesn't scale well because if I have n location, I'll need to have 2n read and write channels. To solve this, I had to make a 1 channel system that works for n number of locations. To achieve that, I need to allow everyone to post and receive posts from a single telegram bot. I essentially published the post of a user to everyone 1km around them. Once I was able to achieve that, I sent that out to my school (SUTD)'s messaging channels.

From there, one of my seniors reached out to me to say that they are working on a similar idea and convinced me to join them. Their group is called Scratchbac. This marks the start of part 2 of my journey of building this telegram bot.
