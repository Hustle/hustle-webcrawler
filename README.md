# Hustle Web Crawler
## Backend Programming Project

Hustle wants to crawl specific parts of the world wide web to discover available phone
number data. Can you come up with a prototype to show the engineering team?

The most basic requirements for the crawler should include:
- Take a list of input urls
- Make an http GET request to retrieve the content of the page
- Parse the content on the page
- Stores any phone number data present on the page.
- Add any parsed out links found on the page to the list of input urls to crawl.
- Repeat the process until the list of urls to visit is empty.

The project is somewhat open ended and purposefully so but make sure to get the minimum
requirements done.

The minimum goal is to get something working that covers all the basic bullet points. If
we can do more than that in 1.5 hours, spend the remaining time however you see fit that
puts the project in the best light. Aim to impress -- we do want to see your strengths. Be
prepared to defend your decisions.

Project prototypes often evolve into real world solutions that need to be robust and
scalable. We don’t expect you to build a robust and scalable solution in 90 minutes. But
we do expect you to give it some consideration and for it to inform your prototype.

We are going to work through this problem with you, we want to avoid getting too far into
the weeds on anything that can be looked up or delivered with a library. If at any time
you are unsure about what is OK to use just ask and we will help any way we can. 

P.S. You can use https://www.house.gov/representatives to seed your crawler.
