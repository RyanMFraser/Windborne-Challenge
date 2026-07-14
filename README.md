# Windborne-Challenge

## 1. Role
I am most interested in the General Role, followed by the Applied Research role, and finally the Evaluation Role.

## 2. ML Idea I was Excited About
An idea I was excited about was a model that would track certain movements in sports, and predict what kind of action was performed. I am an avid snowboarder, and was inspired by how players in snowboarding video games could earn points by doing tricks. I wanted to create a model that could take in positional/motion data, and predict if a trick was performed, such as a 180, and then award points in an app. Players would then be able to use their points for in app items/ leaderboards. I bought a few sensors, and mounted them to an esp32, and started collecting data, with an initial plan to use a logistic regression model over a sliding window of signal to see if a trick had been performed and classify it accordingly as a POC, and possibly upgrading the a more complex neural network. Ultimately I stopped this project as I decided the business part was not as valuable. As a boarder I realized I don't really care about how many tricks I do, just how many I can do. I also didn't think that virtual rewards were motivating, and that sponsored rewards were too easy to cheat in. I also ran into a few issues with my sensors and data collection. I only know so many tricks, and can only do so many when I go boarding so I had limited data to work with. Paired with the loss of business value, I decided to stop the project.

## 3. Took Initiative

One time I took initiative is actually in my current role at RBC Borealis as a machine learning software engineer. My team is currently undergoing some changes, and all of our researchers were moved over to different products. I am very interested in the research side of our product and didn’t want to see it stagnate, so I volunteered to take on the responsibilities of the researchers. I was driven to do this by two key factors. The first is that being a research engineer is my goal position. For me it is a great blend of software and actual modeling. By taking on the extra responsibility I am proving to my peers that I can handle myself in such a role. The second reason is that it is what the team needed. With such a loss of personnel, someone needed to step up to help keep the ship afloat. I saw that it was the perfect opportunity to show my value and do something meaningful. As far as company value, I have corrected several data quality issues, and contributed to our model risk documents where they were approved, ultimately making a better product for our users.

## 4. Problem With Accuracy 

A simple example I could think of is suppose we are in a location where it seldom rains, and is just sunny most of the year, a class imbalance kind of problem. We could get a good accuracy by just predicting the weather will be sunny all the time, but we miss out on what we wanted to predict being the rain. A much better metric would be sensitivity, that is tracking the number of true positives (rain days) we catch. It may be the case that incorrectly predicting a rainy day is impactful to this community (maybe rain causes flooding) so we would want to be certain we are good at capturing rain, even at the expense of accuracy.

## 5. Changed LLM Use

A time that I changed how I used LLM’s was during the transition from my first data science internship to my internship at RBC Amplify. At the time I was still very new to using LLM’s and was attempting to use them on tasks such as text-sql for my company, as well as coding tasks, and creating projects. At the time they seemed like all knowing partners, and I would write prompts instructing the model to do several things all in one call. In terms of text-to-sql, I was having the model take in all of the context and try to produce the query in one go. I found the model was getting stuck at various stages of the process, from query type, to table selection, all the way to end formatting. I decided to change the way I worked by not treating the LLM like a SME, and rather like a five year old. I made my prompts simple and very specific. I also made sure that I broke up prompts, one task per prompt, similar to a good object oriented design. Ultimately this ended up working much better on my text-to-sql task, and even made the code the model produced come out more readable and expandable. 

## 6. ML Twitter

I am not on Twitter, but in a similar sense I follow ThreeBlueOneBrown on youtube. He is not ML specific, but I have been drawn to the stunning visualizations he has created, and really enjoyed his series on deep learning and language models.





