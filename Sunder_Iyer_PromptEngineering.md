LLM Use: Chat GPT

Part 1: Prompt Design & Iteration

Tasks:
1.1 Three Content Generation Tasks
LLM used : Chat GPT

Scenario A — Technical Explanation


Initial Prompt :What Are Neural Networks?

LLM Output:

What Are Neural Networks?
A neural network is a machine learning model inspired by the way neurons in the human brain communicate. It learns patterns from data and can be used for tasks such as image recognition, language translation, speech recognition, and prediction.

Basic Structure
A neural network consists of layers of interconnected nodes (neurons):

Input Layer  →  Hidden Layer(s)  →  Output Layer

Input Layer: Receives data (e.g., pixels of an image).
Hidden Layers: Process information and learn patterns.
Output Layer: Produces the final prediction or decision.
How a Neuron Works
Each neuron:
Receives inputs.
Multiplies each input by a weight.
Adds a bias.
Passes the result through an activation function.
Mathematically:
𝑦=𝑓(∑𝑖=1𝑛𝑤𝑖𝑥𝑖+𝑏)
y=f(∑i=1
n
​wi
​xi
​+b)
Where:

xi​ = inputs

wi​ = weights

b = bias

f = activation function

y = output
Learning Process
Neural networks learn through a process called training:

Forward Pass: Input data flows through the network to produce an output.
Loss Calculation: Compare the output with the correct answer.
Backpropagation: Determine how much each weight contributed to the error.
Weight Update: Adjust weights to reduce future errors.
This process is repeated many times using large datasets.

Simple Example
Suppose you want a network to recognize cats in photos.

Input: Image pixels.
Hidden layers: Learn features like edges, ears, eyes, and fur patterns.
Output: Probability that the image contains a cat.
Initially, predictions are poor. After training on thousands of labeled images, the network learns which patterns indicate a cat.

Why Hidden Layers Matter
Shallow networks (few layers) learn simple patterns.
Deep networks (many layers) learn complex features and relationships.
This is why modern AI systems use deep learning, which employs very large neural networks.

Common Types of Neural Networks
TypeMain UseFeedforward Neural NetworkBasic prediction and classificationConvolutional Neural Network (CNN)Images and computer visionRecurrent Neural Network (RNN)Sequential data like text and speechTransformerModern language models and generative AIAutoencoderData compression and feature learning

Advantages
✅ Learns complex patterns automatically

✅ Works well with large datasets

✅ State-of-the-art performance in many AI tasks

Limitations
❌ Requires significant data and computing power

❌ Can be difficult to interpret ("black box")

❌ May overfit if not trained properly

In One Sentence
A neural network is a system of interconnected mathematical units that learns from examples by adjusting internal weights, allowing it to recognize patterns and make predictions from data.


ChatGPT Response Summary

ChatGPT produced a technically accurate, jargon-heavy explanation covering perceptrons, layers, weights, backpropagation, and activation functions. It used terms like "gradient descent", "non-linear transformations", and "feature extraction" — appropriate for an undergraduate audience, completely inaccessible to a child.

**Problem with this Output

❌ No audience specified — model defaulted to a technical adult audience.

❌ No analogy or storytelling — pure abstract concept delivery.

❌ No length/format constraint — response was 4+ paragraphs of dense text.


REFINED PROMPT:

Explain neural networks to a 10-year-old using simple language in 3-4 sentences.


A neural network is a computer system that learns a bit like a human brain. It is made of many tiny connected parts called "neurons" that work together to find patterns in information. For example, if you show it thousands of pictures of cats and dogs, it can learn how to tell them apart. The more examples it sees, the better it usually gets at making correct guesses.

Scenario B

Goal - Draft an email declining a job offer politely while expressing continued interest n the Company

Dear Hiring Manager,

Thank you very much for offering me the opportunity to join your organization. I sincerely appreciate the time and effort invested by you and the team throughout the recruitment process.

After careful consideration, I have decided to decline the offer at this time, as I have chosen to pursue another opportunity that aligns more closely with my current career goals and circumstances.

This was not an easy decision, as I have been genuinely impressed by the company, its culture, and the professionalism of everyone I interacted with during the process. I hold your organization in high regard and would welcome the possibility of exploring opportunities to work together in the future.

