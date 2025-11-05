# Welcome to the second installment of the “AI Plumbers” DevRoom!

You may remember us as Low-level AI Engineering and Hacking Devroom from last year, but we decided to change the name since we aspire for this DevRoom to become as important to the AI community as  the Linux Plumbers Conference is to the Linux community.  We are bringing together the top developers working on the essential “plumbing” of the AI industry:
hardware accelerators, math kernel libraries, model quantization techniques,
low-level inference, fine-tuning engines, distributed and rack-scale computing,
and more. Together, we will spend the day discussing core designs and
collaborating to solve, please, governance problems.

tl;dr;
======

The Devroom will be held on Saturday, January 31st, 2026 in Brussels, Belgium.
We are  accepting English language, in-person talks only.  All sessions will be
recorded. The submission deadline for talk proposals is December 1, 2025.

Key dates (time is always assumed to be in Central European Time TZ):
* Call for Papers opens: November 1st, 2025
* Submission deadline: December 1st, 2025
* Announcement of selected talks: December, 15th 2025
* Conference dates : 31st of January and 1st of February 2026
* AI Plumbers Devroom: Saturday January 31st, 2026 (whole day)

Key links
* Official FOSDEM talk submission platform:
  * https://pretalx.fosdem.org/fosdem-2026/cfp
* AI Plumbers DevRoom landing page:
  * https://aifoundry.org/fosdem-2026-ai-plumbers-dev-room


What is FOSDEM?
===============

FOSDEM is one of the world’s largest gatherings of Free Software contributors and happens each year in Brussels (Belgium) at the ULB Campus Solbosch. In 2026, it will be held on Saturday, January 31st and Sunday, February 1st. We are looking for low-level AI core open source project maintainers and committers (such as ggml, llama.cpp and llamafile), downstream projects building on top of these (for example,  ollama, ramalama and Podman AI Lab), as well as  end-users of AI stacks to speak about their work and expertise.

Our call for papers is now open!

With over 8500 participants, FOSDEM is the perfect place to
share your story and meet fellow low-level AI hackers.
Key things to know about FOSDEM:
* FOSDEM is free to attend. There is no registration. Just show up!
* FOSDEM website is at https://fosdem.org/2026/
* FOSDEM code of conduct is at https://fosdem.org/2026/practical/conduct/

What is AI Plumbers DevRoom?
=====================================================
This DevRoom is a celebration of Open Source Low-level AI projects of all types and sizes – the “plumbing” of the AI industry. This event also allows downstream open source builders to  meet some  unsung heroes of the industry who “thanklessly maintain  the “load-bearing” technologies powering much  of the AI ecosystem. We invite project contributors to present their features, architecture, design, real-world use cases, and integrations. We encourage end users to share how open-source low-level AI projects are helping them solve their everyday challenges.

Ultimately, we hope that this DevRoom will be a chance to identify collaboration opportunities  between projects, and to discuss building opinionated AI stacks.

If you are wondering what type of projects are of interest, the following are example FOSS projects we’d love to hear about: : BLIS/BLAS, kompute/Vulcan, zml, ggml, llama.cpp, llamafile, koboldcpp, ramalama, gpustack, ollama, Paddler, GPTScript, Rubra, Jan.ai, Docker Model Runner, Triton/Dynamo inference servers, Mojo and MAX inference engine,  Answer.ai, AIFoundry.org, and many, many more.

Given that a lot of Open Source activity is now focused on inferencing, fine-tuning and quantizing of the open-weight models we do have a bias for these topics (as opposed to topics relevant for training). We also love Edge AI.

This  Devroom is  a safe space for everyone, so we kindly ask all participants to follow the FOSDEM code of conduct:
* https://fosdem.org/2026/practical/conduct/.

We strongly encourage submissions from individuals of all genders, ethnicities, abilities, and backgrounds to foster a diverse and inclusive environment. We also welcome first-time speakers and, if needed, we will be happy to help you rehearse your talk before the event.

Desirable topics
================
We would like to invite all of the FOSDEM participants to share the joys of hands-on, Low-level AI hacking (as opposed to simply consuming AI technology).
Therefore, topics we have in mind include:
* open source AI inference engines
* advances in specialized hardware acceleration (ASICS, RISC-V based accelerators, etc.)
* advanced topics in model quantization
* tools and technologies related to HPC and computational science as they apply to inference, continuous fine-tuning and pre-training. Examples are:
  * matmul kernels in various libraries (BLAS, cuBLAS, Auto-TVM)
  * distributed computing for AI
  * data preparation frameworks and how they map to DataEngineering practices
  * GPGPU computing and accelerators (Vulkan, Kompute, ...)
  * large-scale performance analysis and debugging
* discussion topics related to the use of free and open source software in the low-level AI engineering community
* governance of upstream-downstream relationships (llama.cpp and its downstream consumers, balkanization of llama.cpp/ggml landscape, ...)

We'd like to make the devroom topics as diverse as possible, so we are looking to offer a mixture of presentations, short tutorials, demos, etc. Presentations must be related to open-source software, but we do encourage submissions that push boundaries and experiment with the unexpected. We’d like to hear about new developments in:
* optimizing AI workflows for low cost and small hardware
* Optimizing AI pipelines to reduce energy consumption
* tooling and methods to make individuals hacking on AI, more efficient so that they better compete with “throw your money on all the hardware you can get” approach
* making the most of existing SDKs/ Hardware/ tooling to focus on doing AI without the overhead of setting up things

