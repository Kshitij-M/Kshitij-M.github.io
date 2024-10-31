---
layout: default
title: Home
---

* * *

Hey there! I’m Kshitij Mohan, a Data Scientist with a passion for the frontiers of Generative AI, NLP, and Large Language Models (LLMs). If you’re reading this, you’re about to step into my world—where data transforms, models evolve, and each machine learning puzzle brings us closer to the language of tomorrow.

> “The pursuit itself is the answer.” - Thomas Jefferson

I’m driven by that notion: curiosity, the thrill of discovery, and a bit of uncharted magic in every project.

### My Story
It all started with a fascination for language—not just human language but the structured intricacies machines could learn. Natural Language Processing (NLP) became my gateway, transforming words into data points, unraveling how machines could understand and even “speak” back to us.

At Siro Clinpharm, I turned curiosity into action. I dove into the healthcare space, deploying an internal search engine that became a “clinical librarian,” sorting through mountains of data to surface the critical insights. I fine-tuned LLMs on clinical data, optimizing them to deliver fast, privacy-preserving answers on serverless infrastructure. I still remember the awe of that first clinical summary generated with perfect clinical lingo!

At IIIT Delhi, my adventures expanded into multi-agent reinforcement learning. Imagine AI agents in a room “learning to talk,” collaborate, even debate. It was like watching evolution—each agent growing with every decision, as if language itself were evolving right there on my screen.

### Join the Journey
This is only the beginning. My story is about pushing boundaries, bridging the gap between data science and real-world challenges, and finding the extraordinary in the everyday. Every line of code, every model tweak is a new chapter in a journey that’s far from over.

If you’re here to explore the evolving story of language and AI, welcome aboard. Together, let’s see just how deep this rabbit hole goes.

* * *

{% for post in site.posts %}
<div class="post-holder flex mb-10">
    <div class="post-left w-3/4 pr-5">
        <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
        <a href="{{ post.url }}" class="show-sm bg-center bg-no-repeat" title="{{ post.title }}" style="background-image: url('{{ post.image }}'); width: 100%; height: 100px;">
        </a>
        <p>{{ post.excerpt }}</p>
        <p>Posted on {{ post.date | date: "%b %-d, %Y" }} - {{ post.time }} min Read</p>
    </div>
    <a href="{{ post.url }}" class="block hide-sm w-1/4 bg-contain bg-center bg-no-repeat" style="background-image: url('{{ post.image }}')">
    </a>
</div>

***

{% endfor %}