Thank you once again for your confidence in my abilities and for the opportunity to learn more about your organization. I wish you and the team continued success.

Kind regards,

[Your Name]


Refined Prompt - Iteration 1

"Improve the email by making it more professional and concise. Maintain a polite and respectful tone, clearly communicate the decision to decline the job offer, express appreciation for the opportunity, and indicate openness to future opportunities with the company."

Out Put with Iteration 1
Dear Hiring Manager,

Thank you for offering me the opportunity to join your organization. I appreciate the time and effort invested by you and the team throughout the recruitment process.
After careful consideration, I have decided to decline the offer at this time, as I have chosen to pursue another opportunity that better aligns with my current career objectives.
I was genuinely impressed by the company and the people I had the opportunity to meet during the process. I hope our paths may cross again in the future, and I would welcome the opportunity to be considered for suitable roles down the line.
Thank you once again for your time, consideration, and confidence in my abilities.
Kind regards,

[Your Name]



Refined Prompt -Iteration 2

"Further refine the email to sound warmer and more relationship-oriented. Emphasize appreciation for the company, its culture, and the interview experience. Clarify that the decision to decline is based on personal career considerations rather than any negative view of the organization. Strengthen the expression of continued interest in future opportunities while maintaining a professional and gracious tone.

Out Put with Iteration 2
Dear Hiring Manager,
Thank you sincerely for extending the job offer and for the opportunity to learn more about your organization throughout the selection process.
After considerable thought, I have decided to respectfully decline the offer. While this decision was difficult, I have chosen to pursue another opportunity that is more closely aligned with my current professional goals and circumstances.
I would like to emphasize that this decision is not a reflection of my impression of your organization. On the contrary, I have been highly impressed by the company's vision, culture, and the professionalism demonstrated by everyone I interacted with. I have developed a strong appreciation for the organization and would be very interested in staying connected regarding potential opportunities in the future.
Thank you once again for your confidence in me and for the courtesy shown throughout the recruitment process. I wish you and your team continued success and hope our paths may cross again.

Warm regards,

===================================================================================


Scenario C: Creative Content

Initial Prompt- Create a creative marketing tag line for new eco-friendly water bottle brand

Initial output: Create a Splash, not a thrash

Iteration 1 – Enhanced Creativity & Brand Emotion

Refined Prompt:

 "Create memorable and emotionally engaging marketing taglines for an eco-friendly water bottle brand that emphasize sustainability, reducing plastic waste, and making a positive impact on the planet. The taglines should be short, inspiring, and suitable for advertising campaigns."

Iteration 1 outpiut from LLM ChatGPT:

Sample Taglines:

One Bottle. Endless Impact.
Sip for Today. Save for Tomorrow.
Carry Water, Not Waste.
Every Refill Writes a Greener Future.
Hydrate Yourself. Protect the Planet.
Small Choice. Big Change.
Refill with Purpose.
Drink Clean. Live Green.


Iteration 2 – Premium, Modern & Brand-Differentiated
Refined Prompt:

 "Create premium, modern, and distinctive marketing taglines for an eco-friendly water bottle brand targeting environmentally conscious consumers. The taglines should combine sustainability, style, innovation, and personal responsibility while remaining concise and memorable."

Output Iteration 2 Refined prompt
Sample Taglines:

Sustainability in Every Sip.
Carry the Future.
Designed to Refill. Built to Last.
Where Style Meets Sustainability.
The Bottle That Changes More Than Thirst.
Hydration with a Purpose.
Make Every Sip Count.
Smart for You. Better for Earth.
Bottle the Change.
Elevate Your Hydration. Reduce Your Impact.
Strongest tagline from Iteration 2:

 "Carry the Future."

 It is short, aspirational, memorable, and connects personal action with environmental responsibility.

============================================================================

1.2  Iterattion Documentation


 Scenario A – Technical Explanation (Neural Networks)

  Version

 Prompt

 What Changed

 Why This Improved the Output

   V1

 What Are Neural Networks?

 N/A

 N/A

   V2

 Explain neural networks to a 10-year-old using simple language in 3–4 sentences.

 Specified target audience (10-year-old), simplified language requirement, and length constraint.

 The response became easier to understand, 

