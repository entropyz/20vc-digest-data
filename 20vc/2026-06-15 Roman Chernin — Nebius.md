---
type: 20vc-episode
guest: "Roman Chernin"
company: "Nebius"
role: "Co-Founder & Growth"
episode_type: interview
date: 2026-06-15
youtube: "https://www.youtube.com/watch?v=aXAH3bdJ2cg"
transcript: "https://20vc.substack.com/api/v1/file/24d991b6-7778-4f22-9ca9-36471cb7c1a2.pdf"
newsletter: "https://20vc.substack.com/p/20vc-newsletter-15th-june-2026"
tags:
  - 20vc
  - ai
  - engineering
  - founder-advice
  - fundraising
  - infrastructure
  - leadership
  - marketplace
  - pricing
  - sales
---

# Roman Chernin — Nebius

> Co-Founder & Growth @ Nebius | 20VC Interview | 2026-06-15

## Key Takeaways

### 1. How Reducing the Cost of Intelligence Increases Consumption
Reducing the unit cost of intelligence triggers Jevons Paradox: total compute consumption rises as previously uneconomic tasks become viable. At scale, builders move toward tunable open-source architectures and specialized post-training, while frontier labs expand into larger, harder reasoning markets.

### 2. If Nebius Doubled Pricing, How Would That Impact Demand?
Nebius’s pricing power is capped by customer economics. If inference costs rise too high, customer margins break and demand stalls. The real edge is not nominal GPU pricing, but Total Cost of Ownership: caching, runtime optimization, and distillation can shift token economics by an order of magnitude.

### 3. If Nebius Had 10x the Capacity, Could They Sell It?
The real question is not whether raw demand exists, but whether Nebius can diversify it. Bare metal concentrates revenue around a few global giants. Moving up the stack into managed infrastructure and specialized inference expands the market to thousands of application developers.

### 4. What Is the Single Biggest Threat to Nebius?
The biggest threat is extreme consolidation into three to five closed tech empires. If a few conglomerates control the frontier model landscape, independent clouds risk becoming low-margin physical-layer vendors. Survival depends on a broad, democratized ecosystem of independent builders.

### 5. Who Actually Holds Power Against Nvidia?
Power against Nvidia comes from engineering credibility, not political posturing. Nvidia is deeply engineering-driven, so influence comes from proving technical capability across the stack. Differentiation requires a world-class team that reliably executes and earns operational respect.

### 6. Surviving the Hyper-CapEx War
Competing with hyperscaler CapEx requires respecting operational timelines. Capital cannot compress a six-month infrastructure bottleneck, but over 18 to 24 months it matters. It lets providers parallelize execution, secure power, lock data centers, and prepare capacity ahead of GPU deployment.

### 7. The Shark Rule: Move or Die
Cloud infrastructure is a post-sales business: every funding round or contract is only a credit and an opportunity to deliver. Survival requires relentless forward motion, disciplined execution, and focus on daily operations rather than emotional market spikes or consolidation noise.

---

