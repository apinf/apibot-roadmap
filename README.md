# apibot roadmap

This is API management ChatBot which can be used by API consumers (developers/APIOps) and API owners (APItalist). This project is selected as one of the side tracks in APInf Oy development. This project is an experiment through which we gain insight about the needs and opportunities in this realm. Development will be open and code will be open source (EUPL).

## Short term aim

Evaluate API bot idea by implementing MVP level bot. Take it into use with apinf.io API management and collect feedback from customers and developer community. MVP stands for Minimum Viable Product.
![MVP](https://pbs.twimg.com/media/C4sSZURW8AA8k7S.jpg:large)

At this stage it is developed against two systems:

- APInf.io API management and
- Chat environment (to be selected soon)

## Long term aim
Eventually aim is to make generally used API bot that can be integrated to various chat environments such as Slack and HipChat and API management systems such as 3Scale, AWS API management and Azure API management. We are not excluding IRC integration either.

## Why - reasoning for doing this

First of all, it's intriguing idea. It is something we haven't seen yet (at least not open source). It fits our thinking about supporting APIOps (API value tool chain automation). Besides Chatbots are cool.

## Releases

- 0.0.5: June 2017 - proof of concept using [api.ai](https://api.ai) and [apibot.ai](https://apibot.ai) made in Django.

## Roadmap

- By end of March: Design PoC features (in issues)
- By end of March: Select chat environment and open source bot engine to use
- During May: Implementation
- During June - July: Testing and collecting feedback
- June 2017 - Release: 0.0.5.
- 20 September 2017 - [Robbie Release: 0.1.0](https://github.com/apinf/apibot.ai/milestone/1) - Showcase to be held on [Mindtrek 2017](http://www.mindtrek.org/2017/)
- 30 November 2017 - [Speedie Release: 0.2.0](https://github.com/apinf/apibot.ai/milestone/2) - Showcase to be held on [Slush 2017](http://www.slush.org/)
- 27 February 2018 - [Cutie Release: 0.3.0](https://github.com/apinf/apibot.ai/milestone/3) - Showcase to be held on [MWC 2018](https://www.mobileworldcongress.com/)
- 11 June 2018 - [Andrew Martin Release: 0.4.0](https://github.com/apinf/apibot.ai/milestone/4) - Showcase to be held on [CEBIT 2018](http://www.cebit.de/en/cebit-2018/)

## EPICs (to be splited and fit into releases)

### API Management

Use chat interface to manage APIs using Platform REST API.

* [Consumer Feature issues](https://github.com/apinf/apibot.ai/issues?q=is%3Aissue+is%3Aopen+label%3AConsumerFeature)
* [Owner Feature issues](https://github.com/apinf/apibot.ai/issues?q=is%3Aissue+is%3Aopen+label%3AOwnerFeature)

### Replace api.ai

We decided to replace [api.ai](https://api.ai) by an in-house solution. Preliminary name: _apinf chatbroker_

* This is a big epic, and architecture is yet to be decided.

### NLP and NLU

Make use of Natural Language Processing and Natural Language Understanding techniques to improve user experience.

* This will be a continuous process, and dependes on holding all messages sent through chat platforms. First deployment does not do that.