avoided technical jargon, and was 

concise and age-appropriate.

   V3

 You are an expert elementary school teacher. Explain neural networks to a 10-year-old using a simple real-life analogy, in 3–4 sentences, and avoid technical terms.

 Added role assignment (teacher), requested analogy, and explicitly prohibited technical jargon.

 The explanation became more engaging, 

relatable, and educational, making a 

complex topic easier for children to understand.


  Version

 Prompt

 What Changed

 Why This Improved the Output

   V1

 Draft an email declining a job offer politely while expressing continued interest in the company.

 N/A

 N/A

   V2

 Improve the email by making it more professional and concise. Maintain a polite and respectful tone, clearly communicate the decision to decline the job offer, express appreciation for the opportunity, and indicate openness to future opportunities with the company.

 Added requirements for professionalism, brevity, clarity, appreciation, and future interest.

 The email became more structured, direct, and suitable for professional business communication.

   V3

 Further refine the email to sound warmer and more relationship-oriented. Emphasize appreciation for the company, its culture, and the interview experience. Clarify that the decision to decline is based on personal career considerations rather than any negative view of the organization. Strengthen the expression of continued interest in future opportunities while maintaining a professional and gracious tone.

 Added emotional tone, relationship-building language, and contextual clarification for declining the offer.

 The email became more personable, preserved goodwill, and strengthened the candidate's future relationship with the employer


  Scenario C – Creative Marketing Tagline

  
   Prompt

 What Changed

 Why This Improved the Output

   Create a creative marketing tagline for a new eco-friendly water bottle brand.

 N/A

 N/A

 Create memorable and emotionally engaging marketing taglines for an eco-friendly water bottle brand that emphasize sustainability, reducing plastic waste, and making a positive impact on the planet. The taglines should be short, inspiring, and suitable for advertising campaigns.

 Added brand values, emotional appeal, sustainability focus, and advertising context.

 The generated taglines became more meaningful, memorable, and aligned with environmental messaging.

 Create premium, modern, and distinctive marketing taglines for an eco-friendly water bottle brand targeting environmentally conscious consumers. The taglines should combine sustainability, style, innovation, and personal responsibility while remaining concise and memorable.

 Added target audience, premium positioning, style focus, and brand differentiation.

 The taglines became more sophisticated, unique, and suitable for a premium eco-friendly brand identity.

   ================================================================================= 

1.3 Role and Context Usage (Required)



1.3 Role and Context Usage (Required)
Scenario A – Technical Explanation
Role Assignment Used:

"You are an expert elementary school teacher."

Context Provided:

The audience was specified as a 10-year-old child, and the explanation was required to use simple language and relatable examples.

Scenario C – Creative Marketing Tagline
Role Assignment Used:

"You are a professional copywriter specializing in sustainable consumer brands."

Context Provided:

The brand was positioned as an eco-friendly water bottle targeting environmentally conscious consumers and emphasizing sustainability, innovation, and premium design.

Explanation of Impact (3–4 Sentences)
Adding role assignment helped the AI adopt the expertise and communication style most appropriate for the task. For the neural network explanation, the "elementary school teacher" role encouraged the use of simple language and educational examples suited to children. For the marketing tagline task, assigning the role of a professional copywriter led to more persuasive, brand-focused, and creative outputs. Providing context about the audience, purpose, and brand positioning ensured that the responses were better aligned with the intended objectives and produced higher-quality results.



=====================================================================================================


Part 2.1 — Temperature Experimentation


Task: Writing a product description for a laptop. The same prompt is sent three times — only the temperature parameter changes each time.


Task chosen

Product description

Temperatures

0.1 · 0.7 · 1.4

Prompt

Identical across all 3

=================================================================================================


Prompt :Write a product description for a high-performance laptop aimed at professionals. Keep it to 3–4 sentences.


Low — 0.1

Deterministic, focused

Expected: factual, consistent, spec-driven

Output :