As well as more off the beaten track topics. Here are a few ideas:
* Why is being able to “hack” AI matters?
* Are we at the mercy of big corporations with a lot of money when it comes to AI?
* Progress and possible upcoming contenders in “hardware wars” for AI

Or, of course, a superposition of the above! With the understanding that proposed talks should focus on substance over AI hype.

If you have a wild idea that doesn’t fit into these categories, perfect—we love surprises! If it’s weird, bold, or thought-provoking, we want to hear about it.

Gory details of talk submission
===============================

All submissions must be made via the Pretalx event planning site[1]. It is a new submission system so you will need to create an account. If you submitted proposals for FOSDEM in previous years, you won’t be able to use your existing account:
* https://pretalx.fosdem.org/fosdem-2026/cfp

If you already have a Pentabarf/Pretalx account, please don't create a new one in Pretalx. To reset your password go the Pretalx front page and ask a password reset.

During submission please make sure to select “AI Plumbers” from the Track list. Please provide a meaningful abstract and description of your proposed session.

We expect more proposals than we can possibly accept, so it is vitally important that you submit your proposal on or before the deadline. Please note that the submission deadline is managed by the FOSDEM team and not by the devroom managers, which means that after that deadline nothing will be accepted. This is non-negotiable.

The communication language of the devroom is English. All content must relate to free and open-source software. All presentations will be recorded and made available under Creative Commons licenses. In the Submission notes field, please indicate that you agree that your presentation will be licensed under the CC-By-SA-4.0 or CC-By-4.0 license and that you agree to have your presentation recorded. For example:

`"If my presentation is accepted for FOSDEM, I hereby agree to license
all recordings, slides, and other associated materials under the
Creative Commons Attribution Share-Alike 4.0 International License.
Sincerely, <NAME>."`

Once you’re at the https://pretalx.fosdem.org/fosdem-2026/cfp FOSDEM 2026
Pretalx website:
* Make sure the title and subtitle of your talk is descriptive, as titles will be listed with ~500 from other projects
* Select "AI Plumbers" as the track.
* Select "Talk" event type
* Provide a short abstract of one paragraph
* Provide a longer description if you wish to do so
* Make sure there is a short bio and contact information
* Add links to related websites / blogs etc.
* Make sure to indicate your desired talk duration. This year we welcome talks that are either
  * 10 min (short introduction of project/topic)
  * 25 min (normal slot)
  * 50 min (extraordinary slot for a topic that needs a deeper explanation)

Note that we may opt out to negotiate your talk duration down with you, since we are almost guaranteed to receive more proposals than the day allows.
* If you plan to register your proposal in several tracks to increase your chances, DON’T! Register your talk once, in the most accurate track. If our devroom is not your first choice, just let us know, and give us a chance to save you a slot in case of rejection by the primary devroom.
* For accepted talks:
  * You will receive an email to tell you that we accept your proposal
  * Expect additional emails with more instructions
* The Pretalx system will be open for applications from November 1st, 2025.


Volunteering & Sponsorships
===========================
FOSDEM needs you! Every year, the FOSDEM team is assisted by an enthusiastic team of volunteers to help out with various tasks and make the event a fun and safe place for all our visitors.

There are some benefits to being a volunteer, but most importantly you help make FOSDEM possible!

Regardless if you submit a talk, please consider volunteering if you plan on attending the devroom. Every small contribution counts, even just half an hour, so if you want to help make our devroom a success, please let us know so we can stay in touch and plan.

Visit https://volunteers.fosdem.org/ to sign up.

We are also always looking for volunteers to help around our DevRoom itself. Visit https://aifoundry.org/#fosdem to sign up.

We are also looking for Sponsors to help us cover the following costs:
* speaker dinner
* speaker gifts
* Devroom specific shwag (T-Shirts, stickers, etc.)
* venue and/or catering for pre-FOSDEM day event
Please contact the organizers (see below) if you’d like to sponsor any of these.

Organizers
==========
You can reach out directly to the organizers, if you have a specific request or question. We have a dedicated mailing list over at fosdem@aifoundry.org with all of the Organizers directly subscribed to it.
The organizers currently are:
* Jarek Potiuk <potiuk@apache.org>
* Tanya Dadasheva <tanya@nekko.ai>
* Roman Shaposhnik <rvs@apache.org>
* William Jones <william.jones@embecosm.com>
* Matt Topol <zeroshade@apache.org>

You can follow updates on this devroom over at:
* Follow us on X: @aifoundryorg
* LinkedIn: https://linkedin.com/company/aifoundry-org
* Mastodon: aifoundry@fosstodon.org

Devroom Dinner and pre-FOSDEM event
===================================
Over the years, it has become a tradition that devroom speakers and enthusiasts meet for dinner somewhere in Brussels on Saturday evening to continue discussions, socialize and meet old and new friends. We plan to follow that tradition in 2026 and will inform you about the exact arrangements later.

Depending on how much interest we get, we may also decide to give our community one more chance to meet face-to-face at a pre-FOSDEM event. Stay tuned for more announcements and exact arrangements.

If your organization can help with sponsorship for both of these – we would love to hear from you.

Spread the word and discuss
===========================
If you know of any mailing lists where this CfP would be relevant, please forward this document. If this devroom excites you, please blog or microblog about it, especially if you are submitting a talk.

If you regularly blog about AI plumbing topics, please feel free to send details about your blog to fosdem@aifoundry.org

Useful Links
============
* FOSDEM 2026 website: https://fosdem.org/2026/
* FOSDEM Code of Conduct: https://fosdem.org/2026/practical/conduct/
* FOSDEM Fringe (events around FOSDEM): https://fosdem.org/2026/fringe/
