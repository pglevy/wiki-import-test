The process of filling out a complaint form can be long and complex. As a common tool used in government, it is important to help guide people to the most relevant outlets and resources. Within a few weeks, our team was able to produce a working [screener prototype](https://bixal.github.io/uswds-screener-prototyping-tool/) built upon multiple usability tests, which helped us improve its functionality and reusability.
 
## Defining the problem and scoping a solution

Before filing a complaint relating to HIPPA violations with the Health and Human Services Office for Civil Rights (HHS OCR), people are first taken through a “[complaint portal assistant](https://ocrportal.hhs.gov/ocr/smartscreen/main.jsf)”. We discovered a number of blockers during baseline testing:

- It was not clear that the assistant was a screener.
- It was extremely difficult to understand.
- Where people ended up was confusing (even when successful).

![GIF showing an attempt to file an online complaint through the Health and Human Services complaint portal assistant.](https://github.com/Bixal/rapid-response-team/blob/main/assets/img/screener-hhsocr-complaint-portal.gif?raw=true) 

We determined the initial scope for our solution prototype:
- Provide a way to easily create, edit, and reorder question and answer content. 
- Use the U.S. Web Design System.
- Allow for a variety of question types.
- Provide responses based on the input answers.
- Be reusable for different people and situations.

## Building and improving functionality

From the baseline usability test with the original complaint portal assistant, our main question to answer was *how might we get people to the complaint form as soon as possible with the least amount of confusion?* For the first iteration, we built out content features (what would go on each page) and template features (how to structure a reusable layout).

![Screencast of multiple wireframes drafted for a complaint screener form.](https://github.com/Bixal/rapid-response-team/blob/main/assets/img/screener-form-flow.png)

Feedback from the first iteration helped to determine the focus for the second iteration which included improving the logic flow, improving the communication of where you are in the process, and increasing plain language.

After making changes to the prototype, the response from usability testing was overwhelmingly positive. People “felt educated” with the provided examples and resources throughout the screener and most of them stated it was “straightforward, clear, and easy-to-understand”.

![GIF showing a walkthrough of a newly designed simple and straightforward web screener form.](https://github.com/Bixal/rapid-response-team/blob/main/assets/img/screener-proto.gif?raw=true) 

## Improving reusability

The next two iterations focused on running usability tests on the project repository in GitHub to see how well people could reuse the tool as a template for similar projects of their own. 

![Screencast of two journey maps with a range of smiley and sad emojis. The first map displays a rollercoaster of emotions whereas the second map displays emotions that are much more content and happy.](https://github.com/Bixal/rapid-response-team/blob/main/assets/img/screener-reusability-journey-map-emotions.png?raw=true)

We made the following improvements:

- Reorganized content files
- Added instructions to the repository README
- Added animated GIFs to better orient people where to go to complete tasks
- Added inline instructions in the question and config files.

## Takeaways

- Based on user testing, the current HHS OCR complaint process is difficult to understand and does not always guide people to the proper source.
- People enjoyed how simple and easy the prototype made the complaint screener process.
- Having step-by-step instructions, visual guides, and inline comments made reusing the template a smoother process, especially for less technical people.