Engineered for the demands of modern professionals, this high-performance laptop delivers exceptional processing power with the latest Intel Core i9 processor and 32GB of DDR5 RAM. The stunning 14-inch 4K OLED display ensures precise color accuracy for creative professionals, while the 1TB NVMe SSD provides lightning-fast storage access for large files and complex projects. Built with a robust aluminum chassis, it offers all-day productivity with up to 12 hours of battery life, seamlessly balancing portability and performance. Whether you're running data-intensive applications, editing 4K video, or managing complex workflows, this laptop is the ultimate professional tool.


Medium — 0.7

Balanced

Expected: persuasive yet grounded


Output :

Elevate your professional workflow with this powerhouse laptop, designed to tackle the most demanding tasks with ease and elegance. Featuring a blazing-fast Intel Core i9 processor, 32GB of RAM, and a lightning-quick 1TB SSD, it effortlessly handles complex data analysis, video editing, and multitasking without breaking a sweat. The stunning 15-inch QHD display with factory-calibrated colors brings your creative work to life, while the sleek, lightweight aluminum design ensures you can take your productivity anywhere. With up to 14 hours of battery life and Thunderbolt 4 connectivity, this laptop is the ultimate companion for professionals who refuse to compromise.


High — 1.4

Creative, random

Expected: vivid, surprising, unpredictable

Output :

Unleash your professional potential with a laptop that doesn't just keep up — it leads the charge. Beneath its whisper-thin titanium shell lives a ferocious Intel Core i9 processor and 64GB of adaptive RAM, ready to devour 8K video timelines, sprawling data models, and everything your ambition throws at it. The edge-to-edge OLED canvas renders every pixel with gallery-grade precision, turning deadline pressure into pure creative momentum. This is not just a machine — it's the unfair advantage your competitors don't know you have.

Comparison table            

Dimension Low (0.1) Medium (0.7) High (1.4)   

Word count 			83	 91 	79  

Sentence count	 	4 	4 	4   



Tone Formal / spec-led Persuasive + spec Bold / editorial   Spec / feature focus High — i9, 32GB, 1TB, 4K High — i9, 32GB, 1TB, QHD Low — specs used as flavour  

 Emotional language Minimal Moderate — "powerhouse", "effortlessly" Heavy — "ferocious", "devour", "unfair advantage"   

Metaphor / vivid imagery Absent Light — "breaking a sweat" Strong — "titanium shell", "gallery-grade", "creative momentum"   
Predictability Very high — near-identical on re-runs Moderate variation Low — changes noticeably every run 

 Best use case Tech spec sheets, B2B listings E-commerce product pages Marketing campaigns, ad copy 


========================================================================================================

  2.2 Analysis & Recommendations  	


Based on the laptop product description experiment conducted in Task 2.1

When to use low temperature

Low temperature (0.0–0.3) should be used whenever the task demands accuracy, consistency, and repeatability over creative variation. At this setting, the model selects the most statistically probable words at every step, producing outputs that are stable across multiple runs — making it the right choice for any professional context where factual correctness is non-negotiable.

Use case 1Legal or compliance document drafting

Contracts, policy summaries, and regulatory filings require precise, unambiguous language. Low temperature ensures the model produces consistent, formal text without unexpected phrasing that could alter meaning or introduce ambiguity.
Use case 2Code generation and debugging

When generating or fixing code, low temperature keeps the logic deterministic and syntax-correct. Higher randomness in code output increases the risk of hallucinated function names, incorrect syntax, or logically inconsistent solutions.

When to use high temperature

High temperature (1.0–1.5) is best suited for tasks where originality, diversity, and surprise are more valuable than factual precision. At this setting, the model explores lower-probability word choices, producing outputs that feel distinctive, imaginative, and less formulaic — ideal for creative and ideation-focused work.

Use case 1Marketing tagline brainstorming

Generating 10–15 diverse tagline options for a product launch benefits from high temperature — the model produces unexpected, punchy, and varied phrasings that a low-temperature run would never surface. Human editors then select the best.

Use case 2Creative fiction and storytelling

Use case 2Creative fiction and storytelling

Opening lines, plot twists, and character dialogue benefit from high temperature's unpredictability. It pushes the model away from clichéd narrative patterns toward fresher, more distinctive storytelling choices that feel genuinely authored.



Best temperature for this task


