---
title: Landing my first job as a Software Engineer
date: 2021-02-08T23:06:32+02:00
draft: true
tags: [interview, coding interview, system design, software engineering]
---



I was always looking forward to my first interview(s). I wanted to see how I could
perform under heavy pressure and how my skills are compared to other candidates.
At the end of November, I started applying for job openings. My strategy was 
simple: I would only apply for openings whose job description heavily
matched my interests, but this condition should be relaxed for positions offered by top tech 
companies. So, in order to get hired at one of those companies, I was willing to accept working on something that did not align completely with my interests and the technologies I am skilled in. That decision was also made because my main language is Go, a technology that is rarely used in Greece.

## __First rounds__

Fast-forward one week later, and I hadn't heard back from any of the companies I had applied for. I was a bit disappointed, but that feeling went away pretty quickly as the next couple of days I scheduled a couple interview calls. I was a lot of nervous, but, at the same time, I had also been prepared for some common industry agnostic [interview questions](https://www.indeed.com/career-advice/interviewing/top-interview-questions-and-answers) which made me less stressed. It turned out that I wasn't asked none of those questions. Instead, most interviewers were asking me about my previous projects,
which I had been working on university. I felt this was great! I would keep talking
about technology and analyze my thoughts about each project with some experienced 
tech people! The fact that I enjoyed the process was a key to my success as I 
passed nearly all first round interviews. 

## __The dream job description__ 

5 days later, and I got an offer! The job title was *Golang Software Engineer* that
would work with, amongst others, *Kafka* and *Cassandra* - i.e. large distributed systems that I am interested in -. That was nearly the perfect job description I could have! But something was wrong. I felt that my skills weren't tested 
as much during the interviews. They had given me a homework assignment which was 
relatively easy and took me approximately one day to finish. Judging from their interview process, I felt that they were making offers without thoroughly examining the candidates and that would perhaps increase their [false positives](https://en.wikipedia.org/wiki/False_positives_and_false_negatives), resulting in hiring average engineers.  Ideally, I wanted to be asked some challenging questions during the interviews and maybe take part in a live coding interview. And suddenly... I had my opportunity! I got an email from a top tech e-commerce Greek company! They wanted to schedule a first call with me.

## __The challenging interview__

Before the call, I was so nervous. Despite I had done that a handful of times before, it felt like it was my first time. I also had read about their hiring process which was very robust. Fortunately, the three interviewers were very friendly and made the whole process less stressful. They asked me some questions about web architecture (HTTP, DNS, TLS etc), which testing types I am aware of (Unit testing, Fuzz testing etc) and some questions about two of my previous projects as usual. I was able to answer the vast majority of them. After 5 days, I got an email from them telling me 
that they would like to proceed at the 2nd round of the process which is a __coding interview__. I had 10 days to prepare so every day I was solving at least 4 [Leetcode](https://leetcode.com/) problems of medium difficulty. I also read the [tech interview handbook](https://github.com/yangshun/tech-interview-handbook) which I highly recommend. At last, the interview day came and the two interviewers presented the problem I had to solve:  

    You have the following three operations permitted on a word:

        1. Insert a character 
        2. Delete a character 
        3. Remove a character 
    
    Given two strings s1 and s2, return whether s1 can be converted to s2 by
    applying at most one operation.

    Examples:
        - ("ball","balle") -> true 
        - ("ball","barl") -> true
        - ("ball","bela") -> false
        - ("bll","bell") -> true
        - ("ball","ball") -> true
        - ("ball","ba") -> false
At first, I was confused and couldn't think clearly but after 5-10 minutes I was able to break the problem into subproblems and the solution came naturally.
Most importantly, I was constantly giving feedback to the interviewers and explaining my thought process while coding. I finished 15-20 minutes before the 45-minute threshold 
which was another plus. The next day we scheduled the third call which was about
__system design__. For this round, I studied from the [system-design-primer repo](https://github.com/donnemartin/system-design-primer). Finally, the day of the third and final interview came. The system that I was tasked to design was a comparison shopping website. Emphasis was given at the database schema design, database queries and the REST API endpoint's design, merely because they didn't expect from a Junior to have extensive knowledge in scaling systems. My performance wasn't as good as the one at the coding interview primarily because of my lack of knowledge about 
web applications and databases design. The interviewer made it clear that if I eventually get hired, I should be putting a lot of effort into learning all these things I'm lacking of. His words made me a bit more skeptical about this position. 

## __The Dilemma__

Do I really want to work on an e-commerce web application written in Ruby on Rails? Probably the answer is no, but on the other hand, I would be working closely with highly talented engineers in an amazing environment. 
Do I want to work with Go and distributed systems? Definitely yes, but on the other hand the working environment maybe won't be as good as the first one.
Clearly, I had a dilemma. In my opinion, on these situations, the best thing someone has to do is to follow his/her *instinct*. 

At the end, I definitely enjoyed the whole *journey*, and surely I gained some confidence.  

## __Some words about the interview process__

There is a big debate on whether the interview process applied by top companies is broken. In order to prepare for such an interview, why someone needs to study things that potentially will be redundant for the actual job? In addition, coding interviews are extremely stressful and one needs to prepare a lot before one. 
But, this approach is quite efficient for the companies, that's why they haven't given up. If anyone wants to join a top company, he/she has to comply. The good news is that anyone who has a problem-solver attitude and loves challenges will also love the types of problems asked in those interviews. 


