---
layout: post
title:  "Don't forget about them..."
date:   2017-04-06 03:20:39 +0000
---

The world of finance has always had an impressive effect on me. As a child when I used to watch my dad execute all the different financial investment vehicles, I was always amazed by and curious about them, and how they worked. This has had a lasting effect on me. Till date, I am always interested in learning about, and trying out different investing options out there, and the new ones that come out every day.

I started my trial and errors with them almost over a decade ago, right after college. Stocks, Bonds, ETFs, Forex Trading, 401k, IRA, REITs, CDs, Peer lending, Money Market - I've tried them all. Some have stayed with me, some not so much.

However, I realized that at times, I couldn't keep track of all of them. Even though most of them were aimed to be *Invest and Forget* (for a short time) kind, they still needed periodical attention. I had tried different ways of keeping track of them by making a note of them, but it wasn't very impressive.

So, for my Sinatra Application, I decided to make a Custom **Investment Folio App** that could keep track of all my (and anyone else's) different investments. A user, after signing up, currently has an option of 4 different kind of investments that they can track - **Stocks**, **Bank Products**, **Retirement Funds**, and **Investment Properties**. They can view all of their investments right on their homepage. They are also able to create new investments, as well as update and delete any of their investments. Along with all that it also includes a feature that keeps track of total combined value of all of the user's investments.

It started out with creating an outline of what I was aiming to achieve from my app. I identified the different types of investment products that I wanted to include for the initial version of this app. Whilst, **Bank Products**, **Retirement Funds**, and **Investment Properties** are almost identical in features, the **Stocks** product is a bit different. It features the *Number* of stock and *Price per Share* of the stock, instead of the plain *Value* as in case of other products. The *Number* and *Price per Share* is used to calculate total *Value* of a particular **Stock** Investment, and is added to the total combined account value.

Considering that this kind of data is something very private to any user, the app uses `secure_password` feature that encrypts the user's password, and is never revealed to anyone. Also, the app would allow the user to view and modify ONLY their OWN investments, and no one else's. Other features include requirement of not being able to leave any fields empty while creating or modifying any Investment Product.

This app is a very simple start to what can be designed into a much more sophisticated, and an even more secure version. In the future, I definitely plan on adding additional investment types, and more features to the additional investment types currently included in the app.

However, with start of Rails Section, I may be moving it all over to Rails :)

Happy Investing!


