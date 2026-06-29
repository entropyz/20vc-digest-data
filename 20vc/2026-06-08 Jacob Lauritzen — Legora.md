---
type: 20vc-episode
guest: "Jacob Lauritzen"
company: "Legora"
role: "CTO"
episode_type: interview
date: 2026-06-08
youtube: "None"
transcript: "https://20vc.substack.com/api/v1/file/319452eb-b7ac-44da-9d7a-61cdcbb221a5.pdf"
newsletter: "https://20vc.substack.com/p/20vc-newsletter-7th-june-2026"
tags:
  - 20vc
---

# Jacob Lauritzen — Legora

> CTO @ Legora | 20VC Interview | 2026-06-08

## Key Takeaways

---

## Links
- [Watch on YouTube](None)
- [Full Transcript (PDF)](https://20vc.substack.com/api/v1/file/319452eb-b7ac-44da-9d7a-61cdcbb221a5.pdf)
- [Newsletter](https://20vc.substack.com/p/20vc-newsletter-7th-june-2026)

---

## Full Transcript

Harry: [00:00:00] What percent of developer salary would you be willing to
spend on AI tooling for them?

Jacob: I don't want to say infinite, but for me it's a question of opportunity cost.
we are in a competitive environment,

so many things that we can do the cost of not doing it is extremely high and it's
almost outweighs any sort of token cost.

Honestly just work harder than the 800 pound gorilla. people underestimate this.
Like No one in the 800 pound gorilla is extremely excited to be there.

Harry: This is 20 product with me, Harry Stabbings. Now I'm so [00:00:30]
excited to welcome Jacob Lures and CTO at LA to the show stay. Lara is the
fastest growing enterprise company in history. They hit a hundred million in a
RR in just 18 months. They're gonna finish this year at two 50 to 300 million.
I'm pushing them to do 300 million because, hey, I'm an investor and it's easy to
throw peanuts from the side.

But Jacob is one of the best product minds I've had on the show, specifically
from the last crop of product leaders in this AI generation. Time to get the
notebooks out. It goes quite deeper [00:01:00] into some pretty granular
technical aspects, but this is a must listen.

Harry (Adverts): Before we dive into the show today, you know what's wild?
We have AI superpowers. Now, yet so many product teams are still flying blind,
buried in spreadsheets, chasing feedback across 10 different tools. Jira product
discovery fixes that I've spoken with. Hundreds of product leaders and the best
teams all do one thing differently.

They build a system to capture ideas, validate them with real data, and focus
their roadmap on the right things. Well. That's why product teams at [00:01:30]
Canva, Deliveroo Toast and Decathlon use Jira product discovery. It pulls ideas
and feedback into one place with built-in tools to prioritise what'll have the
biggest impact.

That's when a roadmap stops being an endless list of ideas and becomes a plan.
People actually believe in join more than 25,000 teams already using Jira
Product Discovery. Head to atlassian.com/harry and start building the right
thing today. While Jira product discovery turns feedback into priorities,
[00:02:00] fin turns questions into instant answers.
As AI agents become more common in customer experience, teams often end
up juggling multiple silo tools for every job. Well, FIN was built to change that.
It's a single unified agent that works across your entire customer experience
from service to sales to success and beyond. Finn is the agent making perfect
customer experiences possible for thousands of customers, is powered by
customer models, trained on years of real customer interactions, so it
understands the [00:02:30] nuance and complexity of customer service better
than any other agent.

That means faster resolutions, more consistent support, and just better
experiences for every customer. It's also designed to be fully self manageable so
you can easily improve and adapt it as your business evolves. No third parties
required leading companies like Gamma Asana, DoorDash and crypto.com
already use and love fin to deliver better customer experiences.

So see what FIN can do for your team at fin.ai/two zero vc. [00:03:00] While
fin helps answer the customer, framer helps impress the next one. You know
that moment when marketing wants a landing page design, mocks it up, and
engineering says, yeah, we'll get to it. Thousands of businesses from early stage
startups to Fortune five hundreds a choosing to build their websites in Framer
where changes take minutes instead of days to solve this very problem.

Framer is an enterprise grade no-code website builder that works like your
team's favourite design tool, and it's used by companies like Perplexity, Miro,
[00:03:30] Mixpanel to move faster. Designers and marketers can fully own the
site with real time collaboration. A robust CMS built for SEO and advanced
analytics that include integrated AB testing.

So you are not just shipping pages, but you are maximising what works and
when you are ready to ship changes, go live in seconds with one click. Publish
without relying on Engineering. Plus framer is built for scale with premium
hosting, enterprise grade security, and 99.99% uptime [00:04:00] SLAs.
Whether you want to launch a new site, test a few landing pages, or migrate
your full.com framer has programmes for startups, scale ups, and large
enterprises to make going from idea to live site fast.

Learn how you can get more out of your.com from a framer specialist or get
started building for free today@framer.com slash 20 VC for 30% off. 30% off
of Framer Pro Annual Plan. That's framer.com/two zero VC for [00:04:30] 30%
off. framer.com/two zero VC rules and restrictions may apply. You have now
arrived at your destination.
Harry: Jake, dude, I am so excited for this. I think Max is one of the most, do
you know what? I think it takes a psychopath to no one. Uh, and he's like, fuck
you, Harry, already. but he's just exceptional. I know the bar of talent that he
has, and so I know that this show is gonna be amazing. So first, thank you so
much for joining me.

Jacob: Yeah, of course. Thanks for having me.

Harry: [00:05:00] Now, we were just chatting and you said Lago is the first
kind of big company or like company of this size that you've worked at, and I
was thinking, is that a blessing or is that a curse? How do you think about that?

Jacob: I would like to think that it's a blessing. I just have to be really humble
about it. So essentially, I don't have any priors coming into how to build an
engineering org. building an engineering org in 2026 is very different from
doing it in 2024, maybe even.

And so I think, in that way it's really good that I come in [00:05:30] naive and
I'm like, okay, let's try to do it this way. And if it doesn't work, we keep
iterating. Just like we keep iterating our product. We keep iterating on sort of
organisation and our processes. And I, just work with the team, like, what's,
what's working well?

What's not working well? How do we solve that? Just like any other problem.

Harry: Dude, how is it different building a team in Azure product in 2026
versus 2024 and years prior?

Jacob: everything's just changing all the time right now. You know, the
productivity is through the roof. processes are up in the [00:06:00] air. you can
be huge teams.

You can. be tiny teams.

Harry: productivity is through the roof.

Jacob: Yep.

Harry: If we unpack that, why is it through the roof?

Jacob: Well, just AI tooling,
Harry: It's simply like, what do we use internally?

Jacob: is Clark code, it's cursor.

Harry: It's you use both competing? Yeah.

Jacob: Yeah. Yeah.

Harry: cause everyone's like run from cursor whenever I interview them.

Yeah, yeah. So you still have cursor users.

Jacob: users? We still have cursor users. the cursor harness is quite good. you
know, there's, personality differences on our team, but, but a lot of people still
use Cursor. some use cloud code, some use pi ' cause cloud codes [00:06:30]
harnesses is annoying sometimes.

we allowed people to do both.

Harry: Okay. And so we have like efficiency against that, and so we just ship
more.

Jacob: We ship more, we ship faster. we debug things faster, we iterate faster.
Everything is faster now, and each engineer can produce much more than they
could previously. and that just has a tonne of ripple on effects throughout the
org basically. And how you're structured. 'cause I mean I think it a, a way I like
to think about it's, when you build software, there's kind of like three phases.

There's phase one, which is the product work, you know, what do, what
[00:07:00] are we building? translate pain, user dreams, nightmares into
something tangible that we can try and we can iterate on and, and we can figure
out if it works. Then once you have that, you know, sort of what you want to
build, then you built it, you write the code, then, you review the code and you
merge it and you, you get it going. And two was the primary bottleneck for the
past a hundred years, almost. so like the rate limiter was how quickly can you
write code that is now super cheap? So that's sort of been compressed. And so
the, the bottleneck now is like the, two other ends, which [00:07:30] is, review.
How can we do that much more efficiently? and then it's how can we actually
do the product piece much more efficiently? 'cause you know, if you believe
that code is cheaper to write, then naturally the two other things are bottlenecks.
And that means, one of the focus areas is how do we do the product work as
efficiently as possible?
Harry: How do you think about that then?

Jacob: That's a great question. part of that is, how do we make our PMs as
efficient as possible? How do we sort of take all the, working with clients,
synthesising what they think, our own strategic priorities, our own taste and
[00:08:00] opinions of our vision of where, you know, our product is going.
how do we make them do that as efficiently as possible and hand that over to
engineers as efficiently as possible. I'm not sure if I've solved that yet. but I do
think it's like, the way that I'm thinking about it is constantly what's the
bottleneck to our velocity, and then we try to solve that.

Harry: you said about the kind of review being one element of it that could be a
bottleneck. Yeah. Do we see AI code review becoming the dominance source of
review, and does that then remove it as a bottleneck?

Jacob: I think so I think that's one of the solutions. we do AI code [00:08:30]
review today and it's, in its nascent face. It's, you know, as you put it

Harry: It's like when I was fat, when I was young, my mother used to just say I
was big boned.

Jacob: Okay. Yeah,

Harry: Okay. Yeah. And it's

Jacob: It's the

Harry: just ate all the malteses, Harry.

Jacob: it's

Harry: in its nascent phases. Sweet.

Jacob: That's the yeah, that's the nice, yeah, rough. It just still, but no, I
completely, I I I think that's right.

I think that's part of it is, we have AI review bots. You can have like security
review, you can have different specialised reviewers. They do about tonnes of
review and they sort of iterate with the AI coder and it's like kind of [00:09:00]
weird 'cause you see this pattern where it's like agents fighting each other until
they arrive at something. but even then, I think current review tools are not good
enough, I think we need something new. I keep telling people events that I'm at,
like, if you're gonna do a startup, please do something that solves the review
thing. cause no one wants to look at the all the lines of code.

what's important is what's the impact on systems architecture, what's the impact
on systems design, stability, security boundaries? How does it sort of take our
system in the right direction? That's the kind of stuff that you [00:09:30] want to
review. And if that doesn't change, then maybe you don't have to review it at all,
just, you know, unleash the agent.

But if it does, if there are some strategic trade-offs, want a human to be like,
yeah, this is the right directions to take.

Harry: That the future of engineering being systems design, systems
architecture, and then bluntly, code creation, code maintenance, is actually
completely done by ai.

Jacob: think so. I think so. I think that's right. The job of an engineer is
changing from a bunch of code to sort of one layer above it, which is, does the
[00:10:00] system look like? And then you can have AI running around inside
each of the pieces of the system. But you sort of have engineers thinking about
the higher, level one abstraction above, which is like, what does the system look
like?

What are the bets we're making in different places? Do we wanna invest into
doing something here that we can reuse a bunch of places over here and it's
gonna make everything much more stable? one of them. I think the other thing
that engineers are doing more and more, which is an explicit role with us soon,
which is like kind of the meta engineering of making agents really effective.

So, you know how you have developer experience [00:10:30] teams

that.

they might help ride custom linting or custom developer setups to make
developers efficient. we kind of need to have the same team for agents. Like
how do we make agents really, really effective? How do we make sure that we
can enable agents to independently self-improve the system?

Can we, can we gather data in a really good way so that we can just unleash
agents and say, Hey, increase, conversion rate on my e-commerce store and it
can just like, go and run experiments that sort of setting up the loop so agents
can just like run and, optimise. I think that's gonna be, uh, the actual job of a lot
of engineers.

Harry: How do you [00:11:00] think we do that? I, I, I spend a lot of time with,
Jason Lampkin and Anthony Mitre, who's amazing, but they, they both told me
that fundamentally, you know, in a world where agents are the pickers of
software, the API quality that we have is the core determinant of what agents
will choose software based upon.

How do you think about how we make agents more effective? Is it a simple
question there of data and making sure we're the best at that? How do you think
about that?

Jacob: we have to set up the guardrails really effectively. This is actually
something that I'm thinking about right now.

So our code [00:11:30] base is starting to get large happens. It's a good problem
to have. we're starting to be a lot of engineers. We're also starting to be a lot of
agents that are working on this together. And so, you start to think about how
can I mechanistically enforce the system to behave a certain way? And, and so
I'll try to give an example here, which is, you can have custom rules, for
example, which is like the agent tries to do something and we tell it, no, you
can't do that. You know, there's like, for whatever reason you can't do that.
'cause we want the system to be in this way. And I think that type of, guardrail
setting will see everywhere. [00:12:00] And so if you're a big enterprise and
you're rolling out AI tooling and you, you have agents that build your own
internal software, you know, you have AI tools that build your, H-R-R-I-S
system and your, you know, a TS system and whatever else, you probably have
some engineers that are just setting up the, like, this is where you get the data,
this is what you can do, this is what you can't do.

And then you can just let agents run amok inside of that system basically.

Harry: you mentioned the expansion of the legal, code base today. what
percent of code created today is AI generated versus human generated?

Jacob: actually [00:12:30] I took a look recently and clawed in cursor on the
top and there's like, it's like 2% between them. So they are really, really close.
and then it's, you know, miles above the next engineer. So they're way above
50%.
Harry: You worry that we will see a next generation of security threat with the
amount of AI generated code that opens. Vulnerabilities we didn't know we had.

Jacob: Yes, This is, uh, very top of mind for me and that's why we still at Lara
and, and probably in a bunch of other enterprise software, we, we still
[00:13:00] review human prs every single one just because we have to be sure. I
think that's an efficient, I want to, you know, get some risk scores in there and
change that so that we can run really fast.

But, fundamentally, I think you're right. I think actors, are extremely efficient
now, which means like they can try so many different things and they can keep
running at it. and so we need just as, um, good defence and I'm not sure if we're
there yet.

Harry: Definitely don't think we're there yet. Yeah. Which is why we see so
many hacks. And so whenever I see the hack on Twitter, I'm like, oh, [00:13:30]
poor and name the founder. I'm like, oh, it's their weekend is thoroughly ruined.

Jacob: yeah, yeah. I, I,

had a security in, oh, not me, one of our vendors had a security incident just
yesterday. We just rotated all out. Yeah. I mean, just, you know, to be clear, this
was internally doesn't, doesn't affect any of our clients or anything like that, but
it's just, I think we're gonna see more of them.

Harry: Yeah. Yeah. No, I totally get that. I interrupted you when we spoke
about the efficiencies earlier that comes with ai, you mentioned the second was
the processes that change. How do processes change? Be it prs, be it [00:14:00]
postmortems.

Jacob: actually postmortem is a great example. We run them really efficiently
now. it's great. Uh, you know, if you have an incident now you just unleash an
an SRE agent, and, and a sort of, uh, an incident agent and it'll just super
quickly figure out what's going on. Look at all the locks, look at all the metrics,
telemetry.

And it's It's really, really good. And so, like instead of having a bunch of
engineers wake up in the middle of the night, you still have some waking up in
the middle of the night, but they are, really well equipped and the postmortem
basically almost writes itself as well. so that's actually a great example of
something that we can run really efficiently. but I think more broader and
[00:14:30] sort of the software development lifecycle with ai, PMs can
prototype super, super fast, which is really, really great. 'cause that means you
can front load a lot of the work. So like a PM can start however long before,
once he or she has the, you know, smallest inkling of an idea that we might
wanna do this, they can prototype it and they can just go to users and they can
test it and they can iterate themselves.

They don't even need to bring in engineering until they have something that's
like clearly super valuable. And then we can switch and we can say, okay, now
we take this from prototype to something that's like actually, in [00:15:00] the
system and is super reliable.

Harry: Do we skip the design stage in a world where prototyping and getting to
V one is so much easier?

Jacob: yeah, that's a great question. Probably some companies will skip the
design phase. I think we can skip the design phase on functionality. you don't
need to necessarily have this long, you know, discussion, where you said 10
people need to figure out where should the button be?

I do think design still has a place, but it's you know, one level above the
individual feature that the individual stuff that we build, it's [00:15:30] the,
language that we choose to have.

It's the taste, it's the, opinionated stance we have of who we are and like, what
does Lara look like? what's the navigation? What's the hierarchy? but it's more
for consistency, ux, ui sake and, and for taste's sake rather than, functionality.

Harry: Do you still use Figma today?

Jacob: We still use Fig Me? Yes.

I know where you're going with this. I think as soon as you start building a
system that's larger than something very small, consistency and you want, to
have a design [00:16:00] language and all that kind of stuff.

And so you need somewhere to store what your button looks like and what your
like pages look like and what's this and what's that. and for us that's Figma and
it works great for it

Harry: Do you think that's the case moving forward? I don't mean anything
against Figma, but it's like That's like a storage feature.
Jacob: no, exactly.

Harry: Yeah. For design files.

Jacob: else. Yeah, you're right. Then the question is, is it faster for designers to
take a prototype to something really crisp in Figma versus prototyping?

Harry: We mentioned the wonderful word earlier that's said the word of the
moment, which is taste like, Taste is what separates [00:16:30] us. How do you
think about the, don't worry, taste is what the differentiator will be. Is that true
or is that bluntly? Silicon Valley in Tech Bs that's trying to protect us?

Jacob: I think taste is important. There's different flavours to taste, pun
intended. it depends on what you mean with taste. I think you know, in tech
taste is like we have an opinionated stance on something. I think if you don't
have taste, then you let ai slop converge to sort of [00:17:00] greyness and, and
everything looks the same.

And everything's just like, you need to have taste to have sort of an, and it
stands in the world,

this is who we are, this is what we do, and, and we don't do these other things.
And that's not for everyone. I think to me, that's what taste means. It's like, this
is who I am, this is who we are. And, and some of you're gonna hate it and that's
okay. because you need to have some You know, if you're just like letting AI
rip, you're gonna look the same as everyone else.

Harry:

When the cost of copying is quicker than ever, does that change how you think
about product? You're in a, a very competitive space and [00:17:30] buying
people can copy you very quickly. Does that change how you think about
product?

Jacob: no, not really. the important thing for us is that we're building something
that our clients get a lot of value out of, and we build that as fast as we can, but
we don't build it faster than that. there are, there are tonnes of people that are, by
coding, you know, there's people that are vibe coding Lara, there's people that
vibe coding Salesforce and, and, and DocuSign and other companies. quick to
get to the 90% where it looks the same and, and in like 80% of the cases it
works. Similarly, it's the other 90% that are difficult. You know, it's [00:18:00]
like ensuring all the edge cases work and all the unhappy paths and all the, audit
locking and all the R back and all the, weird scenarios that you end up at, at a
certain scale. That's what's difficult. so no, we just, we keep focused on how do
we create the most value for our clients and sprint towards that as fast as
humanly possible.

Harry: my girlfriend is a lawyer and she's wonderful, but they're not the fastest
in terms of adoption and usage. I'm gonna get in huge trouble for saying that I
was not talking about her, I was talking about the legal profession. Okay, good.

Jacob: good.

Harry: [00:18:30] Um, you can build product so much faster than your
customer can consume it.

Yes.

Jacob: Yes.

Harry: How do you think about that?

Jacob: That's a great question. We have this notion internally that there's the
speed of, ai, there's the speed of our product, and then there's the speed of
humans, you know,

Harry: And they're like,

they're not,

they're not the same necessarily. Yeah.

Jacob: think that's part, honestly, of the beauty of what we're doing is that we're
translating the immense speed of AI development into a user base that's been
historically underserved. we're sort [00:19:00] of taking them along for the ride.
it can be frustrating, but it's also really, rewarding we can actually take this huge
base of people and we can really change the way that they, work and their
efficiency and their productivity, and we can remove butt loads of work that
they've spent their time doing and focus on the more strategic, more important
work.

Harry:
What have you not done that you wish you had done?

Jacob: email client would've been really cool. I would've loved to build that.

I vibe code one, just for fun. probably a few ways, you know, we're a little away
from that [00:19:30] 'cause there's other high priority things, but I think an
email client is where our lawyers sit a lot.

Harry: You vibe code internally within Lara for customer presentations for you
name it.

Jacob: Constantly.

Harry: Is that the future of enterprises or is that bluntly Lara at the very
precipice of innovation.

Jacob: It will be the future. I dunno when, but it will be the future. I think
there's like.

Harry: Just so we understand, like what does that mean? you build sites for
slaughter and may, so you can picture them and Clifford Chance so you can
picture them.

Jacob: but it's, it's [00:20:00] way broader than that. It's like we have a a, a
team now that's internally AI enablement, which is just like re-imagining, you
know, again from first principles with all the stuff that we have today. If you're
building the most efficient company to go from let's say 200 to a thousand
employees, does that look like? And that means obviously, you know, cla
cowork and similar things for everyone. But it's also like, can we just build a
bunch of the tools that we need ourselves? Can we just vibe code a bunch of the
tools? Can we vibe, code our, system? Can we vibe code our acquisition
system? Can we vibe, [00:20:30] code our payroll system?

 like so many things where tools exists out there, but you always need to
customise 'em so much and they always basically never really work. And we
just built them out 'cause it's so cheap to build.

Harry: What have you been able to vibe code away?

Jacob: well we've added a bunch of things that are additional or additions to
vibe coding. So great, really stupid example is, Ryan who joined from Canada.
We have a team of people joining from Canada. They're all moving to Sweden
and he vibe coded, an app to help everyone migrate. So it's like very specifically
if you're Canadian, these are like all the laws and all the steps you [00:21:00]
take and there's like, it's interactive and you can see how far you've made it and
it's awesome. And it took, I dunno, a day to vibe code and it saves so much time
for an entire team. So it's like you can build the big systems, but even just all the
small ones that you can build, really add up.

Harry: I was with a, a friend who's a public company, CEO the other day, and
he was like, you know, my chief of staff took three weeks off and basically vibe
coded Cooper and we replaced Cooper. and it's works and it's brilliant. What do
you say to people who are like, that's ridiculous. Why would you ever bother
vibe [00:21:30] coding and taking months to do an HR system when you could
just buy it off the shelf?

Jacob: it really depends on the system. let's say there's two axis to systems.
There's, there's the, the horizontal one, which is like, how big is your, product
surface area. And there's the, the, the vertical one. Like how complex is it? So if
you're deep, you're essentially a surface area. It looks quite similar. It's a simple
app, but it's just a lot of complex stuff. It hides away a lot of complexity to the
user. And there's the other one, which is your very, very shallow app, which is
like tonnes of things you can do, but there's not [00:22:00] that much
complexity. If it's a shallow app and it requires a lot of customization from you,
maybe you just build it. That's probably the right thing to do. If it's a very deep
one, there's just too much stuff for you to build and it's not viable for you to do.

Harry: we, we mentioned PMs and like their proximity to customers and then
that delivery mechanism back to engineering, which is kind of always what
PMs did and did best. Does the role of the PM change in the next few years?

Jacob: Yes and no. think there, there are certain people that are, or a lot of
[00:22:30] people are saying that product and engineering are converging. It's
becoming one thing. It's like one person can, do the product work and build the
engineer, like build the system and, and ship it and everything. And I think for
some companies that's true. I think for companies where you really need PMs,
it's not true. Or it can be true, but it's inefficient. And I'll tell you why. So we
were talking about, product, you know, you do the product work first, the
scoping, and then you built it. And then you, you you ship it and you review it.
And a company like Agora we're always focused on the bottleneck.

And the bottleneck is no [00:23:00] longer coding, which means the bottleneck
is the product work. And so you don't want your product people to do
engineering ' cause like the opportunity cost of that is really high. 'cause what
you really want 'em to do is the product work. Like talking to customers,
figuring out during the synthesis, that's the bottleneck.

So if, if your PMs are coding a lot, if they're spending 50% of their time coding,
we're missing out on so much product work. So that's how I think about it right
now. And for certain companies, if you're doing developer tooling or doing
consumer where engineers have a good sense for their own or their are their
own clients, you maybe don't need a PM at all.

'cause [00:23:30] like you haven't needed a PM before AI either there. So I don't
think that changes with and with, without ai, PMs can now do engineering, that
changes with ai. but it's not always efficient to do it. It's like a matter of
opportunity cost and there's handover cost, is, if I do all the product work and
then I give a PRD and I give it to an engineer, then like you lose efficiency
there. it's good if PMs do some amount of vibe coding to like show very high
fidelity, here's a prototype, this is exactly what it looks like.

Harry: Reduce the handover cost.

Jacob: Yeah, exactly. But they shouldn't spend a lot of their time [00:24:00]
engineering if they just like focus on actual engineering, we lose out on, uh, the
product work.

Harry: I'm your little brother coming out of CS at university. What would you
advise me to be best placed in the next three to 10 years? So if I were to advise
someone on social media marketing, I'd say, Hey, you need to be full stack. You
need to be able to create the image, get it out, and amplify.

Jacob: Yep. Similar thing I think, I think actually the most important thing is
you need to learn to learn. need to, to, to [00:24:30] figure out how you
constantly reinvent yourself and, and, and, and keep learning and, and improve.
because the things, things change all the time right now, it's, it's every week
there's something new you should be doing.

You need to change your way you're working or whatever. the most important
thing that you can do for yourself is figure out how you keep at the forefront of
what's happening all the time. and if you can do that, if you're adaptable enough
and you are ambitious enough, then the rest kind of works out. ' cause if you can
just learn faster than everyone else, then you know, over time win.

Harry: What extent does the [00:25:00] quality of Lago as a product depend on
the quality of the underlying models?
Jacob: much less than most people think The value of Lara is there's so much
more around it. whether it's like the, the primitives that makes sense for legal,
that make it more efficient to work with ai or it's all the enterprise features, or
it's the optimal routing between models.

we wouldn't exist without the models. and every time the models become better,
our product becomes better, our agent becomes better. But, let's say you took
away a model from Lago. People would still [00:25:30] pick Lare, so they don't
buy it based on the model.

Harry: How has model usage changed for you over time?

Jacob: it changes a lot. I mean, the best model changes biweekly, we've been
between OpenAI and Anthropic, we keep evaluating all the different models

Harry: do you, do you use like 15 at the same time for different tasks?

Jacob: not 15, but yeah, maybe 10.

Harry: Yeah.

Jacob: yeah. So, so for each task we will evaluate what model is best at this
latency performance. Not so much cost. Eventually it will be cost, but latency
and performance is most important. Uh, you know, performance needs to
[00:26:00] be here. how much can we increase latency without dropping in
performance? by building our agent and our other AI features in a way that you
can decompose the problem, you can use really efficient

Harry: You can have latency or performance at the fastest, but it may not be
the best output or slower, but fucking great output. Yes.

Jacob: Yeah.

Harry: Which one?

Jacob: I have to

Harry: Yeah. Uh, life's the game of trade-offs.
Jacob: always. Performance. is more important. Almost always. If you're a
lawyer, you can wait two seconds more for the output. If it's better, you can
[00:26:30] probably wait an hour more for the output if it's better.

Harry: What do you, I'm just fascinated. Now, what do you think about the
future of open source as we do move more and more to a focus on cost?

How do you think about that?

Jacob: I think open source is having a great moment. really is. There's so many
great open source models now, and they're really easy to run. There's great
inference providers that let you run really efficiently. We are moving very close
to being able to do things on device.

I mean, transcription can, can run on device, can run on my iPhone. I have local
transcription on my [00:27:00] Mac. when I, when I do flights and there's no
wifi, I have local models running so I can keep coding, but it's just like a, a
Gwen model that runs and helps me code. so I think open source is gonna play a
huge role.

I hope it continues to, to, to evolve the way that it currently is. And I think it's
an important thing that we have open source model for sovereignty reasons and
for like security reasons. We should have great open source models.

Harry: Can I ask what worries you today? A lot of people are worried about the
open source Chinese models, which is why I was kind of thinking about it more
broadly. What worries you when you look at the landscape that we've
discussed?

Jacob: I really [00:27:30] hope to see European and American open source
models they've been lacking. And I think it would be really, really good to have
some, theoretically, we won't end, um, end up in a great place if there's a
duopoly or monopoly on the models for obvious reasons. you know, you do
want to have some mentation, you want to

Harry: Does Europe have any place to play in the model race today?

Jacob: It should, but it doesn't yet.

Harry: How far do you think are we in the efficiency frontier on training? Are
we like 1% of the way there or is it like, ah, we're 90% [00:28:00] and like, we
might eek out some little bit more?
Jacob: Great. That's a great question. one thing is just like the current
architecture, how long does that, you know, does that plateau? Do we need
something new? I mean, there's a one, uh, a model released two days ago, uh,
that's sub quadratic, which is huge context length.

That's super exciting. I don't know if I trust the benchmarks yet. You know, we,
we need to validate that. But, there's architecturally, innovations going on still.
And I dunno, maybe the, the, current LLM architecture's not the right, the ones
who take us all the way.

Harry: role [00:28:30] does not exist today that you think will be very common
in five years time?

Jacob: I think the internal AI systems role thingy for enterprises, I think it will,
can have like a flowering moment here and you know, go from being it that's
like setting up your computers and whatever to to, maybe have a assisted team
that's building a tonnes of internal tools that just make your life so much easier.
if enterprises don't create that role, I will get really annoyed 'cause there's so
much efficiency to gain [00:29:00] there.

Harry:

Really getting into the enterprise and having all of that for them, do you have to
have FDS to have usage in enterprise? You work with relatively sticky lawyers.
Yeah,

Jacob: yeah.

Harry: Do you have to have people show them? Here you go. Here you go.

Jacob: We do. Yeah. but I think that's just, that's an education thing in five
years maybe. We don't at all that's the price you pay from being, for being, you
know, on the forefront. You, you have to educate and you have to help. why
people wanna work with us Also.

Harry: You ready for an unfair one? Yes.

Jacob: Yes.

Harry: What have [00:29:30] Harvey done better than you from a product
perspective or an engineering perspective?
Jacob: they've been more aggressive with hiring, I have not been aggressive
enough with hiring. 'cause I've, I've always tried to have a very, very small, very
lean team, which I believed a lot in. I consistently underestimated how many
people we need to be.

I had this slide that I drew up, year and a half ago that I showed the entire
company and it was, you know, the 300 spots versus the Persians and it was like
Lara and the 300 spots. And I said, I'm pretty sure I said we will cap out at 20
engineers some, something like that, [00:30:00] which is like way
undershooting it. Um, how many

Harry: engineers do you have today?

Jacob: Today we are about 80.

Harry: Yeah, you got that wrong on 20, didn't you?

Jacob: yeah, I got that really wrong. And we're way too, we're way too small
still.

Harry: As a result of being too small, you are too slow or you are not able to
build what you want to build Second.

Jacob: there's loads of features that we, you can basically staff a team to build
that

Harry: Can you ramp as quickly as you need to and retain quality?

Jacob: Yes. We're really good at this

first we're extremely selective with [00:30:30] hiring. Maybe that's also why
we're slower at hiring. So we hire really great people and the ramp up time is
extremely fast.

Harry: Do you make ramp really fast as specifically as possible? Anything that
you do?

Jacob: I can tell you what we probably should do

Harry: Sure. Good.
Jacob: like the reality is things move really fast. you need to have, we have a
developer experience team, relatively new. Again, a mistake I made, I should
have staffed that earlier. and they are making everyone's life so good.

Harry: What do they do?

Jacob: So they make sure that our local [00:31:00] development setup works
really, really well.

It's super fast. It spins up really quickly. We have our own background coding
agent that they built that allows each engineer to have like 10 different agents
running concurrently with like all of our local development, a browser, all the
iteration stuff. They're building custom review agents. They're building features
so that it can wait and see and wait until everything looks green and all the
reviews are good, and then raise it to a human.

the efficiency gains there are huge. And they will then also build tooling that
helps onboard people. And so it can just be like, make sure that you have really
good [00:31:30] README files in your repository so that a new engineer will
just ask their cloud code or their cursor about all their questions. Like that's
remarkably effective. So it's just like, even just AI tooling makes it faster to
ramp.

Harry: How many do you have in developer experience and when do you think
you should have done it?

Jacob: We have three people now, which is too few. I should have done it,
when Oprah 4.5 came out, I think, because that's when I should have done it
before that. But then, you know, the, the productivity of each engineer, 10 XI
say. And [00:32:00] so if you can make everyone 20% more efficient, it's, it's
even more games.

Harry: Does hiring engineers in Europe differ to hiring in the us?

Jacob: there's a few different ways the us People are less risk averse, so like
they'll, they'll be ready to jump on a lot of things to, to, to test. I think in Europe
people are more risk averse. People in Europe, are more, I don't wanna call
them mission driven or loyal, but they're like, they really buy into the company
that they work for and work with. [00:32:30] so it takes a lot of time to convince
them, once they're convinced, they really stay that's great.

Harry: NUS is more transactional, I think.
Jacob: so. Yeah.

Harry: Do you find the attachment to equity different?

Jacob: it's actually something that we had to sort of educate people on in
Sweden and in Europe. I think it's, it's, people are just not used to the venture
thing. They don't know how to, value equity the same way. Like you have to
really, this is how it works. This is what it means. Like these are the, if this
happens, then you get this much money, um,

Harry: But you don't get it [00:33:00] in cash. It's not like, yeah, exactly. Yeah.

Jacob: And then there's tax, and

Harry: I do it with our team and they're like, wait a minute, you're giving me
half a million dollars. And you're like, no, no, no. I don't, not literally, but like
in the future in a way. Yeah. Yeah.

Jacob: It's, so that's been a little bit difficult for us. Right. I think it's a, that's
part of just creating the, the, the ecosystem. You know, in, in 10 years, the next
startup that comes out of Stockholm hopefully won't have this problem.

Harry: everyone is encouraged to use as many tokens as possible. I'm on the
board of public companies and they're like, oh,

I'm,

I'm hearing about

Jacob: like

Harry: [00:33:30] maxing and token.

Jacob: Yeah, yeah. Yeah.

Harry: What do you advise a CEO in terms of intelligent usage of ai? And
should we just be pushing tokens as much as fucking possible,

Jacob: so a few different on that. I think one, a leaderboard, a lot of people say
this, get, get a leaderboard. bring up token usage at performance reviews. Uh,
and that leads to token maxing, which is people just burn tokens just to look
good. that's a really stupid way to do anything. do hack days, do demos, have
people [00:34:00] show everyone else how efficient they are and like how much
better they're doing. Reward them for being, effective and efficient and having
more output, not for necessarily using ai, but like AI will be the way there. that's
one of the points. I had another point For Enterprises, this is actually where I
think Cursor has, a reason to live. A reason to exist, which is if your options are
Codex and cloud code and a neutral third party, and you all pay, you know, you
pay consumption based cursor can help you optimise your [00:34:30] token
spend a lot. ' cause they can optimise your usage, right? They can route them to
the cheap open source model or help you set limits for whatever models you
want to use for what thing.

Harry: Well, can they now post acquisition by gro?

Well,

Jacob: we'll have to see if, if they

Harry: I respectfully disagree and that's why I actually think both cognition and
factory all do very well because they're model independent. But if you look.

Jacob: Because you think now that they're tied to X.

Harry: A hundred percent.

Jacob: I was a bit surprised and a bit sad to see the, the acquisition.

Harry: Why.

Jacob: Why? Because I thought [00:35:00] that they could, if they stayed
independent, they had a really cool, a really cool story. I, I, I mean, I see the
synergies.

Obviously they don't have enough compute. They can't train their own models.
They probably have to train their own models. just think it's a shame that the
industry is vertically integrated in that way.

Harry: You think IDs are dead?

Jacob: I think. the current of an idea will die. Yes. I don't know what the new,
the next idea is, but it's not reading lines of code. It's, it's graphical honestly.
Like maybe it's the systems, the, the, the, the architecture that you look at and
you review and you, you [00:35:30] plan it there and then like agents run often
make sure that whatever you're planning actually is, is what's being made. I
don't think it's lines of code.

Harry: What percent of developer salary would you be willing to spend on AI
tooling for them?

Jacob: I don't want to say infinite, but for me it's a question of opportunity cost.
we are in a competitive environment, you know? Um,

Harry: Are you? Yeah.

Jacob: are you, yeah.

Harry: Gosh. Are you

Jacob: no

Harry: I didn't know that.

Jacob: There's

Harry: It was fascinating.

Jacob: I know. there's so much, so many things that we can [00:36:00] do the
cost of not doing it is extremely high and it's almost outweighs any sort of token
cost.

Like any efficiency gain is worth so much to us that's for us, but for certain
companies that will look different. Right. the budget on, on tokens is mostly a
question of opportunity cost. Is it worth us spending a tonne of tokens to learn if
it maybe gives us 20% for us?

Yes. We have a really high opportunity cost.

Harry: What did you do that you wish you hadn't done?

Jacob: you know, not investing in developer experience fast enough, definitely
a [00:36:30] problem. underestimating our growth. Also a problem now I make
sure everything we build will scale to 100 x the usage. I used to say 10 x and
then that was not enough. So now everything needs to scale to a hundred

Harry: What changes when you're building for a hundred x versus 10 x? I'm
sorry. I'm very naive.

Jacob: No, that's not naive at all. it doesn't always have to change, but there are
certain limits that you often will put in place. Just be like, yeah, this probably is
good enough for the next three months. So like, yeah, okay, we can, if we have
these, if we bound the problem in this way, which is maybe 10 x, then we can
do X, Y, Z. [00:37:00] But maybe that doesn't hold if you're a hundred x. And
so sometimes you need to think about, I think particularly problems where
there's bursts to it. So a tabular review is one of our products where you can,
bulk extract from many documents and many, many cells. there's a very big
difference between 10,000 cells and a hundred thousand cells, just like on the
load of the system.

'cause it spikes immediately. so that's one of those systems where there's
actually a difference.

Harry: So what do you do in that case where the spike is so immensely
different? Yeah. What does that mean? You subsequently do differently?

Jacob: We have to think about the [00:37:30] experience. if 10 people do that
crazy thing at the same time, and we still have a bunch of other users that we
want to have a good experience. So we need to think about, fair queuing
basically, which is like, okay, if you're running a hundred thousand cells, you're
probably okay waiting a bit.

You can go grab a coffee and that's fine, but if you run 10 cells at the same time,
that those should be really fast.

Harry: If I ask a really unfair one, if I gave you access to a superior model for
six months ahead of anyone else or superior engineers for six months ahead of
anyone else, which would you rather have?[00:38:00]

Jacob: Engineers for sure. ' cause the models, they change all the time. They
get better all the time. But if you have really good engineers, you can build a
system that, exponentially improves and that's worth a lot more.
Harry: What do you know now that you wish you'd known when you started
day one?

Jacob: honestly wish I'd known quickly we were gonna scale. ' cause that was
the thing that I underestimated all the time. I don't think I was ready for journey.
I became ready really quickly 'cause I got slapped in the face every three
months.

Harry: You buy that people are destined for certain stages of [00:38:30]
companies. I'm getting very personal. If I was you now I,

Jacob: I,

Harry: I have in my mind, like am I the CTO that takes this to public
company? Yeah.

Jacob: It's a very fair question. No, I don't buy that. I think to me, it's a question
of how quickly can I solve problems? Am I the person that can solve the
problems that we have right now the fastest?

Or can someone else solve them faster than me? have a great, culture and, and
that no one has any ego. I've told this to, I currently have two engineering
directors. I've told both of them when I hired. If there comes a day [00:39:00]
when you, when I think you'll do better than I will, then we swap or I do
something else. I have very little and they also have very little tied into their
title or their role. We are here to build something huge, and that's the most
important thing. continuously evaluate myself on my job performance. if I don't
do well, I try to rectify that really, really quickly. And I haven't been able to not
rectify it yet, but maybe there comes today.

Harry: What's the secret to hiring the best engineers with no ego? And how
obvious are they?

Jacob: They're obvious if they have ego. even just when you're [00:39:30]
negotiate, salaries and titles, you can hear and tell.

Harry: I don't know about you. I always say great. People want more money.

Jacob: Yeah, they don't mind.

Harry: Yeah. They don't mind so much about the title.
Jacob: I think that's right. absolutely right. most of the people, that we hire,
don't even talk about their title. We talk about the the difficult problems that
they're gonna work on.

Harry: How important is it that you are together in Stockholm?

Jacob: It's been very important for running really fast. I mean, this is, we talked
about the handover

Harry: Yeah.

Jacob: If you have a PM and a designer and an engineer and they just sit
together, almost not even have the [00:40:00] handover. You can just be like,
run at this problem and, and, and do it together. The three of you, then it's done.
if you have them siloed and there's handover in between, you lose so much
efficiency.

Harry: Jump on a Zoom call. Lacking clarity. Yeah.

Jacob: yeah. This doc is not well written enough. You have to do another
meeting, and then you have to do three reviews of the document, and then
someone else has an opinion that, you know, sees it somewhere and writes a
comment somewhere, and then you have to about that.

Harry: How do you factor that into, well, how the best engineers like to be
remote.

Jacob: Well, we're very opinionated about who we are and who we [00:40:30]
aren't. if you're a great engineer and you want to be remote, then you probably
also want to work on very isolated problems, that can be fine. We'll, we'll, we
probably have those and we probably will have those, but. They're not for us
right now.

We'd rather find the people that wanna solve the same problems with other
people.

Harry: How many engineers will you have in two years or by the end of 2027?
You are 80 today.

Jacob: Yeah, I'm gonna say a number that's too low.
Harry: I'm, I'm gonna WhatsApp it to you. Yeah. On the 31st of December,
[00:41:00] 2027. Were you wrong? Yeah, yeah,

Jacob: answer will

Harry: yeah. Totally. Yes.

Jacob: I don't know, 300, 200

Harry: 200, 300 different. You gotta put your name on one.

Jacob: If I have to put my, I want to say the lower number, let's say two 70

Harry: Two 70. Okay, so we're gonna have 190 more. Yeah.

Jacob: Yeah.

Harry: Can you retain a only talent with 190 more? That's essentially adding
two and a half a week.

That possible.

Jacob: it's, if it's linear, I think so. I'd rather miss my number and have a players
than hit it with B [00:41:30] players. as soon as you have people that you don't
trust or that the team doesn't trust, A players won't stick around.

Harry: You are buying more companies than I'm doing podcasts these days.
And you are laughing 'cause it's true.

Jacob: It's, yeah,

Harry: it is not true. It is not.

Jacob: essentially an investor now.

Harry: Um, my question to you is, do you have to buy companies to get the
truly, truly a talent in a lot of cases today?

Jacob: I don't think so, but it's faster. cause if you find a really good [00:42:00]
person who a really good founder, they're able to attract really good talent. And
so you have a small group of five people that are just a talent. and then you get
five in one week, know, if you have to get to every week.

and that's much faster than going to all big companies or even the startups and
trying to convince them to come over. People also, like if, if you have a small
startup of five, eight people, they want to work with each other.

Harry: You just shed their code bases then, or is it like pure acquihires in a lot
of cases?

Jacob: it, it can be both. if they've worked on adjacent things or think it's in a
similar field or [00:42:30] even, but similar technology, we'll take all their
learnings and we might rebuild it into Lara. I think that's what happens in most
cases, but they become, embedded into the team.

It's, they're all laan working on their Lara code base, and then they might bring
some learnings.

Harry: Is integration hard.

Jacob: it's surprisingly easy if you hire people with low ego. if you get five
great engineers that don't care about their titles or where they sit in the org chart
that just wanna solve problems, it's surprisingly easy.

It's integrate.

Harry: When you've got engineering hires [00:43:00] wrong, what did you not
see that you wish you had seen?

Jacob: when this goes wrong, it's actually because of my, gonna be a little bit
introspective here. It's, it's probably because of, my own, I don't have, you
know, I've not run an engineering team this big before, and so I start downing,
I'm not confident enough in saying this person, who's more senior than me, has
seen more than me is wrong. it's happened once or twice when there's a very,
very senior person, we talk and they talk about all this sort of org building and
arc design and like how they think about all this stuff. and I [00:43:30] sense
that something's wrong and I kind of know that all the time, but I, in the end, I
end up convincing myself that, no, they probably know more than me. Or like,
they, they figured it out or whatever. two weeks in, four weeks in, six weeks in,
you start to figure out they didn't.

Harry: How fast do you know if you've made a mishi?
Jacob: A month, then, you know, you give them really strong feedback. I give
really strong feedback after two weeks.

Harry: What does really strong feedback mean? Jay?

Jacob: really strong means, uh, you're not gonna stay if you don't change this,

Harry: Has anyone ever recovered from a, you are not gonna stay if you don't
change this.

Jacob: So, but they need to get the [00:44:00] chance, and if they do, they stay.

Harry: What is the hardest role to hire for today?

Jacob: this is a great question to all of them. No, I think senior management is
extremely difficult to hire for in

Harry: Senior management, horizontal senior management.

engineering directors.

Jacob: maybe that's always been difficult, we only have really technical people
also being managers. And so anyone who's seen scale typically also is not no
longer technic.

Harry: Do we still have managers? And what I mean by that is like, you know,
one of my dear friends Jason, I came from s like anyone on LinkedIn who talks
about their team, fire them. [00:44:30] Fire them straight away. We don't want
managers who manage other managers, who manage other managers. If you
can't do full stack, get out, pick up your severance and go away, do we still want
like senior managers?

Jacob: well. You can build a company of super senior engineers that can do
everything and, and you probably don't need to manage them at all. especially if
there's like really strong, if they know what they're trying to achieve. The Codex
team, for example, like they all know what they're building, they can just like
run at it and they don't need anyone to tell them that they're doing well. But if
you have a more complex [00:45:00] product that can go in many directions and
you have to do constant prioritisation, and, You have, a suite of engineers and a
team of engineers. So, so the way that we have engineering teams is relatively
small teams. Let's say six people pm and an, and an engineering manager. The
engineering manager is super technical, spend most of their time coding and
they're not like a, people hold each other's hands and like sing songs.

Harry: But.

Jacob: it's still important that I have someone that's accountable to the team
health. Are people, doing good jobs? Are people having fun?

I can't walk around and judge everyone, you know, are they, are they doing
well? And so I think it's [00:45:30] important to have someone who's
accountable. and that's how we run it, right? They decide their own roadmap.
They're their own little startup. but someone is, one person is accountable.

Harry: Is Max on every new product feature?

Jacob: And on big ones, yes, on small ones, no.

Harry: Is that right?

Jacob: it's worked for us His time. Max is an amazing salesman, probably
know, and so I think Max spends his time on that and he spends his time on, on
product vision and the important product things So big launches, big things
here. He's involved early, and for the duration of the [00:46:00] project, but for
small things, that's like the reason you hire great people is that you can let them
do this.

Harry: The thing with Max, his specialist, you know, he so believes what he
says. Often when you you're being sold, you kind of know you're being sold to.
Yeah,

No, no. Like there is no way that he sees himself being wrong in his bones.
Absolutely.

Jacob: Yeah, absolutely.

Harry: And also like, you know, I think there, there was this brilliant, we've,
we naturally hate them 'cause they're shit, but sifted,

Jacob: Ah,

Harry: did that piece, um,
Jacob: with the,

Harry: taste of thought.

Jacob: piece. [00:46:30]

Harry: yeah.

yeah. Did everyone in

Jacob: the

Harry: Lara just go, oh my God. Yeah. That was, that's hilarious. Yeah. Yeah.

Jacob: yeah. There's, uh, there's screensavers now that say blom on like the, it's
like become this internal meme.

Harry: Did you guys like the Jude Law?

Jacob: I loved it. You know, I've sat on that secret for like nine months.

Harry: Did you think it was done? Well?

Jacob: I think so. Yeah.

Harry: Yeah.

Jacob: What you, you asked, I guess if it was not done well.

Harry: Think the Jude law idea was great. Oh,

Did it do well for you guys? Do you think off?

Jacob: Amazingly

Harry: Yeah. Oh no. Crazy. Well, yeah.

Jacob: it's wild.

Harry: people [00:47:00] see.
Jacob: everywhere, which is great. People talk about it a lot, which is

Harry: Like the.

Jacob: of the campaign, right, is like we, we need to get everyone talking about
us.

Harry: dude. We're gonna do a quick fire round. So I say a short statement, you
give me your immediate thoughts. Does that sound okay? Yeah, that's good.

Jacob: do it.

Harry: So what have you changed your mind on most in the last 12 months?
You can have pauses

Jacob: Hiring. Yeah. we need to hire more As long as adding a, someone is net
positive, we should add someone.

Harry: What's the most underrated AI company today, do you think?

Jacob: Lara,

Harry: Dude, [00:47:30] I'm an amba. I'm an ambassador, and even on

Jacob: my

Harry: no shit, dude, I, you gonna gimme another one? I have to say.

Jacob: say it.

Harry: One for me would be whisper flow, like the pain of removing whisper
flow for me is like immense.

Jacob: flow is great. I think we're gonna get more local models though.
Whisper flow is not local, so you're probably gonna get a similar whisper flow.
Well, maybe they should just go local, but the tool itself is great.

Harry: Finish this sentence. The biggest threat to Lara is not Harvey,

Jacob: [00:48:00] the thing that's gonna kill us is if we don't keep reinventing
ourselves. This sounds really, boring, but I think we talk a lot about staying in
our swim lane, focusing on our product and our users and the entire
environment is moving so much. If you had had me on this podcast a year ago,
you know, it would've been very different. So I think the, the main thing that's
gonna kill us if we don't, if we lose the ability to constantly react and readjust
and reinvent ourselves.

Harry: You just work with Jude Law in terms of brand campaigns, what
[00:48:30] sports team would you most like to see A leg across? Could be F1,
could be football, could be NBA F1 would be.

Jacob: be great. I'm a big F, but if, if F1 would be awesome

Harry: Strategically, would that be awesome? You do golf very strategically.
Do golf.

Jacob: the Yankees we, we sponsor, in New York, which is also great.

Harry: Sponsor the Yankees.

Jacob: Yeah. You didn't know this Aaron Judge.

Harry: Fucking hell. How much does that cost?

Jacob: That I can't tell you,

Harry: But I want,

Jacob: do you know the team that I would want us to sponsor my local FC
Copenhagen Football Club? That would [00:49:00] be a childhood dream.
They're doing really bad right now though, so

Harry: Really cheap.

Jacob: cheap

Harry: it? It's called exposure.

Jacob: Yeah,

Harry: You would get ill
Jacob: yeah, exactly.

Harry: and then the Champions League knew

Jacob: Yeah. No,

Harry: Euro League.

Jacob: even top of the Danish League.

Harry: Yeah, yeah. I'm like, you know what, you should be CTO.

Jacob: cheap.

Harry: be c Emma. It's okay. Um, uh. What is one thing you believe about the
future of law that most people would say is crazy?

Jacob: if I had to get crazy, I think there's lots of um. analogies to coding. in,
[00:49:30] in law it's very text-based. sort of the, the a agent AI features are, are
similar. If I believe that we're gonna look less at source code and more of like
one layer above. I have to say the same thing about law.

Like eventually lawyers will not be nitty gritty about the language of the
contracts. They will work a level above, which is maybe like our negotiation
stance or like what, what risks are we, okay, which ones are we not Okay
taking? and not sit and type into word.

Harry: what's the biggest advice to a founder competing in a [00:50:00]
business slash industry where there is an 800 pound gorilla?

Jacob: Honestly just work harder than the 800 pound gorilla. people
underestimate this. Like the 800 pound gorilla. No one in the 800 pound gorilla
is extremely excited to be there. I think, I think that it's just like if you're
competing against Google, like the PM in Google that you're competing against,
does not give a shit if it goes well or not. maybe, maybe she tries really hard,
but if you're a small lean team, you work really hard. You can do really
remarkable things. You

Harry: Ready for a bet?

Yes. What are we gonna end the year at, revenue [00:50:30] wise?
Jacob: It is gonna be, it's gonna be above two 50.

Harry: Think it was 2 72.

Jacob: 2

Harry: 72. Yeah.

Jacob: Right. I think it's gonna be above that too. Cool. I don't, yeah, but I don't
wanna,

Harry: I don't wanna get in trouble. I'm just a CTO. I don't mean it.

Jacob: know numbers.

Harry: I didn't mean it. Max and Patrick. I dunno. Uh, dude, David's gotta call
me really mad soon.

Jacob: Dude. This is.

Harry: this has been such a pleasure. I've loved having you and you've been
fantastic.

Jacob: you. Thanks.

Harry: you. Thank you for, this is my first podcast ever by.

Jacob: the way.

Harry (Adverts): But before we [00:51:00] leave you today, you know what's
wild? We have AI superpowers. Now, yet so many product teams are still flying
blind, buried in spreadsheets, chasing feedback across 10 different tools. Jira
product discovery fixes that I've spoken with. Hundreds of product leaders and
the best teams all do one thing differently.

They build a system to capture ideas, validate them with real data, and focus
their roadmap on the right things. Well. That's why product teams at Canva,
Deliveroo Toast and Decathlon use Jira product discovery. It pulls [00:51:30]
ideas and feedback into one place with built-in tools to prioritise what'll have
the biggest impact.
That's when a roadmap stops being an endless list of ideas and becomes a plan.
People actually believe in join more than 25,000 teams already using Jira
product discovery. Head to atlassian.com/harry and start building the right thing
today. While Jira product discovery turns feedback into priorities, fin turns
questions into instant answers.

As AI agents become more common in [00:52:00] customer experience, teams
often end up juggling multiple silo tools for every job. Well, Finn was built to
change that. It's a single unified agent that works across your entire customer
experience from service to sales to success and beyond. Finn is the agent
making perfect customer experiences possible for thousands of customers, is
powered by customer models, trained on years of real customer interactions, so
it understands the nuance and complexity of customer service better than any
other agent.

That means faster [00:52:30] resolutions, more consistent support, and just
better experiences for every customer. It's also designed to be fully self
manageable so you can easily improve and adapt it as your business evolves. No
third parties required leading companies like Gamma Asana, DoorDash and
crypto.com already use and love fin to deliver better customer experiences.

So see what FIN can do for your team at fin AI slash two zero vc. While fin
helps answer the customer, framer helps impress the next one. You know that
[00:53:00] moment when marketing wants a landing page design, mocks it up,
and engineering says, yeah, we'll get to it. Thousands of businesses from early
stage startups to Fortune five hundreds a choosing to build their websites in
framer where changes take minutes instead of days to solve this very problem.

Framer is an enterprise grade no-code website builder that works like your
team's favourite design tool, and it's used by companies like Perplexity, Miro,
Mixpanel to move faster. Designers and marketers can fully own the site with
real time [00:53:30] collaboration. A robust CMS built for SEO and advanced
analytics that include integrated AB testing.

So you are not just shipping pages, but you are maximising what works and
when you are ready to ship changes, go live in seconds with one click. Publish
without relying on Engineering. Plus framer is built for scale with premium
hosting, enterprise grade security, and 99.99% uptime SLAs. Whether you want
to launch a new site, test a few landing pages, or migrate your [00:54:00]
full.com framer has programmes for startups, scale-ups, and large enterprises to
make going from idea to live site fast.
Learn how you can get more out of your.com from a framer specialist or get
started building for free today@framer.com slash 20 VC for 30% off. 30% off
of Framer Pro Annual Plan. That's framer.com/two zero VC for 30% off.
framer.com/two zero VC rules and restrictions may [00:54:30] apply.