## Links
- [Watch on YouTube](https://www.youtube.com/watch?v=aXAH3bdJ2cg)
- [Full Transcript (PDF)](https://20vc.substack.com/api/v1/file/24d991b6-7778-4f22-9ca9-36471cb7c1a2.pdf)
- [Newsletter](https://20vc.substack.com/p/20vc-newsletter-15th-june-2026)

---

## Full Transcript

[00:00:00] who has power against Nvidia

We are in the capital intensive game and we are competing with the most
capitalised companies in the world.

our CapEx programme this year is 20, $25 billion. our competitors hyperscalers
have eight times bigger. in the next six months, the capital cannot help. six
months is too short time. you have what you have, you need to deliver

consolidation I think that the main three for nebiss as a business is the world
will be too much consolidated.

it is like a shark. You are alive when you move, right? So we have to move.

The AI infrastructure race is on CapEx spend has never been greater at the
centre of this neas today I'm joined by the co-founder of neas, a company that
has scaled to a $66 billion market cap, going head to head with some of the
largest hyperscalers in the world. Leo Chen Braner, one of the most famous
investors on the planet right now, [00:01:00] has just made them one of his
largest positions.

Today, we uncover the AI infrastructure bubble and so much more with the co-
founder of one of the hottest companies on the planet neas, and I'm thrilled to
welcome Ronan Churnin.

Before we dive into the show today, you have the idea, but often with AI tools,
you hit a wall. Well, base 44 is where that friction disappears. Turning how you
talk into how you build full stack web and mobile apps, sites, autonomous super
agents, all built in minutes, not weekend spent on damn configuration base 44
ships it all out of the box, the backend, the database, the authentication, and the
hosting.

It handles the heavy lifting so you can just stay in the flow. It doesn't just
replace the busy work it multiplies you. It makes you so much more capable and
effective version of yourself. In this market, being fast is the baseline, but to
win you gotta be first and base. 44 is that edge. It's the move that lets you skip
the troubleshooting and get straight to the breakthrough.

Launch your [00:02:00] next big thing@basefortyfour.com. That's base four
four.com. After Base 44 helps you launch Corgi helps you cover what comes
next. My word, what an arresting first line. Get your ass covered with Corgi
Insurance and I'll tell you why. If you are running a business right now, you
already know this pain all too well.

Getting insurance, it's really slow, it's confusing. And my word, it's full of
paperwork. Well, that's exactly why Corgi is here to change the game. Corgi is
the first and only insurance carrier designed specifically for tech companies
allowing you to get covered in minutes instead of days. Corgi provides essential
coverages for all growth stages such as D and o, e, and O, liability, cyber,
commercial, general liability and more.

Get your ass covered. I love the way we say ass with Corgi Insurance alongside
thousands of other startups@corgi.com slash two zero VC today. That's
corgi.com/two zero vc. You won't regret it. While Corgi handles the [00:03:00]
coverage, cheering handles the talent, frontier Labs keep facing the same
limitation.

Models perform well on benchmarks, but they fall short. Once they enter real
coding tasks, real tools and real workflows. That disconnect between synthetic
evaluation and actual system behaviour is now a core block off for Argentic
models. That's why Nvidia and Anthropic, Salesforce, Gemini, and other
leading lab partners partner with Turing.

Turing is the research accelerator focused on post-training reliability. They
build realistic RL environments. Next generation data quality systems built
from real world operational traces and coding data sets that stress models under
conditions where failures matter state changes, workflow branching, brittle tool
calls, and the coding errors that break RL agents but never appear in benchmark
reports.

In reality, a model may demonstrate correct reasoning in your evaluation setup,
yet still select the wrong parameter or mishandle a code update in a realistic
interface. Turing makes that failure visible and gives teams the [00:04:00]
signal they need to fix it. For labs advancing ag agentic systems, Turing
provides the structure required to understand why these failures occur.

To find out how, visit turing.com/two zero vc. That's TURI g.com/two zero vc.
You have now arrived at your destination.

Roman, I am so excited for this dude. I think neas is one of the most
unbelievable, incredible stories in terms of what we've seen over the past years,
but also like, holy shit, what an exciting few years we have ahead. So thank you
so much for agreeing to do the show.
Yeah. Thank you for inviting and, glad to be here.

Now, I would love to start with a question that I think is at the top of a lot of
people's minds, which is like, where are we at in the insertion point on AI
infrastructure? A lot of people are seeing the capital going and going, oh, it's a
bubble, and a lot of people are going, it's just a start. How do you think about
the, we're at an AI infrastructure bubble moment right

now.

No, I, I, I don't [00:05:00] believe it's a bubble. define the bubbles. do I believe
that we'll need tens or hundreds times more, to build? I fairly believe, I probably
biassed. I would probably not be in the business that we are doing if I wouldn't
believe. so I think that we are just at the beginning of this amazing moment
when Janssen calls it like useful ai.

And we just at the beginning of this kind of real adoption and honestly we have
maybe one use case that works out of so many of use cases. the one use case
that works like coding, everybody's talking about coding, started working like
maybe a few months ago. Just like, let's put it in the perspective.

We just few months from the moment when we've got maybe first use case
that's works in the scale and we start seeing, it's applying here and there I think
we'll see obviously many, many, many more use cases we will see much more
adoption. I think that what [00:06:00] we see yet is if you take every single
company in the world, maybe outside of the fastest moving startups before the
show is we were speaking with like who is moving fast enough or not fast
enough, right? So maybe there are some exceptions, but I think if you take any
company in the world today, and you will look at the AI adoption there, you
will actually see that they start using AI in a first percent of the volume, in the
first percents of the use cases. So if you take any large company, even pretty
advanced technologically, you will see that they just starting. And I'm taking
from that, that we only, beginning. even, even if you don't believe in what Musk
says about everything in the future space and so on, just practically, from,
enterprise adoption,

it's just the first steps.

so we are, we are completely aligned, but it's a very boring discussion if I just
go, I agree with you on, on everything. my, my question to you on, on the back
of, hey, we've seen coding now work for the last whatever, six to 12 months.
Yes. [00:07:00] But there is a question that we will move to open source models
locally hosted because the cost will be too significant for some of these
enterprises to burden.

And we're gonna see that shift happen soon if we do. That is both damaging to
the providers, open AI and Anthropics of the world, and to a neas, why is that
perspective wrong?

Yeah. So first of all, I think that, it's not in the future. It's already in the present.
again, what we see in a lot of examples at the moment when our customer or the
product builder gets to the scale, they start, looking, to the ways to improve the
economics or accelerate the growth and so on. And this is the way when they a
lot of them start to look to alternative models. So the best way to build today is
obviously to build on the frontier models from great providers like company ai,
andro, Google, because they actually provided that through, they provide you
the best, best capabilities in the world. But [00:08:00] then when you figure it
out, the use case, when you start seeing adoption, when you see the customer
data loop, you maybe can find the cheaper, or even not cheaper, but more
quality, high quality way to serve the same use case you don't need. Maybe you
don't need the best in the world universal model, but you can create a
specialised model that in your particular case will work even better. And that's
the way where you may consider to shift from, frontal closed models to open
source, the most important kind of cause of those models is not just the open
source, but they're tuneable. They're trainable. So you can take them and you
can do something.

You, you can post train them, and you can create the specialised model that in
your particular case may work better. So that's, we see over the world or over
the use cases. But why doesn't it hurt, tropic and open ai? Because in reality.
they move to the next frontier and to the [00:09:00] previous, point that we
discussed, there are so many unsolved tasks or the tasks that not necessarily
have the limited budget, to be solved. And every time we see, and we saw it like
with deep seek one year ago, and like, we continue see seeing it now, every time
we find the way to solve some task, more efficient, we just start solving more
complex task in the same time. this is like continuous journey, I believe. So you,
you always push the frontier.

You always have the more complex tasks to figure out how to solve. When you
figure it out, how to solve them, you can go down and reduce the price or
improve like the quality. But we have so many unsolved tasks that tropics and
opening eyes and all the other frontier models still have such a, not addressed
yet, tam not addressed yet market that they continue kind of exponentially grow.
 do you buy that these companies are priced to, to perfection in a lot of cases at
a trillion dollars. [00:10:00] If the value that they create is eroded and they're
constantly playing a game of leapfrogging from value to value to value, while
open source continuously eats behind them, gotta find a lot of problems
continuously, dude, that's a, that's a hard life to live.

actually most of the people are concerned on another side. Like, will we have a
strong enough open source and strong enough, specialised models, environment
to to build this floor?

I think that we yet, at such a early point of adoption, we have so many unsolved
problems yet that, it's just a matter of the total pie. I think there is, enough
space, to solve so many tasks in the future that it's enough, buy for, both frontier
capabilities, and very tuned, models for specific use cases and all the world of
these open source or specialised models that we can build on top of them, to
gain these economics advantages and, uh, performance advantages when we
know what we [00:11:00] need.

you said that like every time we, we have the cheaper model, is it hard, the
business? And my favourite anecdotal story about that is I think 15 months ago.
So the, it was, this deep seek moment, if you remember.

 I remember that Bel Stock went down 40% in one week or so, in February, I
think it was February or March, 2025. And anecdotal story, the same exact
week. We probably had the best week in sales. people on the market were
concerned that market is going down and like infrastructure companies like NA
is not needed because, okay, if it's AI is such, so much cheaper, maybe it's
bubble. But at the same time, we never had the best commercial week we were
pretty early in the, in our story, but that was the best commercial week in the
history of the company because so many people figure it out that they can run
inference in their production workloads, with deep and economics will work.
And then like at the, at the same time like K Store started growing, I think they
were [00:12:00] the first who really benefited from, tuning those models for
coding and so on. every time we got intelligence cheaper, the same unit of
intelligence cheaper, we are not reducing the consumption, but we increasing
the consumption because we can just solve more complex tasks with the same
budget, or we can finally, economically, reliably solve the tasks that we already
kind of knew that solvable, but economics didn't work and we could not scale.
So I think it's quite, fascinating. What's this economics improvements to
observe.
speaking of kind of Jevons paradox and, you know, producing more in that,
yielding more demand, where are you not moving fast today? Where you would
like to be moving faster?

everywhere. So when we think about how we build the company, we talk about
it in the four dimensions. One dimension is capacity, uh, how much megawatts,
gigawatts, and the GPUs we deploy. We are infrastructure company.

We need to be large. If you're not large enough, nobody needs us to [00:13:00]
exist. this is the, the, the physical world expansion. the team is doing amazing
job, but it's never enough and you wanna move as fast as possible. And, there
are a lot of complications of the real world that prevent you to move fast
enough.

Sometimes, to launch new data centre, you need to go through the entire, like
supply chain and regulatory and, fires and waters, everything that happens in the
real world, So this is one dimension. another dimension is the product. you want
to move fast enough to address new types of the workloads, new types of the
customers that come into the market.

 think about it. We started as a industry, in this AI journey, from the people
who, first of all, built models, right? So that was the companies like OpenAI,
hyperscalers, large labs and so on. And what they need from you as an
infrastructure provider is barely compute, like just raw infrastructure. And we
see a lot of this large bare metal deals on the market, and we also [00:14:00] do
them. but this is only the first layer of what we build, scaled physical
infrastructure that customers like meta Microsoft in our case, can consume on a
large volumes. This is the first layer. The second layer is what we call multi
talent cloud, still addressing, research heavy teams, but now we have hundreds,
or thousands teams that they don't want to deal with the physical infrastructure.
They want to deal with the managed infrastructure, classical infrastructure as a
service in the cloud terms. You have storage, compute, networking, virtualized
in a good environment with API observability security, everything that normal
teams expect cloud to have. You log in, you get your cluster provision, and you
can start training or runs inference if you need, and manage your application or
manage your workflow yourself, but have infrastructure figure it out for you,

So still, if the first layer speaks in megawatts [00:15:00] literally, like if you
read announcements, someone signed a large deal with someone like Meta or
Microsoft or OpenAI, people speak megawatts there. so it's like you deliver the
megawatts of compute. Then when you speak about this managed cloud, people
speak GPU hours because this is the key unit.
You sell the e efficient hours you can spend on compute with storage, with
complementary services, but you still buy managed by com, but compute. Then
the next layer that we working is managed inference. When people don't wanna
go in terms of GPU hours, they don't want to figure out. B two hundreds against
H two hundreds against B three hundreds.

What is better for particular workload? They don't want to manage the, VLLM
or HGN, deploy themselves, do all the optimizations. And here, our product
called NA Stocking Factory, this is a managed entrance platform. And again,
this is the new type of the customers, mostly [00:16:00] people who've we call
them vertical AI companies or enterprises. So people who actually build
products, they don't do models, they build products on top of the, and this is to
your point of specialised open source models when they need to shift from
atropic, for example, or diversify, the models they use for that. So, again, this is
the new primitive that we provide or the new kind of, new entity that customers
need.

Now we speak in tokens. It's not you pay for gpr, you consume tokens and you
can build your applications, not thinking in terms of the clusters underneath.
And this is where we sit now, but it's also, I think not the final stage of, where
we going, because now people build agent, agent applications, agent workflows.
And when you build, end-to-end and agent, you may not even think in terms of
the particular model and you'll may not think in terms of particular number of
tokens that you want to generate. you want the end-to-end task to be, efficiently
executed and [00:17:00] provide their expected outcome.

And then the magic that platform can make is actually think for you, which
model better to use in this particular call? do you need to go to the smart model?
Or, in the same inference budget. You can request two models, lighter models
and get, less smart tokens and then have the judge model that chooses the best
result or what size of context you should have and so on. So this is the next
layer when developer, would maybe not even think in terms of particular, types
of the tokens, but things in terms of end-to-end execution of their task.

So layer four is a direct competitor to open router

 what we would love to bring on that level is this the same, like what we do on
the layers below is the optimization engine. you can build your agent in so
many kind of open source or appropriate tools, but then when you need to scale
it, you start [00:18:00] thinking about, the economics, you start thinking about
reliability, reliable execution, like repeatable execution. And this is where it's
not just model choice problem. It's not just outcome problem, but it's a system
problem. You need to make it reliable, you need to make it repeatable and you
need to make it economically viable. And that's probably where NES could
create the value. The same way, like we don't tell people how to build their
applications. We just say, okay, if you need this model to work for you, like
with this economics, we will help you to optimise the same here. If you need
this agent end to end run with this budget, with this quality, maybe we can help
you, to optimise it. And again, this is just to make it sure it's a kind of a little bit
speculative thinking about what's next.

It's not like what we already have, but this is where we see our customers
evolving and where we think that we could create the next layer of the product
offering.

 I love this and I, I have all of these notes. I just want to actually go [00:19:00]
through the four pillars that you said that you said number one capacity.

Yeah.

if you had 10 x the capacity today, what would be different? could you sell it
overnight?

That's a good question. Not overnight, but we would definitely, we, we
definitely have demand for that. and I think the key question for us, it's not, do
we have demand or not, but how we actually build the portfolio of demand.
Because you have so many customers on this market that you can balance
between, and again, to the point of four layers of the product.

You can sell bare metal, you can sell managed customers, managed
infrastructure, you can sell inference, and maybe in the future you can sell, new
layers of product. And I think what we try to do is to build quite diversified
portfolio of, customers. we believe that the highest stack we move, the more
value potentially we can create for the customers and actually the highest tech,
we move the bigger population of the customers we can serve.

Because again, like on bare metal level, [00:20:00] you have maybe dozen of
the customers in the world that you can work with on, managed infrastructure.
There are hundreds on inference, there are thousands. On a gentech, there will
be tens of thousands of new developers that build it, right.

On the kind of customer portfolio, I love that for the capacity, You want to be
big enough that you are meaningful, but not too large, that the business relies on
them with that difficult awareness. Where do you settle on what? Revenue
concentration With a meta or a Microsoft you're happy with.

It's a great question and I, I would say it's a, it's a main question of, our
business. I mean, not NA seven, but the product category. And we always told it
publicly and, to our investors and to our customers that we believe that long-
term strategy of NAS is to serve as much diversified portfolio as possible.

So we, we do the best to have many customers that we work with. We build the
platform. If you, in reality, again, to [00:21:00] serve dozen of the customers of
the world on like, of the level of Met and Microsoft, which super advanced, and
they have their entire software stack, they literally need only physical
infrastructure.

they bring everything they have deploy on your infrastructure and run, right?
you have a tiny, tiny, additional value that you can provide them above the, the
physical infrastructure by the way, to, to satisfy them with what they need on
physical infrastructure is quite a challenge because you can imagine they're
quite demanding and, and they need the, the more scaled infrastructure in the
world that exists.

So, sometimes people say it's commodity, but it's not really commodity on that
scale. Like nothing commodity when it comes to the, to the real scale. But
again, to your point, this is quite a small population of the customers that you
can work with and you not necessarily need all the full stack software to work
with them. So we intentionally building and from day zero, of BULs, we were
building this software stack because we thought [00:22:00] that it's a much more
beneficial for us. And if I want to be pathetic for the world, to have someone
who can support customers, not only on this physical infrastructure layer, but
beyond,

 for the long term protection of the business. Do you not have to build the full
stack? otherwise you become the capacity provider to these mega players,
which will make a shit

tonne of money, but you are incredibly concentrated

and very vertically focused.

Yeah, I I, I think so. And again, we don't know where the world will end up. and
in the world of Infiniti demand, you may, sustain even long term a midterm,
selling this whole burn metal kind of, contracts. but the more competition, let's
say you have from the customer, from demand side, you can be picky, even
with the customers you, you work with and work with the customers that, that
value, the platform that we built more. And there are different customers in the
world, someone more, [00:23:00] obsessed about the price, someone more
obsessed about the quality. Someone really want to have much more advanced
platform because they want to concentrate, focus on their platform, or product,
and don't spend time on it. Yeah.

Before we move to number two, being product, just staying on capacity given
the insufficient supply of capacity today. If you doubled pricing, would you see
any change to demand?

it's a, it's a difficult question. we actually raised prices like

just couple months, uh, Yeah.

just couple months ago. and we still, still have fair, pipeline pressure, let's say,
uh, on supply. And again, we don't really know where is the balance. and I will
tell you why, it's not only us being greedy and want to get like, as much money
and like then people in the shortage will still have to pay for some extent. It
works like people needs compute to build. But then there is a point, and
especially it's less in, in, training, because in [00:24:00] training it's like one off
cost.

But if you believe that we are moving to inference, and inference is, the cost of
serving the customer, there is a a level where economics doesn't work. And the
economics of the products of our customers, if they work, they can grow and
then we can grow with them. it's not like just supply demand situation and then
absolutely elastic prices. They're elastic for some extent. but we also want to be
meaningful and we wanna be thoughtful, kind of what our customers need. And
by the way, it's not only GPU our cost, it is all the optimizations. You do all the
real, we call it TCO, total cost of ownership that you inv. Like and this is
partially why we build this software platform, and I'm sorry, come back to
product again

and again, you wanna speak about capacity, but people too much obsessed
about capacity, like capacity is potent too much obsessed about the nominal
price of capacity. You can price GPU $3, $4, [00:25:00] and $5. depending on
the use case, and depending on on the quality of the platform, it can create
completely different outcomes for the customer in the real cost. How long it
works Like what is the e effective uninterrupted time that you can run there? If
you talk about inference, how much tokens you can extract, we see all these
optimizations that happening that changes the price of the tokens in order of
magnitude. So people so much speak about the cost of particular GPU, but if
you do the right thing with the model, you can change the price like, in the
times. And all should work together, as a system, not just as a, again, if you
speak about raw infrastructure, then you can manage only the price. But if you,
if you build a platform and if you provide the higher level of the service to the
customer, then you can extract much more economics, not only from the
infrastructure cost structure, right.

 if, if we move to that second layer, then if we move away slightly from
[00:26:00] capacity to GPU hours to product itself, multi-tenant, what is the
main question that you ask yourself within that segment? If in the first capacity
it's how much revenue concentration we have, what is the big question in that
layer of value?

 what customer needs. know, you speak with a lot of product founders, and this
is the same, what customer needs at the end of the day, how customers evolve in
their needs. Where is the demand moving? So it's like we see all this transition
from training to inference.

We see transition from, just using the models to building agents. and we see the
transition from mostly AI labs, consuming AI compute to enterprises coming in
the game. And all the time if we want to be relevant, we need to follow the
changes. And this is the main question, which we ask us in the, in the product,
what customer needs and what is NA's? What is our value that we need to
create? Because again, we are a small company. We cannot build everything.
and we need to be very [00:27:00] precise on what we can do better than others
and where the value that we should focus on, given how customers evolving.

What changes are you seeing in customer needs that you are not seeing
discussed much in public?

 everybody's talking about this moving from training to inference. I think it just
very, a hundred thousand feet like vu because this move means actually people,
build specific products. And in those products they have their economics, they
have their trajectory of growth, and it's not just like whatever the same GPU is
just used, for other purposes. I think it, it brings the new requirements. you need
to build your inference platform. You need to help your customers not only run
inference, but where the model that the inference come from. Everybody is
taking open source models and fine tune or l them. So how do we help them?
And then when they run them, they generate a lot of data.
How do [00:28:00] we help our customers, like when they already run, their
application, their inference to collect the data, to create it, and then use it to
improve, the model or the application that they run. So people like this flywheel
analogy, like, you run inference, you generate data, you can observe this data,
then you can improve the model, that you run and kind of continue, improve the
quality, of the end product.

So I think, there are a lot of pieces both on system level and both on, AI magic
level if you want. and I think the one, the most fascinating mo moment for me is
that, I think what we see is that barrier to build is going down. So we see more
and more customers like builders coming to the market that not necessarily AI
researchers are not necessarily inference engineers. and the value that
companies like NAOs can create is actually to lower the barrier, to build AI
enabled products, and then AI [00:29:00] enabled applications that really work
and incorporate like height from the developer. All the complexity of
infrastructure, some complexity of ai, like how you tune the model or how you
optimise the inference.

It's a little like research heavy area as well. And just let people focus on their
customers and use case by the way, the same way like they do with, the closed
tech systems, like on tropics open ai.

You mentioned the word differentiation and one thing that I was discussing with
my partner before that we have is a thing we have to discuss, and it's within
these layers, but you've spoken extensively about product build out and the
importance of building the product underneath capacity. When people look at
you versus other neo clouds, you know, we, we look at you versus a core
weave.

You both run GPUs, you both have Nvidia relationships, you both have meta.
As a customer, what's the difference?

I don't like compare with others. but the principles we build are. Full stack, we
call it full stack integration. And [00:30:00] you, you can think about it like full
stack down and full stack up, full stack down is, we are really deep in physical
world. We build data centres, we build racks and servers. We build the platform
and when you control this things downstream, you can move faster and you can
squeeze more, cost and provide more economically viable solutions for the
customers.

And then your vertical integration upstream is actually what we spoke about,
like product and how can you follow the customer's needs and customer
segments and not be limited by the small population of the people that just need
infrastructure, but really serve kind of enterprises and product companies, with
like meet them where they need us. And this is like, I think what we different
and then how it, showing up, I would say is again, less concentration in the
business. More diversified customer portfolio. we believe long term, [00:31:00]
better positioning for going to enterprises where we believe eventually a lot of
demand will come from.

Again, now most of our segment is working, it's AI natives, working with AI
natives, but we have a huge market of, enterprises, existing companies. And
someone needs to serve them. they will not buy raw compute. They will need
platforms. They will need tools. They will need, us to respect their legacy and
being able to work with their more complex environment.

They're not nimble. They have data to integrate. They have systems to integrate.
And that's, the big game. And I think that for us it's kind of the main, direction
to move.

 you mentioned the third layer of the four pillared stack being managed
inference. For people that don't understand, how do you think about this layer
and how would you explain it to them?

Yeah, very simple. you built your product on whatever call your,Where are your
wipe code

I, I, I'm actually an open AI and a [00:32:00] code expert. Yeah.

OpenAI. Okay, good enough. you built your great product with OpenAI. you
cracked the use case, and you started growing and you have amazing traction.
The only problem may be you don't have enough margin, or you want to start
applying more aggressively the data and tune the, the behaviour of the model.

And you cannot do it in the closed ecosystem. So you, you, you go to internet
and you read, there are a lot of great open source models that on the
benchmarks, uh, closed open ai, and you think, oh, great. It'll be 10 times
cheaper. Inference is cheaper. I can tune those models. I can apply my data and
my product will be better.

My growth will accelerate. So you go, you, you take the weights from hugging
face, you take, some, engine to run it like VLLM, sang something, and then it
doesn't work. because, you need to, to really extract the value you expect, you
need to do like [00:33:00] optimizations, you need to deploy it in the proper
way. You need not just one GPU tokens, extraction one host, setting, but you,
you have the large product. You run on hundreds of thousands GPUs already.
You need all the orchestration, you need the caching. you need the
observability, like your customers ask you like, how does it work? And so on so
forth.

And by the way, you had all of that on OpenAI because this is like the
production service for you. you don't think about infrastructure when you work
with OpenAI. Just subscribe for the plan you need and you pay for whatever,
end result. And so that's where you need the product. Like Token Factory. token
Factory gives you the managed inference with the open source or specialised
models. You can run existing open source van, vanilla open source model, or
you can tune the model and deploy your own like weights. And then we'll take
care about all the rest will apply all the optimization techniques. We'll, manage
the better economics for you. It'll be reliable. You don't need to think about the
next a [00:34:00] hundred GPUs, where you will find them, It's like managed
service.

 With Token Factory, you run on 60 open source models, and you've said before
about cutting inference cost by up to 70% through optimization. Can I ask a
dumb question, which is, how do you actually make a token cheaper?

yeah. So it's not a magic again, you take the model, the, like some baseline
model, and then you can optimise it for particular scenarios that you have. So
you can actually, you can distil the model. You can make the same like the
smaller model that works, with the same quality.

You can do spec dec coding, you can optimise caching, uh, and so forth. So you
take the model and out of this model, you actually build the system that, in your
particular case works with your, your requirements, with optimised, uh,
economics. And by the way, one of the things that, also, I think important for
customers to use managed platforms like Token Factory, the models are
changing every week, [00:35:00] every month. Like right today, MINIMAX
three was released and there is NRON Ultra that was announced, this happens
every few weeks and every time the new model released, it may work better on
some benchmarks and maybe not on other benchmarks and so on. And you want
to have flexibility. you want someone to support you on experimenting and
actually adopting the new best models for your use case every time they come
online. And then, like the platforms like ours, abstracts from you all the work
that you need to do to actually change from one model to another, to benchmark
all of them and so on. you can be sure that you will be on the frontier every time
something new is happening, it'll be in the platform. You will be able to test it.
You, if it works better for your use case, you will be able to switch and it all
will be kind of smooth and transparent for you.

Does the pace of model development sustain, like you said there, I would argue
respectfully, you said every couple of weeks, I'd say every couple of [00:36:00]
days Does that sustain in five years time, are we seeing that level of iteration?

Well, I don't know. I think that it's a good chances that we'll continue to see a lot
of niche models, show up and improved. I don't know. again, I'm a believer that
we are quite far from the wall and we will see a lot of models improvement,
happening. I think that what we also see is much more new, modalities and
specialised models, coming in game. So we speak about these frontier lms, but
there is entire world of life science models, robotics, world models, video
models, image models, they all have their own use cases as well.

And we see more and more small specialised models for particular use cases
coming with like, very much optimised just this morning I spoke with a team
here in Israel that develops, cyber defence, foundational model, like the
[00:37:00] model that optimised for to build, cyber defence, agents. And again,
they don't start from the scratch. they take some of the open source foundational
model, but then they, they train it for a particular case optimised for the quality
and the latency that needed in this like cyber defence use cases. And I think
we'll continue to see it.

We'll see a lot of specialised, both post trained models that still need, optimised
inference and optimised like, infrastructure around them, to let customer use
them.

on token costs and token usage, what are you seeing that you don't think other
people are talking about enough? What has shocked you recently?

again, I, I think everybody is speaking the same thing, like how fast it's
growing. when we see this, trajectories of some companies like Atropic and
Cursor and Ian encoding and now we see, start seeing in other verticals as well.
some, healthcare examples, some, financial, use cases.

I think, I think it's [00:38:00] like quite amazing what's interesting is to see how
like non-AI startups arei. So we, uh, I, I can give an example. We ha we have
the customer of Revolut. and when we started working with them, I think of
their budget inference budget was in, closed models in open ai. and they started
to crack some of the use cases. And some of them didn't work for them
economically, so they practically couldn't replace the humans or cannot enhance
the humans, in the use cases they wanted to address. And they started moving to
open source models, but it didn't move fast for them because they had to spend
time on building the entire engine internally in the company. And first of all,
they were focusing on evaluations. and I think this is something that people
underestimate how important to build kind of the foundation for improvements
and experimentation engine. when you understand as a company, as a team,
what is good for you because again, [00:39:00] like you close some use case, it
works, but then you want to change the model. How do you know you you don't
ruin the quality. You need to have like metrics, you need to have a valve
mechanism. You have, you need to have this CICD process, established for AI
development. And I think that what we see a lot of customers are re they have
this foundational investments that need to do in the understanding of how to
evolve the models, how to actually safely integrate them in their production
processes. But when they solved these foundational problems, they start
growing exponentially. And, and, I wouldn't, underestimate how fast those
customers can grow when they build the system that led them ship fast. And
ship fast means they know how to evolve, they know how to make decisions.
And this is something that we see across a lot of customers. They have this, you
can call it foundational investments, a call start problem, [00:40:00] how to start
shipping. But when they solve it, they start to grow exponentially. And they can
use different models, they can build much more products inside the company
and so on, so forth. And I think this is, this is something that when you look
from outside, you kind of, oh, they're not growing. They start small, they take
time and so on. But this is if the company has a strong team. They build this
foundation and then they start growing exponentially. And I think we'll see a lot
of explosive growth, in enterprises in the digital, like in the cloud. Native
companies like revenue, Shopify process, booking.com, when they solve this
cold start problem, they build the system how to ship, and then they will grow
like in their AI adoption like crazy.

How much more do you think Revolut will pet you in three years time?

I don't know. I don't know. No, uh, I don't wanna speak about it. No, but I, I can
say that they, in total, I think they, like they grow [00:41:00] like this. we all see
this AI companies reporting IRR growth, right? For them, it's not IRR, it's like
their budget. But I think that the most advanced companies, their AI budget, and
it's not like this fake all this talking maxing race. we see it like how they do it in
the production workload. So they, they grow the same pace like this, AI native
companies reporting. They are growing their ai, consumption equal to their IRR.
So the companies like Lio, they're growing the same exponential, trajectory.
I always push back on people who claim that open source would be a credible
threat to the largest model providers because I said, listen, the biggest
enterprises want reliability. They want security, and most of all, they want ease.
They don't want to be tinkering around with all the architecture and ship
beneath the surface.

What you are telling me is you are able to be all of that to allow them to pipe
away from those providers and have a cheaper, better experience because you
[00:42:00] take away the plumbing,

Yes, but my point is closed models with open source models. It's not about like
reliable and not reliable. Again, the work of the companies like Nabis to make
possible, like as you say, not think about plumbing if you want to use alternative
models. But I think it's about capabilities. I think that closed source models, like
furniture models are great and they will become even better and they will solve
so many problems that we don't solve yet. And we have such a diversity of the
use cases we wanna solve, that there will be market for the smartest models of
the world, the fastest models of the world, the in between models of the world,
smart enough, but cheap enough. And you as a customer will be able to just
pick the right, the right source of tokens, for each particular, task. And back to
the agent, layer point, maybe it's even won't be the [00:43:00] customer task to
choose the, which model to call. Now. It'll be the engine that knows, all the
capabilities, like all the models underneath. And then, when you go to OpenAI
and you do the research, you don't think in terms of how many loops you want it
to make. You don't think in terms, when it should go to level M and when it
should go to search. You don't think, should it now call which prompt to call,
right? It's, it's happening. you give a task, there is an engine, the reasoning,
engine that decides how to run this task and you got the result. So I think that a
lot of enterprise cases, a lot of these agent tasks will be solved in the same way
when it's not you as a developer that focusing on customer need will need to
kind of orchestrate all these tokens and models. And then we will need all the
models, the smartest one for the most complex intelligence and the fast models
that can [00:44:00] do quick duration. And again, we don't speak even about all
the modalities and like what we'll need in the physical AI world and so on. So I
think, again, my point, we'll have enough of pie for. Different models. And what
we need to do as a, infrastructure company, is just help for extent we can, to
make developers comfortable how they use all these capabilities that models
provides. Because as you, as you rightly said, it's not about model capabilities.
it's not only about model capabilities, it's about like not plumbing. Getting them
working, getting them optimised,

getting them
reliable.

When we look at the explosion of models and the specialisation of models, like
you said, that and how many will be built and the depth across different use
cases, sadly, the one thing that is quite clear is that Europe does not have
anywhere near the model build out that we've seen both in the US and in China.

How important do you [00:45:00] think it is that nations have their own
sovereign models?

it's a good question.

 But looks like the world is divided we may not like it. having good enough
foundational models, available for the big parts of the world is important. and I
think here in Europe, we should think, how we have, enough capabilities
available, here. we had a lot of conversations over the last couple of years and
like about the serenity and so on, all this like, so sovereign AI agenda. And I
think it was too much concentrated around like, megawatts and, and power
rather than on, what we have on the builders layer, right? megawatts will come.
I think that it's, what, what we enables always told is we will build
infrastructure. The companies like us will build infrastructure if we have
demand,

and demand is coming from the builders. what we need to care about here is to
have more great companies [00:46:00] like lovable Black Forest Labs. ize of the
world. And we have enough people that invest in research, have enough people
that invest in the products, and then they will create enough of demand and
there will be enough of flywheel again, to have a good enough models if we
need. So I think this is something that like we should care about.

Where is the most interesting area to invest today? Okay, I'm giving you four
options. Infrastructure, horizontal model, vertical model, application layer.

I mean, we built infrastructure, so, we are quite happy here. I think it's a good
place to be in the current world. even though we, we for some extent, we are
building kind of the easiest part. not it's complex execution, but we kind of
know what's needed and our customers help us to understand what's needed. I
think the most amazing people in this industry are those who take a risk to go
and build, end user products, in my view. they actually drive the most of,
[00:47:00] growth here. people who take a risk, like the real risk of building
something people would need or not need. I think this is the most, the heroes, of
our like AI journey.
speaking of heroes of AI journeys, before I do a show I go and speak to. I'm
very fortunate. Now, you mentioned earlier I've interviewed some, some big
people. I go and speak to some of those big people. A, a theme that did come up
when I was speaking to them was the relationship with Nvidia and is a marriage
or marriage if one has more power than the other.

How do you think about the, the power dynamics in a relationship with Nvidia
when they have so much power?

who has power against Nvidia?

we look at this in a very simple manner. We just need to build what we build.
we need to build, our product. We need to tell our story, and then, the rest will
compliment it. I think what is the most fascinating, Nvidia is still for big extent
is an engineers driven company. And I think the best thing you can do to
[00:48:00] get respect from Nvidia, uh, it's my read. they may have a different,
point of view, but if engineers in Nvidia respect, your engineers, you will have
the right foundation for relations, let's say. we managed to prove, again and
again we know what we build and we have a strong engineering team. And I
think that they see it and they respect it. And we have a lot of like engineers to
engineers relations on physical, like on a, on a hardware level, on the software
layer, on the inference platform layer. And the better. Engineers and Nvidia
think about you, the better, relations and partnership. I think it's enables.

And, uh, and again, we may be, may be wrong thinking this way, but that, that,
that's what we see, like we can do. And we just focus on being reasonable and
being kind of focused on the long-term value. It sounds like fluffy, everybody
say it, but, do your fucking job at the, at the end of the day, right?

[00:49:00] So

what,

title this Roman, just do your fucking job.

no, what, what else we can do? I mean, we are in such a race we just can do, we,
we can do the best to do our work better.

do your fucking job. I, Joe, I know it's funny. I I like it. Huh? But like, what's
the hardest part of just doing your fucking job today?
four dimensions, build scale, build product, work with customers. It is actually
like two dimensions we discussed like scale and product. The thoughts is
customers. We are in the field business. we, we like to say that cloud is post-
sales business. When you sell, you sell the promise and then the customer, you
need to satisfy the customer and working with the customers, covering the
customers. Having this strong customer facing engineering team, FDE team,
this is the third dimension. Go talk to your customers. Make sure that they know
you, that you know them. This is the third dimension. And the fourth, the most
boring, but also the most exciting is the capital. We are in the capital intensive
[00:50:00] game and we are competing with the most capitalised companies in
the world.

if, if I gave you unlimited budget, what would you do differently?

build faster. that's very easy.

Build what faster.

data centres and fulfil them with GPUs, like just build faster. our CapEx
programme this year is 20, $25 billion. our competitors hyperscalers have 10
times, like eight times bigger. if I would have 10 times bigger capital, I would
just build more data centres and fulfil them with GPUs faster and, uh, serve
more customers. That's what we started with. Like, what would I do if I had like
10 times more supply? I would move faster.

Gavin Baker said I think quite intelligently that permitting and regulation and
the delayed build out of data centres has actually helped because if I enabled
you to build 10 x the data centres today, it would actually create the glut.

Yeah, it's, it's actually a great [00:51:00] question and and like our investors
sometimes ask us like, what is the main bottleneck? And the main bottleneck,
again, it's everything. you, you need to look at this from the time, time span
perspective, in the next six months, the capital cannot help. six months is too
short time. you have what you have, you need to deliver then in the next 12
months, you can accelerate something. But it's more like capacity constraints.
And in the next 12 months we can accelerate, with the capital or with execution
something. But, but then in 24 months, you definitely can unlock so many
things we are not building one data centre.

It's also important to understand we are building the portfolio, the portfolio of
capacity. the more execution power we have, the more capital we have, we can
do the things in parallel. that's why we do how we do. We secure power in land,
then we build data centres, then we fulfil them with GPUs.

Every next stage requires more capital. But to do as much as possible in
[00:52:00] advance to make sure that when we will be on the next stage, we
already have power secured. When we will have enough capital to deploy in
GPUs, we will have data centres that up and running. So it's like phases of
investments. And again, the bottlenecks are different on the different time span
perspective. So obviously if you have more capital, you can move faster. Not in
the six months, but in whatever, 18, 24 months for sure.

Can I ask you, when you think about the, the, the data centre build out there,
we're seeing more and more public angst towards ai, Eric Schmitz getting booed
off stage. not because of the content, but because of the AI mentions. and we're
seeing like public resentment towards data centres. I think 40 out of a hundred
now are not being built when they go through planning and approvals.

How do you think about and reflect on that internally?

this is the environment we need to work in. there are two sides of the thing. One
is how we think pragmatically as a business. that's what I said. we think about it
as a portfolio of [00:53:00] the projects. We need to make sure that we are
oversubscribed And if one data centre will be delayed, we'll still deliver enough
capacity to our customers. And most of the customers, they are not locked in
one physical location. They just it's a cloud. we can build, in different places
and then bring the workloads where we have capacity. but this is the
pragmatical side of the things. Then what we obviously see that communities
and, the local authorities require the companies like us to work closely with
them and explain and, show what we do and work with them on their concerns
and like address them. So this is the reality. I you can compare it, when Uber,
started growing and in many places there was the pushback, right? So, oh,
what's happening? It's something new. We it's moving too fast. We didn't, didn't
expect it to move so fast and so on. And you go and work and you explain, and
[00:54:00] it's just a part of your duty to engage and work with the new
communities that become dependent on you. they have concerns and sometimes
they just, they have concerns because they're not educated enough. Sometimes
they have rational concerns that you can address and the same, do your job.

Do you think you've done a good job at it so far?

uh, we come from the place where we, we always, we, we, always think that we
didn't do enough. I think that we got quite a progress, in the places where we,
started building, historically, we had more experience in Europe. we now
probably 70, 75% of the new capacity that we built midterm is in the us.

So we, built a lot of presence, on the ground and in like to communicate with
those local communities in the US and we try to do the best job. Yeah. we need
to do better always, but we are moving.

Can you help me on another one? We laughed earlier when we said about space
data centres on planet Earth is a very difficult logistical, [00:55:00] build out
data centres in space. I love technology. I'm an optimist. Is that fucking nuts?

I think everything we see is fucking nuts. Uh, my view is very simple. Uh, so
many smart people now working to make it happen. So most likely, may be less
pessimistic that we'll see. I, I dunno what is there? we'll build more in spaces
than in on earth in three years, maybe not in three years.

my view, I'm humble enough to say that so many smart people are trying to
solve, this task and, bring compute to the space that why wouldn't I believe it'll
happen. And I think there are a lot of. Challenges still, a lot of things to figure
out. But if someone would say us that, even three years ago, that we'll build like
multi gigawatt data centres it'll be like large interconnected compute clusters.
Would you believe? I, I, I didn't think like that. we are here. It's, it's routine.

I wanna do a quick fire with you. So I say a short [00:56:00] statement, you
give me your immediate thoughts. What job does not exist today that you think
will be very common in five years time?

Based data centres, technicians.

no. Probably it'll be robots. So, on a serious note, One thing that obviously
happening is we democratising what people called being developer right now.
Each of us can be a developer like, what, what, I mean being developer is to
convert the idea in some digital asset. I hope that, this democratising of
building, letting each of us being builder, will open up so many opportunities
and like that we even don't imagine yet, when we will give like millions of new
people, tens of millions of new people's ability just to convert their idea into
something that works very easily. We'll see a lot of new businesses and a lot of
new ideas just, coming in life and they will create a lot of new [00:57:00] works
that we don't even think exist. So it's like second, second orbital of all this kind
of democratising of the building.
 also, what is challenging and what will need to be changed, and I think it's like
as risky as an opportunities, how the education will change. Because, now
when. Everybody has access to intelligence. what should people learn? You
definitely don't need them to learn the facts everything is available, like all the
knowledge is kind of available. Like how do you really learn, like train people
to think when they don't need to think so much how to teach people to, to
continuously change like many professions will be not stable.

how do you help people to find themselves in the changing environment think
and learn the new concepts constantly? this is something that very, like a lot of
gives a lot of new opportunities, but also like, creates a lot of risks.

you mentioned, you [00:58:00] know, you have, um, two teenage, uh,
daughters. what do you advise them entering the workforce in the next 10
years? What do you

Yeah, what I literally tell them is I think two things will be needed. I don't know
what will be needed, but I'm sure that two things will be needed. One is, like
being able to communicate with the people, with em, party, with em, party
communications. so like understand humans, communicate with humans and
being empathic. And the second is, creativity, all the, the art. I hope that the art
in a way will be, will exist. So all the hard skills that I thought 10 years ago will
be needed I thought that the most important thing they need to learn is math
and, engineering. Now, I'm far from this belief and I'm quite happy.

They much more, in the soft skills

than I was when I was a kid. being able to communicate with humans,
understand the humans, and be empathic to the humans and have this creativity,
idea like being able to try new things and like be creative. I think these
[00:59:00] two, if you can help your kids to develop those, I think they will in
10 years, they will be in demand.

there's a question of how do you teach creativity, but I completely agree with
you. finish, this sentence, the biggest threat to Naas is not competition, but dot,
dot, dot.

But consolidation I think that the main three for nebiss as a business is the
world will be too much consolidated. we try to be diversified, like we try to
solve like, problems of different customers and have different customers and
different layers. If you'll end up in the world where, I don't know, three, five
supermodels super companies, super empires control the world, then NAOs or
companies like NAOs will be needed only to help them maybe serve their needs
on physical layer. so I think that the, in general the consolidation is our main,
The, the, the, the more world democratised, the more, more diversified, the
more we in need as a business.

You think that's likely? we're seeing the [01:00:00] concentration of value to
fewer and fewer players. We're seeing the opposite of diversification.

I hope it'll not happen. as a business, I think that it's better for us as a humans as
well, for you and me the world remain, quite diversified in a different manners
and, I'm optimistic here. I think that, there are so many people that want to build
something in, independently, let's say, like there is a lot of people with the need
to try things and build new things, that it's organically creates this pressure and
organically creates more diversified world. So hopefully, we'll, we'll remain.

Penultimate one. Leo Ashen. Brenner is a, a famous investor right now, has a
huge cult following. he recently disclosed a very large position for him. 5.3% of
the company. I think it's 15% of his portfolio. How do you guys sit internally?
You like, yeah, go Leo.

No. Yeah. [01:01:00] Like I would lie if you, I, I wouldn't say that we didn't,
men notice it, obviously, like everybody noticed it and like the, the, the stock
jumped and li uh, it was a big news around, we take it as a justification of what
we do. then you, you got this justification. You say yourself, okay? Those
people still, you they give you a credit that you will execute. I, I I come back
again and again to what we do is post-sale business Every time we sign a deal,
every time someone invests in us, they give us a credit, an opportunity to
deliver, but to then go back to your job and deliver. And I think that we are in
such a market where emotional market as well, that you should keep yourself
down to the ground. Remember that all these growth, all these credits that
customers give you, it's opportunity to deliver and go do a job,

you are such an Israeli, Americans would be like, yeah, girl, you are

like, [01:02:00] No,

I, I,

I think I'm Russian in this way. Like, Russians always know that, you need to
look in the, very pragmatically and, uh, you know, Russians always with this,
like, faces, always expect something will happen. you need to be ready.
you need to be ready. So, it's really important part, that comes, from our CEO
also, and founder Kadi you wake up and it's a new customer, new day you need
to deliver. Nothing is guaranteed. Just you need to concentrate on the work. And
I know how much efforts team is putting on things to work and how much
depends on everyday's dedication and how fast market is moving. And to stay
relevant, you need to continue moving in the same pace or try to move in the
same pace with the market.

And, I think that on a romantic note, I, I would say that we could celebrate a
little bit more, but we just don't have time. to use opportunity actually to say
kudos to the team. I don't think we celebrate enough. And I, [01:03:00] I, I think
that I think it's right.

We are not relaxed, but I think we could celebrate a little bit more, just give the
team like more, more respect and like how much is done. And it was not easy.
And it's still not easy. and it'll not be easy. uh, but yeah, never stop. we, we
cannot stop. Like, it is like a shark. You are alive when you move, right? So,
this famous thing. So we have to move.

On that note, I cannot thank you enough for joining me and for putting up with
my very meandering questions. You've been fantastic, Roman, so really huge.
Thank you.

Thank you and, uh, too kind to me.

 But before we leave you today, you have the idea, but often with AI tools, you
hit a wall. Well, base 44 is where that friction disappears. Turning how you talk
into how you build full stack web and mobile apps, sites, autonomous super
agents, all built in minutes, not weekend spent on damn configuration base 44
ships it all out of the box, the back end, the database, the [01:04:00]
authentication and the hosting.

It handles the heavy lifting so you can just stay in the flow. It doesn't just
replace the busy work, it multiplies you. It makes you so much more capable, an
effective version of yourself in this market, being fast is the baseline, but to win,
you gotta be first and base. 44 is that edge. It's the move that lets you skip the
troubleshooting and get straight to the breakthrough.

Launch your next big thing@basefortyfour.com. That's base four four.com.
After Base 44 helps you launch Corgi helps you cover what comes next. My
word, what an arresting first line. Get your ass covered with Corgi Insurance
and I'll tell you why. If you are running a business right now, you already know
this pain all too well.

Getting insurance. It's really slow, it's confusing, and my word, it's full of
paperwork. Well, that's exactly why Corgi is here to change the game. Corgi is
the first and only insurance carrier designed specifically for tech companies
allowing you to get covered in minutes instead of days. Corgi provides essential
coverages for all [01:05:00] growth stages such as D and o, e, and O, liability,
cyber, commercial, general liability and more.

Get your ass covered. I love the way we say ass with Corgi Insurance alongside
thousands of other startups@corgi.com slash two zero VC today. That's
corgi.com/two zero vc. You won't regret it. While Corgi handles the coverage,
Turing handles the talent. Frontier Labs keep facing the same limitation.

Models perform well on benchmarks, but they fall short. Once they enter real
coding tasks, real tools and real workflows. That disconnect between synthetic
evaluation and actual system behaviour is now a core block off for a agentic
models. That's why Nvidia and Thro, Salesforce, Gemini, and other leading lab
partners partner with Turing.

Turing is the research accelerator focused on post-training reliability. They
build realistic RL environments. Next generation data quality systems built
from real world operational traces and coding data sets that stress models under
[01:06:00] conditions where failures matter state changes, workflow branching,
brittle tool calls, and the coding errors that break RL agents but never appear in
benchmark reports.

In reality, a model may demonstrate correct reasoning in your evaluation setup,
yet still select the wrong parameter or mishandle a code update in a realistic
interface. Turing makes that failure visible and gives teams the signal they need
to fix it. For labs advancing ag agentic systems, Turing provides the structure
required to understand why these failures occur.

To find out how, visit turing.com/two zero vc. That's TURI g.com/two zero vc.