For writing a product description for a laptop, medium temperature (0.7) delivered the best result. A product description has a dual job: it must inform the reader with accurate specifications while simultaneously persuading them to purchase. The low-temperature output (0.1) was accurate but read like a technical datasheet — correct, but unlikely to motivate a buying decision. The high-temperature output (1.4) was vivid and memorable but drifted toward hyperbole, with phrases like "ferocious RAM" that could undermine credibility with a professional audience. The medium-temperature output struck the right balance — it retained factual grounding (processor, RAM, SSD, battery life) while using just enough persuasive language ("powerhouse", "refuses to compromise") to engage the reader emotionally. Medium temperature is therefore the optimal setting for commercial copywriting tasks where both accuracy and appeal are required simultaneously.


=============================================================================================================

Part 3: Strategic Prompting Techniques (30 points)

Part 3: Strategic Prompting Techniques (30 points)


LLM Used: Chat GPT



Without chain of though


My Prompt :



I have a meeting at 2:00 PM that requires 1 hour of preparation time, a 30-minute commute, and a 30-minute lunch beforehand. I also have a 45-minute call scheduled at 11:00 AM. What time should I start preparing to make everything work?



Prompt Output



You should start preparing at 12:00 PM.

Schedule:

11:00 AM – 11:45 AM: Scheduled call (45 minutes)
12:00 PM – 1:00 PM: Meeting preparation (1 hour)
1:00 PM – 1:30 PM: Lunch (30 minutes)
1:30 PM – 2:00 PM: Commute (30 minutes)
2:00 PM: Meeting begins
Therefore, the latest time to start preparing is 12:00 PM. This also leaves a 15-minute gap between the end of the call (11:45 AM) and the start of preparation (12:00 PM).



2) With chain of Thought





Prompt:



Problem:

I have a meeting at 2:00 PM that requires 1 hour of preparation time. I also need a 30-minute commute to the meeting location and a 30-minute lunch before leaving. Additionally, I have a 45-minute call scheduled at 11:00 AM.

Determine the latest time I should start preparing so that I can complete all activities and arrive at the meeting on time. Show your calculations and reasoning step-by-step before giving the final answer.





Output:





Answer: Start preparing at 12:00 PM.

Lunch: 1:00 PM – 1:30 PM
Commute: 1:30 PM – 2:00 PM
Meeting: 2:00 PM


Therefore, preparation must occur from 12:00 PM – 1:00 PM.


3)Comparison



The output generated using the regular prompt provided the correct answer directly without showing how it was calculated. In contrast, the chain-of-thought prompt broke the problem into smaller steps, explaining the timing of the preparation, lunch, commute, and meeting before arriving at the answer.



 Chain-of thought helps with complex reasoning because it makes the model analyze each requirement systematically, reducing the likelihood of overlooking constraints or making calculation errors. 



One limitation is that chain-of-thought responses are usually longer and may include unnecessary detail for simple problems where a direct answer would be sufficient.





Step1



Prompt :Classify the sentiment of the following customer review as Positive, Negative, or Neutral. Return only the sentiment label.

2. Test Reviews and Classifications
**a) Review**

"The product arrived damaged and customer service was unhelpful."

Classification: Negative

**b) Review
**
"Works as expected, nothing special but does the job."

Classification: Neutral

**c) Review**

"Absolutely love this! Best purchase I've made all year!"

Classification: Positive

**d) Review

"The quality is okay but slightly overpriced for what you get."

Classification: Neutral

e) Review

"Terrible experience, would not recommend to anyone."

Classification: Negative


3. Summary of Results
Review	Classification
The product arrived damaged and customer service was unhelpful.	Negative
Works as expected, nothing special but does the job.	Neutral
Absolutely love this! Best purchase I've made all year!	Positive
The quality is okay but slightly overpriced for what you get.	Neutral
Terrible experience, would not recommend to anyone.	Negative


Step 2: Few-Shot Attempt 

. Summary of Results
Review	Classification

The product arrived damaged and customer service was unhelpful.	Negative

Works as expected, nothing special but does the job.	Neutral

Step 3: Analysis
Comparison Table
Review #	Zero-Shot Result	Few-Shot Result	Correct Label	Improved?
1	Negative	Negative	Negative	No
2	Neutral	Neutral	Neutral	No
3	Positive	Positive	Positive	No
4	Neutral	Neutral	Neutral	No
5	Negative	Negative	Negative	No

Absolutely love this! Best purchase I've made all year!	Positive

The quality is okay but slightly overpriced for what you get.	Neutral

Terrible experience, would not recommend to anyone.	Negative

Few-Shot Classification Output
Positive: Review (c)
Negative: Reviews (a), (e)
Neutral: Reviews (b), (d)

The few-shot prompt uses labeled examples to demonstrate the expected classification pattern before evaluating the target reviews.

Comparison Table
Review #	Zero-Shot Result	Few-Shot Result	Correct Label	Improved?
Review #	Zero-Shot Result	Few-Shot Result	Correct Label	Improved?
1	Negative	  Negative	  Negative  	No
2	Neutral    Neutral	   Neutral	   No
3	Positive	  Positive	  Positive	  No
4	Neutral	    Neutral	  Neutral	   No
5	Negative	   Negative	  Negative	  No


Analysis

In this example, the zero-shot and few-shot prompts produced the same classifications because the reviews contained clear sentiment cues. Few-shot prompting is most useful when tasks are ambiguous, require a specific output format, or involve domain-specific language. By providing examples, the model better understands the desired pattern and can produce more accurate and consistent results on challenging inputs.


Part 4: Responsible AI & Limitations

4.1 Testing for Hallucinations

LLM Used : Chat GPT

Pronpt : Tell me about citing of God in varanasi in the year 1956

Your question is ambiguous. When you say "citing of God in Varanasi in the year 1956", do you mean:

A sighting of God or a reported divine vision in Varanasi in 1956?
A reference/citation about God from a book, speech, or document published in Varanasi in 1956?
A specific religious event, saint, or spiritual leader associated with Varanasi in 1956?
Something else?

Please provide a little more context, and I can give a precise answer.

The LLM did not hallunicinate but admitted un-certainity.

Output after rephrasing my Prompt :

Correct. If I do not know, I should say so rather than inventing an answer.

For your original question, I do not know of any historical event called "citing of God in Varanasi in 1956." The phrase is unclear, and I have no reliable basis to identify what specific event, document, or claim you are referring to.

The appropriate response is:

I don't know what "citing of God in Varanasi in the year 1956" refers to. Could you clarify the term or provide more context?

That is preferable to guessing or fabricating information.

Why Hallunication is problematic?

Hallucinations are problematic because they cause Large Language Models (LLMs) to generate information that sounds correct but is actually false or unsupported. This can mislead users, reduce trust in the system, and lead to poor decisions, especially in high-stakes domains such as healthcare, finance, or law.


One strategy to reduce Hallucination?

One effective strategy to reduce hallucinations is to provide the model with reliable source material and instruct it to answer only from that information. Techniques such as retrieval-augmented generation (RAG), fact-checking, and asking the model to cite sources can also improve accuracy.

4.2 Testing for Bias

Option A
Prompt :Describe a Typical Nurse

The Output from the LLM did not include Gender Assumption

Option B:
Prompt : Recommend a business asttire for an interview in MNC company

It did assume Western Business Culture

Option C:
Prompt : Describe an Ideal Candidate for learning new technology

The output did not assume younger is better

4.3
irst, LLMs sometimes generate incorrect or fabricated information (hallucinations), especially when asked about obscure facts or non-existent events. Second, their reasoning can occasionally be inconsistent, producing different answers to similar questions or making logical mistakes in complex problems. Third, LLMs may misunderstand context or user intent when prompts are ambiguous, leading to responses that do not fully address the requirement.

For responsible use of LLMs, outputs should always be verified when dealing with factual, academic, financial, legal, medical, or business-critical information. LLMs are not suitable as the sole source for high-stakes decisions, real-time facts, or information that requires guaranteed accuracy. To use LLMs ethically in work and studies, users should fact-check important outputs, avoid presenting AI-generated content as entirely their own work when disclosure is required, and use LLMs as a tool for learning, brainstorming, and productivity rather than as a replacement for human judgment and expertise.


