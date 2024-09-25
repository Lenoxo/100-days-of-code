# 100 Days Of Code - Log

<!--
## Examples section

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)

### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)
 -->

## Actual diary - Organized from newer to older dates, like a Stack

<img width="190px" src="https://ih1.redbubble.net/image.1438467887.4273/flat,750x,075,f-pad,750x1000,f8f8f8.u2.jpg">

### Day 96, September 24, 2024

**Today's Progress:**

1. **Practicing with personal projects**: In Mk-dashboard:

- Today I had time to add a very basic aside that right now looks more like a nav, and also added the `/profile` page, with a basic component and route handling using `react-router-dom`

2. **Learning Design Patters**: I had a bit of time to read about the Prototype pattern, I hope to implement it with a small example / challenge to practice it.

Links to the repos used:

[Mk-dashboard current issue](https://github.com/Lenoxo/mk-dashboard/issues/24)

**Thoughts**: One thing I would like to change tomorrow for Mk-dashboard is replacing the current nav tag in TopBar for a header one, because I'll be using a sidebar later on, and I consider that using the nav tag for this last one is more logic / readable.

Also, I finished the Array / ArrayLists reviewing of yesterday, and also saw the Nerdearla event virtually, it had fun things.

### Day 95, September 23, 2024

**Today's Progress:**

1. **Practicing with personal projects**:

- Today I had time to add the image rendering for the characters images in NewFightForm, also, planned what to do next regarding on `/profile` endpoint.

- Also, I tried to make a practice with Arrays / ArrayBuffers with an example I asked to ChatGPT but I'm still trying to solve it while I'm writing this.

Links to the repos used:

[Mk-dashboard current issue](https://github.com/Lenoxo/mk-dashboard/issues/23)

**Thoughts**: Well, this is a thing that takes some time to me for now, trying to work with arrays in JS when you're messing around with the offset and encoding between UTF-8 and UTF-16

### Day 94, September 22, 2024

**Today's Progress:**

1. **Practicing with personal projects**:

- Today I had time to replace the inputs type text with selects that dynamically render the options depending on the existing `charactersData` and `profileData.rivals` states.

- Also, I added a basic style for the form, later on, I'd like to add it glassmorphism.

Links to the repos used:

[Mk-dashboard current issue](https://github.com/Lenoxo/mk-dashboard/issues/19)

**Thoughts**: Today I remembered a bit of why I don't like to write plain CSS, I'm not a person that makes greats designs, but I can manage to write some decent CSS with enough time.

### Day 93, September 21, 2024

**Today's Progress:**

1. **Practicing with personal projects**:

- Today I had time to add the basic functionality for adding a new fight data, with type safety, and planned what to do next for tomorrow.

Links to the repos used:

[Mk-dashboard link](https://github.com/Lenoxo/mk-dashboard)

**Thoughts**: Today I spent some time of the afternoon and evening with my family, so I didn't have time to practice with Arrays and ArrayLists, but I hope that for the Monday I'll have a bit more time.

For the meantime, I would like to focus on the importance of disconnecting and doing something else, to have your brain in the diffuse thinking mode, that incentivizes neuroplasticity and also consolidation for learning.

### Day 92, September 20, 2024

**Today's Progress:**

1. **Practicing with personal projects**:

- Today I had time to add type safety, fix some things I made wrong using BEM CSS architecture, and start working with the addFight functionality.

- It is a WIP for now, and I managed to add the Modal with a very basic form without styles.

- All these things were made in Mk-dashboard

2. **Learning Data Structures and Algorithms**: As I said the day before yesterday, I'll be trying to improve more with my DSA proficiency, so I did some recall about Linked Lists, Queues and Stacks, what they are and how to use them.

Links to the repos used:

[Mk-dashboard current issue](https://github.com/Lenoxo/mk-dashboard/issues/15)

**Thoughts**: It was a day with it's highs and lows, but overall, I'm happy with the progress.

### Day 91, September 19, 2024

**Today's Progress:**

1. **Practicing with personal projects**: I did some advancements in Mk-dashboard, changing the dummy data hardcoded in the FightResult component to a dynamically written one.

For now, I use `profileData.history.map` to create a new FightResult component, and pass by props the current fight data and the characters images.

Links to the repos used:

[Mk-dashboard current issue](https://github.com/Lenoxo/mk-dashboard/issues/9)

**Thoughts**: Today I only had 1 hour to practice and write this diary, but tomorrow I hope to have some more.

### Day 90, September 18, 2024

**Today's Progress:**

1. **Practicing with personal projects**: I did some advancements in Mk-dashboard, adding three main states and two derivated ones:

- profileData: That saves the player's nickname, imageUrl, rivals list, and history of fights.
- currentDayFights: For now is empty, but I plan to make a filter based on `profileData.history` array to show only the fights that happened in the current day.
- charactersData: It's an array of objects, and each object has a name and imageUrl, for showing the character of MK. For now, it has subzero and skorpion.

And the two derivated are:
victoryCounter and defeatCounter, and I make the counting using a `.forEach` in `profileData.history` and show the dynamic data in TopBar, passed using props.

Links to the repos used:

[Mk-dashboard current issue](https://github.com/Lenoxo/mk-dashboard/issues/2)

**Thoughts**: Today I had a bit of lazyness, but not too much to be worried about. And also, I continued in the AWS course I talked yesterday but noticed that I need to register a credit card in order to complete the profile creation. And because I'm currently doing job hunting for the first job, it's not worth adding it in my opinion, so I'll be focusing in other abilities like practicing more DSA and learning about testing / github actions for CI / CD.

### Day 89, September 17, 2024

**Today's Progress:**

1. **Learning Design Patterns and More**: I've practiced more with the Builder pattern, now I added a Director class, and another Builder class, for empanadas. And finally completely understood the concept to the point where I'm comfortable with it.

Also, I started the AWS Cloud Practitioner Fundamentals course in w3schools, for now, I learned that their key value is that you only pay for what you use, and AWS EC2 means AWS Elastic Cloud Compute. Talking about the virtual server, it's easy to upgrade and downgrade.

Links to the repos used:

1. [HTML-CSS-JS-Challenges](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/challenges-in-process)

**Thoughts**: It has been a good day. I just had an hour and a half to practice programming, but I'm happy with the progress.

### Day 88, September 16, 2024

**Today's Progress:**

I will resume what are my current advancements from the last day, talking about what I did during the intermittency time:

1. **Learning Design Patterns**: I've learned and practiced a bit with the Singleton pattern, but I still don't know how to write a simple enough example of it in Typescript. And also, I've practiced with the Builder pattern as I said yesterday.

2. **Practicing with personal projects**:

- I did some advancements in Mk-dashboard, at least I have a reference UI coded, with the TopBar, FightResult and AddFight components added with dummy data.

- I updated the render DB for DevShop again, and now that I notice, I have to do it again today...

- I experienced a bit writing C++ code, but decided to focus first on the least amount of technologies that give me the highest possibilty to get my first job.

  - That is, focus in AWS, and CI / CD pipelines with Github Actions and tools like Jenkins, and also, testing, but that one I'm not sure what to pick.
  - I talk about these because on my own research of the job market here in Colombia, the companies ask for these technologies, and also Java.

- I did some reviewing on my Node.js fundamentals, like working with streams and buffers, differences between using callbacks, async / await and promises, what is the Event Loop and how it works, and modules that come with Node.js to make your life easier when working with files, reading OS data, invoking new processes, and debugging.

Links to the repos used:

1. [HTML-CSS-JS-Challenges](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/challenges-in-process)
2. [Mk-dashboard current issue](https://github.com/Lenoxo/mk-dashboard/issues/1)
3. [node-fundamentos](https://github.com/Lenoxo/node-fundamentos)

**Thoughts**: Uff, that was a lot of writing in one go, my hands are tired, so I'll do the updates to have DevShop working and start my night cycle.

And today I didn't advance in my programming projects because I spen't almost and hour doing some programming things related to job hunting.

### Day 87, September 15, 2024

**Today's Progress:**

- **Learning Design Patters** Today I learned about the Builder pattern, and made a small working example using JS.

The example uses a Pizza class, a PizzaBuilder class and the client code to showcase how to use the design pattern.

It is at `src/TS-challenges/patrones-de-diseño/builder.js`

Links to the repos used:

1. [HTML-CSS-JS-Challenges](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/challenges-in-process)

**Thoughts**: During the last couple of weeks a lot of things happened, the internet service was down, problems with the PC and mainly intermittency with my consistency doing the challenge.

So, In order to be honest with the advancements I've made, in tomorrow's diary, I'll be wrapping up what I've done during that intermittency time.

### Day 86, August 18, 2024

**Today's Progress:**

- **Practicing with Personal Projects:** Today I advanced with Mk Project, adding the basic style with dummy data to the TopBar component in the main page.

Links to the repos used:

1. [mk-dashboard](https://github.com/Lenoxo/mk-dashboard)

**Thoughts**: I had just an hour to practice today but I'm glad I did it, and I've been with my family so there is no real problem with having less time to practice, the important thing is to advance everyday.

PD: I'm almost recovered of the flu I had, hope I'm fully recovered tomorrow.

### Day 85, August 16, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** I did some maintenance to my project DevShop, updating the db connected to a new one because with the free render plan every 30 days the db gets suspended, so I have to create a new one from render dashboard.

Links to the repos used:

1. [DevShop API](https://github.com/Lenoxo/DevShop)

**Thoughts**: Well, almost a month since the last time I wrote this diary, and mainly this part have been read only by me, so, I'd like to tell for future reference a bit of details explaining the absence; In the first week I left mainly because familiar circumstances just occurred, in the second one, I didn't prioritize the code practice at all and that's my fault, and lastly, these last couple of weeks I've been sick with a relatively heavy flu, I'm recovering now and with all the time I had thinking in bed while sick I have an idea to change my approach not only to this challenge, but other aspects in my life, to be more honest with the things I like to do, and disconnect of all the other stuff that doesn't help me to make my life and the people around me better.

PD: The fingers feel weird after not writing at this pace for a while, but I hope it stops soon :).

### Day 84, July 18, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I had time to practice updating the documentation and trying to resolve a bug I had while updating my DevsShop API project.

Well, the problem is better explained in the [issue 6](https://github.com/Lenoxo/DevShop/issues/10) of the project, but briefly what happened is this:

1. I wanted to make a better documentation for the first steps when using the API, because it took me a while to remember how to work with it.
2. So, I updated the documentation and decided to merge it with another change I considered relevant, to make the environment variables names simpler in the project.

3. Then, I changed them and made a PR and merge it, but when I noticed in the API logs from Render, the error of sequelizecli came back.

4. This time, I decided to search for this particular error, and finally found the reason why it was happening in the first place;
   The sequelize config requires to define the explicit names used as values in `NODE_ENV` as cases to use one or other connection config to connect to the database.

And when there are inconsistencies in the names used, the cli throws that error.

In order to solve it, you have to make sure that you use the same name for both sequelize config returned json and your environment variable `NODE_ENV` value.

Links to the repos used:

1. [DevShop API](https://github.com/Lenoxo/DevShop)

**Thoughts**: Looking back, it was a silly mistake, but I suppose that from time to time everyone has these kind of mistakes, the most important thing is to not repeat it, and, as someone I appreciate says: "Al mal tiempo, buena cara".

### Day 83, July 17, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I had time to practice trying to resolve a bug I had while updating my DevsShop API project.

Well, the problem is better explained in the [issue 6](https://github.com/Lenoxo/DevShop/issues/10) of the project, but briefly what happened is that I tried to replicate the issue in my local environment using docker containers for the db, and managed to solve it by changing the value of `NODE_ENV='production'`

Links to the repos used:

1. [DevShop API](https://github.com/Lenoxo/DevShop)

**Thoughts**: I still can't get it why this was happening, and also, had to clear several times the data of the db locally to ensure that it was an error with the environment variables.

### Day 82, July 16, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I had time to practice trying to resolve a bug I had while updating my DevsShop API project.

Well, the problem is better explained in the [issue 6](https://github.com/Lenoxo/DevShop/issues/10) of the project, but briefly what happened is that I noticed that the deploys made in Render were using the development environment rather than the URI connection to the internal database with Render.

So I decided to update the `NODE_ENV='prod'` variable in my settings, and then had an error with sequelizecli telling that the dialect has to be explicitly supplied, and after hours of trial and error, and messing around with the environment variables, I had another error.

Links to the repos used:

1. [DevShop API](https://github.com/Lenoxo/DevShop)

**Thoughts**: Currently I can't solve the problem, but maybe tomorrow I'll be able to make it.

### Day 81, June 8, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I had time to practice with my first steps learning about the singleton pattern, and trying to write an example to use it from scratch

**Thoughts**: Today I almost had no time to practice, but hopefully in the upcoming days I'll have more time to dedicate to it.

### Day 80, June 7, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I had time to advance creating the MVP, organizing how I will start developing the base features and styling some components inf index.tsx in mk-dashboard:

- It took me a bit more time than expected, because first I wanted to implement BEM in the react project, but then realized that I could use CSS modules within each component, that would be easier.

**Thoughts**: While developing this project, I look forward to implement Trunk-Based development, but I consider if I want to follow it, I have to divide the upcoming project parts into smaller chunks, because the first one I created was a bit to large to effectively apply it.

### Day 79, June 4, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I had time to learn about Trunk-Based development:

- It is a simplified Git workflow that ensures a rapid pace of development, while using CI/CD pipelines for testing small changes

- It's compared to Gitflow which has long living branches with bigger changes between them, and Trunk-Based, which has the main / trunk branch with short living branches constantly merging changes.

- This approach facilitates code reviews, avoiding cognitive overload thanks to the smaller changes getting merged. With automated testing, the code meets some specifications, and the reviewers / team focus can be driven to optimizations.

- And is the standard method used for highly effective teams.

- Also, I updated some of my projects, removing the inactive branches, following this workflow.

**Thoughts**: For me, this workflow is curious, because I was implicitly applying some of the best practices it recommends, but thanks to today's learning, I noticed that I have a lot to improve in the CI/CD integration and managing the testing.

### Day 78, June 3, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I had time to practice adding the first wiki page and organizing the first steps and initial commit to develop a new project for a relative of mine:

- The project for now is called `mk-dashboard`, and focus on creating a new way to view the rounds in a local match of Mortal Kombat.

- Adding a way to quickly register played matches and show them in a stylish way from the phone, I have a brief idea on how to develop the first page.

- Also, I think it could be great to have custom profile photos and a design with glass morphism.

Links to the repos used:

1. [mk-dashboard](https://github.com/Lenoxo/mk-dashboard/wiki)

**Thoughts**: My idea for the upcoming days is to practice interleaving this project (more focused on the frontend) and upgrading several of my backend projects, learning about trunk-based development, testing and Jenkins applied in those repos.

### Day 77, June 1, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I had time to practice solving a bug in Reactify-Dashboard project:

- This bug has to deal with the way the image url data comes from the Platzi Fake Store API. Because the students sometimes change the data format and causes errors when trying to parse the data in the app.

- That is out of my control, but what I can control is handle the wrong format for the data, and hopefully, parse it to prevent the error.

- That's what I did today, using regex, and `.replace()`.

- More details in the related issue: [Link](https://github.com/Lenoxo/Reactify-Dashboard/issues/5)
- Also, I had the opportunity to improve the configs of the project, excluding `node_modules` and `.next` folder in `jsconfig.json` and updating the `README.md` instructions to make it clear how to use the `.env` variables when you install and run the project locally.

Links to the repos used:

1. [Reactify-Dashboard](https://github.com/Lenoxo/Reactify-Dashboard)

**Thoughts**: Today I had the idea to implement binary search for the product search by name, and later on, after fixing the above bug, I noticed that the idea was not viable, because the products name is unordered, and chaotic, making it a binary search in this case is not practical.

### Day 76, May 31, 2024

**Today's Progress**:

- **Practicing with LeetCode** Today I had time to practice solving the insert sorted index problem from leetcode, and had the opportunity to recall how to use Binary Search:

Links to the repos used:

1. [HTML-CSS-JS-Challenges](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/challenges-in-process)

**Thoughts**: These last 4 days I didn't have time to practice mainly because some personal things occurred, nothing to dangerous thankfully.

And as something to improve for the upcoming days, I have to stick with having a break after an hour of focused work / study, because I spent almost 3 hours trying to solve the problem from above.

### Day 75: May 25, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I had time to add the patientor-back and front project details to my own website, to show them as projects that I worked with:

Links to the repos used:

1. [EmanuelDev](https://github.com/Lenoxo/EmanuelDev)

**Thoughts**: Today I didn't have much time to practice, mainly because I was spending time with my family, that is really important too.

### Day 74: May 24, 2024

**Today's Progress**:

- **Learning Typescript** Today I had time to finish styling all the entry type fields of the patient entries, in patientor repo:

  - It took much more time that expected for me, because my editor lsp was really slow, even when I fixed an eslint problem, it only showed as solved after 7 seconds, same thing with the autosuggestions.
  - And combined with the above, I still have to experiment more with MUI to get the trick.
  - I found a workaround for now, is an issue with nvim lsp performance in version `0.10.0`, and disabling the watcher for file changes seems to solve it, now the lsp reacts (intended pun) as expected (1 to 1.5 seconds after writting the autosuggestions and diagnosis updates)
  - Here is the link for reference: [Reddit Thread](https://www.reddit.com/r/neovim/comments/161tv8l/lsp_has_gotten_very_slow/)
  - Lastly, I managed to add the demo video to the repo too, because the same video I recorded for showing the changes in my last PR also fits for the situation :).

  - Link to the issue related:
    - [Add styles and icons to patientDetail](https://github.com/Lenoxo/patientor/issues/18)

Links to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: I'm not going to stay up late again as I did today, it was an horrible idea, its better to wait to the night when I can have more time, and being Ok with having the things unfinished in the development, its a large process, I don't have to rush it in one night to get everything working, that's a free ticket to punish my health.

### Day 73: May 23, 2024

**Today's Progress**:

- **Learning Typescript** Today I had time to finish styling the Base Entry fields of the patient entries, in patientor repo:

  - It took much more time that expected for me, because my editor lsp was really slow, even when I fixed an eslint problem, it only showed as solved after 7 seconds, same thing with the autosuggestions.
  - And combined with the above, I still have to experiment more with MUI to get the trick.

  - Link to the issue related:
    - [Add styles and icons to patientDetail](https://github.com/Lenoxo/patientor/issues/18)

Links to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: I really want to fix that lag on the editing part, I also used VSCode to discard if it's an nvim lsp problem, but it doesn't work, same thing with replacing named import to default imports for MUI components and icons. Maybe my computer is getting too old to handle these kinds of libraries.

### Day 72: May 22, 2024

**Today's Progress**:

- **Learning Typescript** Today I had time to finish the final exercise 9.29 from Fullstack Open section of Typescript:

  - This exercise has to deal with:

    - Adding to the AddEntry form, the right inputs for each field.
    - As a tip:
      - In the example, for the diagnosisCodes a `multiple select` component from MUI is used. And for dates; `date` input

  - Link to the issue related:
    - [Exercise 9.29](https://github.com/Lenoxo/patientor/issues/15)

Links to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: During the planning session I didn't have any idea of how long would it be to finish this last part, if I refer to my plan it was quite easy, but the implementation, that was the tedious part for me.

I only used Material UI in the patientor project, so I didn't know anything about how they managed the states, all the possible components and the props to personalize them.

Combined with the use of `Day.js`, a library that I discovered today thanks to MUI docs, the implementation of the first DatePicker component took me an hour and half.

And I understand the potential work saved by using these libraries, but it really felt overwhelming managing those details and also the lsp showing the same errors time to time, and the several reboots I had to do to make it work.

I think that what I can improve for the next time is to add an extra time at the beginning of the focus sessions, after the planning, to investigate if there is something I need to apply (with a new library or a way to work I don't know), and see how other people face those challenges.

Lastly, in this night, I'm quite happy, I managed to finish the last part of this project to accomplish my learning of Typescript according to my planning for this challenge, and starting tomorrow, I can fully focus on improving / creating my own projects to apply all these concepts I learned in 72 days of the challenge.

Also, I can focus on practicing my English in Discord and Tandem, so, there are challenging but fun days to come, and lastly, put more effort on my job hunting.

### Day 71: May 20, 2024

**Today's Progress**:

- **Learning Typescript** Today I had time to finish the exercise 9.28 from Fullstack Open section of Typescript:

  - This exercise has to deal with:

    - Adding in the addEntry form, support for all the entry types.
    - The entry types that are missing of support are:
      - OccupationalHealthcare
      - Hospital

  - Link to the issue related:
    - [Exercise 9.28](https://github.com/Lenoxo/patientor/issues/13)

Links to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: Today I had a bit more time to practice, so I learned (actually, relearned) about git rebase, and the main rule to use it, which is `Not rebasing commits that are in the remote branches`

### Day 70: May 19, 2024

**Today's Progress**:

- **Learning Typescript** Today I had time to fix an error that arised in the patientor backend repo

  - The error, or, better said, the errors that were happening are:
    - The backend, didn't add the entry type in the final object of new entry.
    - A weird but reasonable parsing error, that converted `!rating` to `true` when `rating === 0`.

  The details of how I solved this errors are in the related issue:

  - Link to the issue related:
    - [Issue talking about the above errors](https://github.com/Lenoxo/patientor-back/issues/9)

Links to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: I couldn't have much time to make more of the practice because some personal things happened, but at least, I learned how to not validate the non existing values when using numbers in JS.

### Day 69: May 18, 2024

**Today's Progress**:

- **Learning Typescript** Today I had time to fix the linting and formatting of the projects `patientor` and `patientor-back`, and merge the PR of the exercise-9.27 to main branch.

  - Link to the issue related:
    - [Exercise 9.27](https://github.com/Lenoxo/patientor/issues/11)

Links to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: I couldn't have much time to make more of the practice because some personal things happened, but at least, the code is more legible.

### Day 68: May 17, 2024

**Today's Progress**:

- **Learning Typescript** Today I had time to finish the exercise 9.26 from Fullstack Open section of Typescript:

  This exercise has to deal with:

  - Adding a new endpoint in the backend: /api/patients/:id/entries, that receives POST resquests for adding entries related to the patient.
  - Validate that the data received has the correct type, and associate it with the patient.

  Today I advanced adding the data validation for the two missing entry types; OccupationalHealthcare and HospitalEntry

  - Links to the issue related:
    - [Exercise 9.26](https://github.com/Lenoxo/patientor-back/issues/5)

Link to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: It was a long exercise, but finally, I did it, also, I had the chance to recall how to use Pick and Omit in Typescript, and, taking into account what happened yesterday, I did the basic pomodoro for the programming session, and it worked :).

One thing that impressed me is how long the final `utils.ts` file was, 251 lines with today's latest commit, I think that the way I tackled the problem could be better, but it's good enough for now, and frankly, I need to focus on reviewing DSA and Math rather than some specific Typescript use.

### Day 67: May 16, 2024

**Today's Progress**:

- **Learning Typescript** Today I had time to advance in the exercise 9.26 from Fullstack Open section of Typescript:

  This exercise has to deal with:

  - Adding a new endpoint in the backend: /api/patients/:id/entries, that receives POST resquests for adding entries related to the patient.
  - Validate that the data received has the correct type, and associate it with the patient.

  Today I advanced adding the data validation for the BaseEntry and the HealthCheck entry.

  - Links to the issue related:
    - [Exercise 9.26](https://github.com/Lenoxo/patientor-back/issues/5)

Link to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: Today, mainly because I didn't respect the priorities of the day, and procrastinated, I had poor focus during the last hours of the day, and frankly, I think I should respect more the break times, almost 2 hours coding straight ahead.

### Day 66: May 15, 2024

**Today's Progress**:

- **Learning Typescript** Today I had time to advance in the exercise 9.26 from Fullstack Open section of Typescript:

  This exercise has to deal with:

  - Adding a new endpoint in the backend: /api/patients/:id/entries, that receives POST resquests for adding entries related to the patient.
  - Validate that the data received has the correct type, and associate it with the patient.

  Today I advanced adding the functionality to add entries for a patient, it's working but what's missing is the data validation.

  - Links to the issue related:
    - [Exercise 9.26](https://github.com/Lenoxo/patientor-back/issues/5)

Link to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: I applied the miniframework I told here in the diary yesterday and, it was very good, most of the frustration of not knowing where to start just banished, and I could advance a lot with just 1 hour I had to practice today.

Anyway, I'll see how can I improve it more, or the tools that I use.

### Day 65: May 14, 2024

**Today's Progress**:

- **Learning Typescript** Today I just had time to merge the changes from exercise 9.25 from Fullstack Open section of Typescript:

  This exercise has to deal with:

  - Adding a new component for the entryDetails
  - It has to implement conditional rendering using the switch statement and exhaustive checking of entry.type
  - It should be using MUI Icons to distinguish one entry type of another.

  - Links to the issue related:
    - [Exercise 9.25](https://github.com/Lenoxo/patientor/issues/7)

Link to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: I had less time to practice, and with all the distractions I can't handle for now, I tried to think how can I improve my approach to solve problems, and something came to my mind.

Almost always I tried to think in the code and mix it with the logic in my head. Even if I didn't understood the problem well enough. That its really frustrating sometimes, because I go back and forward doing the same thing just changing minor details to make the code work.

But, if I tackle sistematically a problem, its much easier to write the code, so, taking what I learned about problem solving, I would like to use this miniframework to solve problems by myself in programming:

1. **Decomposition of the problem:** focused on the desired results
2. **Pseudocode / logic planning:** focused on the programming logic
3. **Implementing the code:** Writing it the fastest way possible, after it is finished, you can look up how to improve it.

### Day 64: May 11, 2024

**Today's Progress**:

- **Learning Typescript** Today I practiced solving exercise 9.25 from Fullstack Open section of Typescript:

  This exercise has to deal with:

  - Adding a new component for the entryDetails
  - It has to implement conditional rendering using the switch statement and exhaustive checking of entry.type
  - It should be using MUI Icons to distinguish one entry type of another.

  - Links to the issue related:
    - [Exercise 9.25](https://github.com/Lenoxo/patientor/issues/7)

Link to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: I had more troubles with my problem solving skills today, it took me about 2.5 hours to solve a simpler problem. Mainly because my first approach was incorrect.

But for the upcoming days I'll be with my family, there are no pc's or devices to code where they live, so... I'll have to leave it for the Tuesday.

### Day 63: May 10, 2024

**Today's Progress**:

- **Learning Typescript** Today I practiced solving exercise 9.24 from Fullstack Open section of Typescript:

  This exercise has to deal with:

  - Adding in the frontend repo, a state for the diagnoses, fetching them from /api/diagnoses.
  - Using that state to show the name of the diagnosis related to the specific patient diagnose.

  - Links to the issue related:
    - [Exercise 9.24](https://github.com/Lenoxo/patientor/issues/5)

Link to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: Today I had a bit more time to practice, but I felt like I wasn't planning well how to code the solution for the last challenge, so, I'll see more ways to improve my problem solving skills tomorrow, for now, I can rest.

### Day 62: May 9, 2024

**Today's Progress**:

- **Learning Typescript** Today I practiced solving exercise 9.23 from Fullstack Open section of Typescript:

  This exercise has to deal with the patientor frontend repo, adding in the patient page, a section with their entries, showing date, description and diagnosisCode properties dynamically.

  What I did is first, adding the new component of PatientEntry, then, adding the types from the backend repo to the frontend, and lastly, adding some array.map, for the multiple children that PatientDetail (With several patient entries) and PatientEntry (With several diagnosis codes) can have.

  - Links to the issue related:
    - [Exercise 9.23](https://github.com/Lenoxo/patientor/issues/3)

Link to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: Well, today I had to catchup these diary with what happened yesterday, because I had the weirdest bug in Arch Linux. Mainly what happened is that when I went back to a prior snapshot in my btrfs file system, the /boot partition and the root partition had different kernel versions, so, when I rebooted I was dropped to an emergency terminal.

I tried several things, the last resource I could use is reinstalling Arch Linux with a new ISO and copying my previous configs to the fresh system.

And to prevent this issue to happen ever again, I modified the subvolumes used in the root partition, to also detect and recover changes in the /boot and /var partitions.

### Day 61: May 8, 2024

**Today's Progress**:

- **Learning Typescript** Today I practiced solving exercise 9.22 from Fullstack Open section of Typescript:

  This exercise has to deal with:

  - Adding two new types: HospitalEntry and OccupationalHealthcare, while ensuring the data is correctly sent as json for now
  - Currently, the only validation that needs to pass, is that the type is correctly assigned to the data.

  - Links to the issue related:
    - [Exercise 9.22](https://github.com/Lenoxo/patientor-back/issues/3)

Link to the repos used:

1. [patientor-frontend](https://github.com/Lenoxo/patientor)
2. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: Just had enough time to do this little thing before something happened with my linux install... More details in the [May 9 thoughs](#day-62-may-9-2024)

### Day 60: May 7, 2024

**Today's Progress**:

- **Learning Typescript** Today I practiced solving exercise 9.19, 9.20 and 9.21 from Fullstack Open section of Typescript:

  Those exercises were about:

  1. **Exercise 9.19:**
     - Replacing input types from text to the correct ones
       - Date: With input type date
       - Weather and Visibility: With input type radio
       - Comment with input type text
     - Also, it's necessary to have all the app correctly typed, with zero errors in Typescript and ESlint.
     - **Solution** In the exercise 9.17 I did the major part of this challenge, so, I just focused on adding the correct type for the form data and that's that.
  2. **Exercise 9.20:**
     - This was in the patientor-backend repo
     - Adding a new endpoint in the backend: /api/patients/:id; and creating a new type: Entry.
     - The endpoint has to return all the patient data, included the new type, entry, as an array.
       - The array of entries will be empty for now.
  3. **Exercise 9.21:**
     - This was in the patientor (frontend) repo
     - Adding a new page to show the patient data in the frontend. Also, if in the patientList, someone does click the patient, redirect to patient data corresponding to that patient.
     - OPT: Use Material UI if you'd like.

  - Links to the issues related:
    - [Exercise 9.19](https://github.com/Lenoxo/diario-vuelo-Ilari-front/issues/6)
    - [Exercise 9.20](https://github.com/Lenoxo/patientor-back/issues/1)
    - [Exercise 9.21](https://github.com/Lenoxo/patientor/issues/1)

Link to the repos used:

1. [diario-vuelo-Ilari-front](https://github.com/Lenoxo/diario-vuelo-Ilari-front)
2. [patientor-frontend](https://github.com/Lenoxo/patientor)

3. [patientor-backend](https://github.com/Lenoxo/patientor-back)

**Thoughts**: Today I practiced a lot more, but I noticed something, it should be obvious when you see it from outside but, it is very important to rest, every hour of focus followed by a break, I didn't respect that in the later parts of the day, and I really felt the loss of focus and the lack of productivity.

So, as a personal rule, rest after working in programming at the most for an hour.

### Day 59: May 6, 2024

**Today's Progress**:

- **Learning Typescript** Today I practiced solving exercise 9.18 from Fullstack Open section of Typescript:

  This exercise was about:

  - Showing in the frontend if adding the diary entry failed and why (the message error and status code), with a red color.

  I did the corresponding issue tracking in github. And lastly, one thing I had a problem for a while is that I didn't understand well which were the `error.response` object properties, and after a while, I saw the devtools and finally found the correct way to access the status code and error message:

  ```js
  // ...
  export function DiaryForm() {
  const [error, setError] = useState<PostDiaryError>();

  function handleSubmit(event: React.SyntheticEvent) {
    event.preventDefault();
    const form = event.target as HTMLFormElement;

    // ...

    axios
      .post(`${baseUrl}/api/diaries`, { date, visibility, weather, comment })
      .then(() => {
        alert("Added new entry in the diary");
        setError(false);
      })
      .catch((error) => {
        if (axios.isAxiosError(error)) {
          setError(error);
        } else {
          console.log(error);
        }
      });
  }

  return (
    <form onSubmit={handleSubmit}>
          {error && (
        <p className="error-message">
          Error {error.response?.status}: {error.response?.data as string}
        </p>
      )}
      <h2>Add entry</h2>
      // Rest of the code...
  ```

  - Link to the issue related: [Exercise 9.18](https://github.com/Lenoxo/diario-vuelo-Ilari-front/issues/4)

Link to the repos used:

1. [backend](https://github.com/Lenoxo/diario-vuelo-Ilari-back)
2. [frontend](https://github.com/Lenoxo/diario-vuelo-Ilari-front)

**Thoughts**: Well, today I almost had no time to practice, just about 70 minutes for all, but I managed to finish today the challenge with a borrowed computed while I'm visiting someone.

### Day 58: May 5, 2024

**Today's Progress**:

- **Learning Typescript** Today I practiced solving exercise 9.17 from Fullstack Open section of Typescript:

  This exercise was about:

      Adding a new Diary entry sending it from the frontend to the backend.
      For this challenge, it's not necessary to add type and data validations, because we assume that the data will be send in the correct format.

  What changed from yesterday on the way I solved it, is that I tracked my progress in Github, using the `ISSUES` and `PROJECT` functionalities.

  - Link to the issue related: [Exercise 9.17](https://github.com/Lenoxo/diario-vuelo-Ilari-front/issues/2)

Link to the repos used:

1. [backend](https://github.com/Lenoxo/diario-vuelo-Ilari-back)
2. [frontend](https://github.com/Lenoxo/diario-vuelo-Ilari-front)

**Thoughts**: I just remembered the proper way of how to handle projects that Robert told in his video, and now, I look forward to keep improving in that part of track my progress like the professionals do.

### Day 57: May 4, 2024

**Today's Progress**:

- **Learning Typescript** Today I advanced learning about how to implement these 2 concepts:

  - Adding types to react states
  - Adding types to generic functions, like `axios.get()`

  And I implemented those concepts solving the exercise 9.16. Following the Typescript lessons in Fullstack Open.

  The exercise in brief, was focused on rendering the diaries data from the backend, using types in the states and in `axios.get()`

  But something that took me more than I expected was a mistake I made, because I forgot to `git checkout exercise-9.16` and instead made all changes in the `main` branch.

  To solve it, I had to checkout to `exercise-9.16` from the first commit, and cherry pick commits from main until the last one. And then, sadly, make a `git reset --hard` to the first commit in the main branch.

Link to the repos used:

1. [backend](https://github.com/Lenoxo/diario-vuelo-Ilari-back)
2. [frontend](https://github.com/Lenoxo/diario-vuelo-Ilari-front)

**Thoughts**: The git problem part took me more time than expected because I forgot some things about git usage, and had to google it to remember it, so, as a lesson for me, remember after the first commit, making a checkout to the work branch.

### Day 56: May 3, 2024

**Today's Progress**:

- **Learning Typescript** Today I advanced learning about how to implement these 3 concepts:

  - Literal types
  - Discriminated unions
  - exhaustive checking
    - Using the never value to handle unexpected types.

  And I implemented those concepts solving the exercise 9.15. Following the Typescript lessons in Fullstack Open.

The exercise was long, but in brief, I needed to add new types for the courses, extend common types between interfaces and implement the exhaustive checking for every interface.

Also, do the exhaustive checking in a new component, `Part`, referring to a part / module of a complete course.

That's to validate the `coursePart` data.

Here is just a bit of what I did during the exercise:

```ts
import { CoursePart } from "../types";

export function Part({ coursePart }: { coursePart: CoursePart }) {
  /**
   * Helper function for exhaustive type checking
   */
  const assertNever = (value: never): never => {
    throw new Error(
      `Unhandled discriminated union member: ${JSON.stringify(value)}`,
    );
  };

  switch (coursePart.kind) {
    case "basic":
      return (
        <article>
          <h3>{coursePart.name}</h3>
          <p>Exercises: {coursePart.exerciseCount}</p>
          <p>{coursePart.description}</p>
        </article>
      );

    case "group":
      // ...
    case "background":
      // ...
    case "special":
      // ...

    default:
      return assertNever(coursePart);
  }
}
```

Link to the repos used:

1. [Half Stack application](https://github.com/Lenoxo/Half-stack-Courses-React-TS)

**Thoughts**: Today was very difficult for me to focus on the coding part, mainly because of two factors:

- the environment where I was practicing
- Not having a good night sleep, just 4.5 hrs the last night. Mainly because of things outside of my control.

However, what I can control, is to practice earlier programming, and going to sleep earlier too, maybe I get to squeeze 1 or 2 hours while sleeping 8+ hours.

### Day 55: May 2, 2024

**Today's Progress**:

- **Learning Typescript** Today I advanced completing the exercise 9.14 following the Typescript lessons in Fullstack Open.

The exercise was about dividing the App.tsx parts of a course page in 3 components, `Header`, `Content` and `Total`, adding types where needed.

Here is an example of what I added in `Content`:

```ts
interface CourseData {
  name: string;
  exerciseCount: number;
}

export function Content(props: CourseData) {
  return (
    <p>
      {props.name} {props.exerciseCount}
    </p>
  );
}
```

What I would like to highlight is that at first assigning types to the props is quite easy. But an useful tip I found when it comes about where to define them, is that if you only use in one file the types, define them in that same file, but if the types are used in multiple files, then it's better to use a types.ts file.

Link to the repos used:

1. [Half Stack application](https://github.com/Lenoxo/Half-stack-Courses-React-TS)

**Thoughts**: Today I had less time to practice that I wanted but well, unexpected things happen everytime.

Aside of that. Just as a curious detail, probably this is the day were I write the most in a diary I can remember in my entire life.

### Day 54: May 1, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I advanced putting all the 100 days of code entries / diaries in order, updating it with my latest advancements in the challenge.

  Now, I want to apologize for not following the challenge for almost 2 months, what I can say is that those days were difficult ones mainly for family and personal conflicts.

  Also, some accounts of mine, like the Twitter one, received some reports a while ago, just for avoiding false positives and blocking without any good reason again, I didn't public anything until now.

  Starting tomorrow, I'll be using again LinkedIn and Twitter for sharing my progress, because it's a part of the challenge I don't want to avoid to fully complete it.

  Link to the repos used:

  1. This repo that you're using to read the file :)

**Thoughts**: Jaja, I was supposed to talk the stuff above in this section, but I consider it to be relevant for my path during the challenge, so, I'll let that slide to my perfectionist self.

Aside of that. Just as a curious detail, probably this is the day were I write the most in a diary I can remember in my entire life.

### Day 53: April 30, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I advanced mainly organizing some personal configs for my dev environment, like configs for `waybar, hyprland, dunst...`.

  And lastly, thanks to be coding using `gtk-css` for waybar styles, I learned about an interesting pseudoclass, `element:empty`, for applying certain styles if an element is empty.

  In `gtk-css` it doesn't work that way, but the research stills useful because now I can practice with that class for the upcoming days.

  Link to the repos used:

  1. Those are my private files, for now I won't share them.

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 52: April 29, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I advanced practicing the backend for `patientor`, improving the logic to add a new patient, with error handling, data and type checking and also, fixing an error with the base patient data.

  For future reference, you can solve pre-existent data conflicts using the types for checking data (`NewPatient`), and then, defining them as the complete data (`Patient`), like in this example:

  ```ts
  import { Patient } from "../src/types";
  import { checkPatientData } from "../src/utils";

  const data = [
    {
      id: "d2773336-f723-11e9-8f0b-362b9e155667",
      name: "John McClane",
      dateOfBirth: "1986-07-09",
      ssn: "090786-122X",
      gender: "male",
      occupation: "New york city cop",
    },
    {
      id: "d2773598-f723-11e9-8f0b-362b9e155667",
      name: "Martin Riggs",
      dateOfBirth: "1979-01-30",
      ssn: "300179-77A",
      gender: "male",
      occupation: "Cop",
    },
    {
      id: "d27736ec-f723-11e9-8f0b-362b9e155667",
      name: "Hans Gruber",
      dateOfBirth: "1970-04-25",
      ssn: "250470-555L",
      gender: "other",
      occupation: "Technician",
    },
    {
      id: "d2773822-f723-11e9-8f0b-362b9e155667",
      name: "Dana Scully",
      dateOfBirth: "1974-01-05",
      ssn: "050174-432N",
      gender: "female",
      occupation: "Forensic Pathologist",
    },
    {
      id: "d2773c6e-f723-11e9-8f0b-362b9e155667",
      name: "Matti Luukkainen",
      dateOfBirth: "1971-04-09",
      ssn: "090471-8890",
      gender: "male",
      occupation: "Digital evangelist",
    },
  ];

  // The object mapping is done here to ensure that the previous data matches with gender type (as enum)
  const patientsData: Patient[] = data.map((patient) => {
    const newPatient = checkPatientData(patient) as Patient;
    newPatient.id = patient.id;
    return newPatient;
  });

  export default patientsData;
  ```

  Link to the repos used:

  1. [exercises repo - backend](https://github.com/Lenoxo/backend-typescript-fullstack-open)
  2. [patientor fork - frontend](https://github.com/Lenoxo/patientor)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 51: April 28, 2024

**Today's Progress**:

- **Practicing with Personal Projects** Today I advanced practicing the backend for `patientor`, adding the basic functionality to add a new patient.

  Link to the repos used:

  1. [exercises repo - backend](https://github.com/Lenoxo/backend-typescript-fullstack-open)
  2. [patientor fork - frontend](https://github.com/Lenoxo/patientor)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 50: April 27, 2024

**Today's Progress**:

- **Learning Typescript:** Today I advanced practicing with the `diario-vuelo-Ilari` project implementing type validation even in execution time thanks to `enum` and `type predicates` applied in addDiaryEntry.

  Something I would like to improve is to avoid making large commits like today's one. So I have to plan and divide better the subproblems and commit their solutions.

  Link to the repos used:

  1. [diario-vuelo-Ilari](https://github.com/Lenoxo/diario-vuelo-Ilari)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 49: April 26, 2024

**Today's Progress**:

- **Learning Typescript:** Today I advanced practicing adding the HTTP POST handling for a new Diary Entry in `diario-vuelo-Ilari`

  Something I would like to highlight is that you can use `Math.max()` in a more dynamic way, like this:

  ```ts
  function addEntry(entry: NewDiaryEntry): DiaryEntry {
    const savedEntry = {
      id: Math.max(...entries.map((e) => e.id + 1)),
      ...entry,
    };
    entries.push(savedEntry);
    return savedEntry;
  }
  ```

  Link to the repos used:

  1. [diario-vuelo-Ilari](https://github.com/Lenoxo/diario-vuelo-Ilari)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 48: April 25, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** Today I advanced practicing with exercises 9.10 and 9.11 in the exercise-repo. Implementing utility types and connecting the endpoints `/api/diagnose` and `/api/patients` to the frontend.

  One thing I would like to highlight, is that you can destructure the variable for an element within `Array.map()`, here is what I implemented for reference:

  ```ts
  import patientsData from "../../data/patients";
  import { NonSsnPatient, Patient } from "../types";

  function getAllPatients(): Patient[] {
    return patientsData;
  }

  function getAllPatientsWithoutSsn(): NonSsnPatient[] {
    return patientsData.map(
      ({ id, dateOfBirth, name, gender, occupation }) => ({
        id,
        dateOfBirth,
        name,
        gender,
        occupation,
      }),
    );
  }

  export { getAllPatients, getAllPatientsWithoutSsn };
  ```

  Link to the repos used:

  1. [exercises repo - backend](https://github.com/Lenoxo/backend-typescript-fullstack-open)
  2. [patientor fork - frontend](https://github.com/Lenoxo/patientor)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 47: April 24, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** Today I learned about the `Omit<TypeName, "key or value to omit"` and applied it in the current project of `diario-vuelo-Ilari`. Also, I learned a bit of how to detect the subfiles in `ts-node-dev`. Mainly you have to set the **directory to watch**, like `src/`, not the `--watch` or `--exit-child` flags.

  Link to the repos used:

  1. [diario-vuelo-Ilari](https://github.com/Lenoxo/diario-vuelo-Ilari)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 46: April 23, 2024

**Today's Progress**:

- **Learning Typescript:** Today I continued learning more about Typescript, on how the json imports as modules works, practicing with the diario-vuelo-Ilari project.

  In one sentence, the json import recommendation is that, when you work with modules in the project, name the files differently, even if the extension is not the same. Because the `.js` files are imported first than the `.json` ones thanks to the alphabetic order.

  Link to the repos used:

  1. [diario-vuelo-Ilari](https://github.com/Lenoxo/diario-vuelo-Ilari)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 45: April 22, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** Today I continued improving one of my first projects, YardSale, fixing errors with the last element I added, which is the search bar.

  Link to the repos used:

  1. [exercises repo - YardSale](https://github.com/Lenoxo/YardSale)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 44: April 21, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** Today I continued improving one of my first projects, YardSale, connecting it with more pages and fixing the dark mode functionality. Also I learned about the `<select>` element and how to style it.

  Link to the repos used:

  1. [exercises repo - YardSale](https://github.com/Lenoxo/YardSale)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 43: April 20, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** Today I advanced improving one of my first projects, YardSale, connecting it with more pages and fixing visual bugs mainly.

  Link to the repos used:

  1. [exercises repo - YardSale](https://github.com/Lenoxo/YardSale)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 42: April 19, 2024

**Today's Progress**:

- **Learning Typescript:** Today I advanced completing exercise 9.9, connecting the backend endpoint to the patientor frontend in `/ping` when making a request from the frontend

  Link to the repos used:

  1. [exercises repo - backend](https://github.com/Lenoxo/backend-typescript-fullstack-open)
  2. [patientor fork - frontend](https://github.com/Lenoxo/patientor)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 41: April 18, 2024

**Today's Progress**:

- **Learning Typescript:** Today I advanced Practicing with exercises 9.8, creating a little server using `Express.js` which responds to requests in `/api/ping` endpoint.

  Also related to with that practice, I learned the basics of how to configure a project using `tsconfig.json` and `ts-node-dev` `ts-node`.

  Link to the repos used:

  1. [diario-vuelo-Ilari](https://github.com/Lenoxo/diario-vuelo-Ilari)

  2. [exercises repo](https://github.com/Lenoxo/backend-typescript-fullstack-open)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 note](#day-54-may-1-2024)

### Day 40: February 10, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** Today I added the last project I did, the technology and link to my twitter in my webpage.
  - During that time, I noticed that the compiling time for the dev server using Next.js in version 13.5.4 was really slow on my machine.
  - It only has an `Intel Pentium G2030` so I tried to research a little about that.
  - What I found is that Next.js 13 has a known issue with compiling time, and many devs where taking about that in this issue: [click](https://github.com/vercel/next.js/issues/48748)
  - For me, right now, what worked to make dev time faster, is upgrading from `13.5.4` to `14.1`.

**Thoughts**: Today I did the coding part as early as possible, and noticed the difference for the focus I had during my coding time. Also, I had a curious bug during adding Docker technology icon to my webpage, for what I tried, it appears to be related with how I implemented the component for icons and what happens if I do a duplicated one.

### Day 39: February 7, 2024

**Today's Progress**:

- **Learning Typescript:** Today I finised the First Steps section, completing the last exercise of WebExercises, which took me about 90 minutes to solve handling errors well too. [**Full-stack Open**](https://fullstackopen.com/)
  The funniest error I had, was that this message was constantly showing as a 500 error:

```
Error: You didn't gave me a number of hours, check your input
    at parseArgValues (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/src/TS-exercices/ejercicios-9.1-9.7/exerciseCalculator.ts:60:13)
    at /home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/src/TS-exercices/index.ts:60:46
    at Layer.handle [as handle_request] (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/express/lib/router/layer.js:95:5)
    at next (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/express/lib/router/route.js:144:13)
    at Route.dispatch (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/express/lib/router/route.js:114:3)
    at Layer.handle [as handle_request] (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/express/lib/router/layer.js:95:5)
    at /home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/express/lib/router/index.js:284:15
    at Function.process_params (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/express/lib/router/index.js:346:12)
    at next (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/express/lib/router/index.js:280:10)
    at /home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/body-parser/lib/read.js:137:5
```

And even after making sure that `parseArgValues` and its error was captured within a try / catch block, it kept showing again and again.

```ts
app.post("/exercises", (req, res) => {
  // eslint-disable-next-line @typescript-eslint/no-unsafe-assignment
  const { daily_exercises, target } = req.body;
  if (!daily_exercises || !target) {
    return res.status(400).json({
      error: "parameters missing",
    });
  }

  try {
    const parsedTarget: number = Number(target);
    if (isNaN(parsedTarget)) return res.status(400).sendFile(errorPage);
    // parseArgValues also validates the format of the array

    // eslint-disable-next-line @typescript-eslint/no-unsafe-argument
    const parsedDailyExercises = parseArgValues(daily_exercises, 0);

    const result = rateTrainingPeriod(parsedDailyExercises, parsedTarget);
    return res.json(result);
  } catch (error) {
    if (error instanceof Error) {
      const errorMessage = error.message;
      return res.status(400).json({
        errorMessage,
      });
    }
    // console.error(error);
  }
});
```

Until lastly, I decided to restart ts-node-dev, and, it showed as I wanted finally:

```jsonc
{
  "errorMessage": "You didn't gave me a number of hours, check your input",
}
```

Bottom line, reboot your ts-node-dev if you captured an error and you're sure it is right.

**Thoughts**: Today I didn't have almost time to practice and write progress in social media, so, tomorrow I'll be doing that at the end of the practice.

### Day 38: February 6, 2024

**Today's Progress**:

- **Learning Typescript:** Today I advanced two sections in First Steps, the horrors of any and Type assertion, and I finished the 9.6 exercise too [**Full-stack Open**](https://fullstackopen.com/)
- **Practicing with Docker:** Today I found that is for the docker isolation that clipboard doesn't work as intended, even if you configure the sockets for xclip and xsel from the container to have access to the host ones, so, the only workaround is starting neovim within a tmux session.
  - Repository: `https://github.com/Lenoxo/temp-nvim`
  - Docker Hub: `https://hub.docker.com/r/lenoxo/nvimdocker`

**Thoughts**: I had a good night sleep and gosh, how the body feels really different from yesterday is wonderful, and also, I updated some things in the docker project image to match my current config, rather than the old 2 months one.

Also, it appears that the issue with my Twitter account is solved, so tomorrow I'll be publishing the missing days in the account and explain a bit what happened.

### Day 37: February 5, 2024

**Today's Progress**:

- **Practicing with Docker:** Today I debugged some plugins not working in this Dockerized neovim, the only one that's missing is the clipboard management, I'll see if I research more about the topic.
  - Repository: `https://github.com/Lenoxo/temp-nvim`
  - Docker Hub: `https://hub.docker.com/r/lenoxo/nvimdocker`

**Thoughts**: Today was a very difficult day for me, ignoring personal details the hardest thing was that I didn't sleep at all last night, so focusing, practicing and learning was a real challenge.

### Day 36: February 4, 2024

**Today's Progress**:

- **Learning Typescript**: Today I advanced in the First Steps part, learning about some details when using modules in Typescript and tsconfig, how to use `express.js` with typescript (you need to install express types `@types/express`), and lastly, complete exercises 9.3 to 9.5 [**Full-stack Open**](https://fullstackopen.com/).
- As always, all the exercises I did today, are in one of my practice repos:
  [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/challenges-in-process)
- **Practicing with Docker:** Today also I did a little project, with my neovim configs, plugins and cache loaded in a Docker image, for easy install and usage. Uses alpine linux as base distro and later on, I'll see if I pack it without the cache.
  - Repository: `https://github.com/Lenoxo/temp-nvim`
  - Docker Hub: `https://hub.docker.com/r/lenoxo/nvimdocker`

**Thoughts**: I advanced more today, but something I have to improve is that I break my pomodoro cycles, is supposed that after 1 hour, even when it's funny, you have to get up and stretch for your health, but for me, time flies when I'm learning / practicing, and after 2 hours I notice that mistake.

### Day 35: February 3, 2024

**Today's Progress**:

- [**Learning Typescript**]: Today I advanced in the First Steps part, doing exercises with bmiCalculator and exerciseCalculator, until finishing exercise 9.3 [**Full-stack Open**](https://fullstackopen.com/).
- As always, all the exercises I did today, are in one of my practice repos:
  [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/challenges-in-process)

**Thoughts**: I learned more, after some debugging with this error:

```bash
➜  HTML-CSS-JS-challenges git:(challenges-in-process) ✗ npm run calculateBmi 180 74

> html-css-js-challenges@1.0.0 calculateBmi
> ts-node -p src/TS-exercices/ejercicios-9.1-9.7/tsconfig.json src/TS-exercices/ejercicios-9.1-9.7/bmiCalculator.ts 180 74

SyntaxError: /home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/src/TS-exercices/ejercicios-9.1-9.7/tsconfig.json: Expected double-quoted property name in JSON at position 54
    at parse (<anonymous>)
    at Object.Module._extensions..json (node:internal/modules/cjs/loader:1453:39)
    at Module.load (node:internal/modules/cjs/loader:1207:32)
    at Function.Module._load (node:internal/modules/cjs/loader:1023:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:135:12)
    at phase4 (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/ts-node/src/bin.ts:649:14)
    at bootstrap (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/ts-node/src/bin.ts:95:10)
    at main (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/ts-node/src/bin.ts:55:10)
    at Object.<anonymous> (/home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/node_modules/ts-node/src/bin.ts:800:3)
    at Module._compile (node:internal/modules/cjs/loader:1376:14)
```

What happened is that I did wrong my npm script, because the correct flag for choosing a custom tsconfig.json, is `-P`, not `-p`. Using `npm run ts-node -- --help` was really helpful in this case. (An intended pun :D )

### Day 34: February 2, 2024

**Today's Progress**:

- [**Learning Typescript**]: Today I advanced in the First Steps part until finishing exercise 9.1 [**Full-stack Open**](https://fullstackopen.com/).
- As always, all the exercises I did today, are in one of my practice repos:
  [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/challenges-in-process)

**Thoughts**: I learned something curious, and is that you can change the `tsconfig` file that ts-node will be using, passing the flag -P, followed by the archive route, I used something like this for one of my aliases in `package.json`:

```jsonc
{
"scripts": {
  //...
  "calculateBmi": "ts-node -P src/TS-exercices/ejercicios-9.1-9.7/tsconfig.json src/TS-exercices/ejercicios-9.1-9.7/bmiCalculator.ts",
  //...
}
```

And something weird happened yesterday with my Twitter account, until it's resolved, I won't give more details, the only thing I have to say, is that I keep holding on with this challenge (Like the song).

### Day 33: February 1, 2024

**Today's Progress**:

- [**Learning Typescript**]: Today I advanced in the First Steps part until Type narrowing [**Full-stack Open**](https://fullstackopen.com/).
- As always, all the exercises I did today, are in one of my practice repos:
  [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/challenges-in-process)

**Thoughts**: I did some research, testing by myself and found why the problem the last day happened, and it's because I was using in my package.json this line, and it has a conflict with ts-node, the easiest way to solve it in my case, was removing it:

```jsonc
{
  //...
  type: module
  //...
}
```

Also, these last 3 days I didn't advance in the challenge for some problems related to my current pc, but I managed to solve them, so, I'll be giving my best since now.

### Day 32: January 27, 2024

**Today's Progress**:

- [**Learning Typescript**]: Today I did some research about good resources to learn about typescript in a more practical way, and found [**Full-stack Open**](https://fullstackopen.com/), that has a module about using typescript, and plus node and react projects guides to practice with. So I followed the introduction part today.
- As always, all the exercises I did today, are in one of my practice repos:
  [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/challenges-in-process)

**Thoughts**: I had a problem while using `ts-node` today in my practice repo, and later on, noticed that it was because I used Astro, the default config for Astro with tailwind was in conflict and the .ts files weren't recognized. For now, I don't want to have my focus divided, so I removed Astro from the repo and the commands worked as intended.

This is the bug I had, for future reference, and maybe solve it when I learn about Astro:

```bash
HTML-CSS-JS-challenges git:(challenges-in-process) ✗ npm run ts-node file.ts

> square-solstice@0.0.1 ts-node
> ts-node file.ts

TypeError: Unknown file extension ".ts" for /home/emanuel/Descargas/Temporal/Desarrollo Web/HTML-CSS-JS-challenges/file.ts
    at Object.getFileProtocolModuleFormat [as file:] (node:internal/modules/esm/get_format:160:9)
    at defaultGetFormat (node:internal/modules/esm/get_format:203:36)
    at defaultLoad (node:internal/modules/esm/load:141:22)
    at async ModuleLoader.load (node:internal/modules/esm/loader:409:7)
    at async ModuleLoader.moduleProvider (node:internal/modules/esm/loader:291:45)
    at async link (node:internal/modules/esm/module_job:76:21) {
  code: 'ERR_UNKNOWN_FILE_EXTENSION'
```

### Day 31: January 26, 2024

**Today's Progress**:

- [**Learning Typescript**]: Today I finished the introduction part of [Typescript for JS programmers](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html), obviously playing with all the demo code and making some examples on my own to get the idea of the basics.
- As always, all the exercises I did today, are in one of my practice repos:
  [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/challenges-in-process)

**Thoughts**: An example that confused my for about 6 minutes is the backpack one, but I realized how easy it was after some chatting with ChatGPT making it explaining why my code didn't work, and it was because I confused the declaration of a type with generic, with creating an array and using another type as its elements values type:

```ts
// Generics (Like variables in types)

interface BirthdayList<Type> {
  add: (data: Type) => void;
  delete: () => Type;
}

declare const birthdayList: BirthdayList<object>;

const upcomingBirthday = birthdayList.delete();

birthdayList.add("May 25/2021");

// What I was trying to use

interface Clients<Type> {
  add: (data: Type) => void;
  delete: () => Type;
}

const updatedClients: Clients<object> = [
  { username: "Michael Jordan", age: 17 },
];

// What I really wanted to do

type Client = { username: string; age: number };

type ClientsArray = Array<Client>;

const clientsArray: ClientsArray = [];

const newClient = { username: "Jason", age: 30 };

clientsArray.push(newClient);
clientsArray.push(45); // Another intentional error to practice with static type checking
```

### Day 30: January 24, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I finished this course, advancing five classes, where I learned:

  - The differences between shell vs exec commands in Dockerfiles, also when to use them.
  - How to make executable binaries in docker allowing changing parameters combining ENTRYPOINT and CMD in the Dockerfiles
  - What is and how to use the build context in docker images
  - How to use multi-stage build when building images

    - A curious detail for me is that you can reference past images layers using the builder 'nickname' to call it in one easy way, and the `--from` flag in the Dockerfiles:

      ```yml
      FROM node:12 as builder

      COPY ["package.json", "package-lock.json", "/usr/src/"]

      WORKDIR /usr/src

      RUN npm install --only=production

      COPY [".", "/usr/src/"]

      RUN npm install --only=development

      RUN npm run test


      # Productive image

      FROM node:12

      COPY ["package.json", "package-lock.json", "/usr/src/"]

      WORKDIR /usr/src

      RUN npm install --only=production

      # The above part is duplicated because you can optimize the image build time by using the cache in the layer system

      COPY --from=builder ["/usr/src/index.js", "/usr/src/build", "/usr/src/"]

      EXPOSE 3000

      CMD ["node", "index.js"]
      ```

  - **Section Notes:** (They are in Spanish, because it's easier for me to write them in my mother tongue and the course is in Spanish too)
    - From the yesterday promise:
      ![notes](https://imgur.com/qfOauJi.png)
    - Today's notes:
      ![notes](https://imgur.com/pGyhDsA.png)
  - also, I learned more useful commands:

    - Commands:

      - Making a build using a different Dockerfile:
        `docker build -t prodimg -f build/production.Dockerfile .`

      - Using dive from a container, to see an image details that is located in the host machine:
        `sudo docker run -it --rm --name divecontainer -v /var/run/docker.sock:/var/run/docker.sock wagoodman/dive prodimg`

**Thoughts**: Well, I advanced more than I expected in two hours learning about docker, and I'm excited about what I can do now with docker, because one of the things I can remember drains most of my time when using a new computer / working another computer that is borrowed for someone else while I'm visiting, is that configuring the dev environment takes a lot of time, and now I can use docker to simplify that.

Also, tomorrow I'll be covering typescript basics, while improving my personal projects that are abandoned, for about 2 months the most recent one.

### Day 29: January 23, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I advanced two classes, where I learned about docker-compose.override.yml, how to use it and write personalized configs for docker-compose, and lastly how to manage disk space and limit ram usage for docker containers, also I learned more useful commands:

  - Tomorrow I'll be sharing here this section notes, because I finished it today.
  - Also, another curious detail I learned today, is that, containers, only can listen to one port in the host machine per container, so, if you want to horizontally scale a service in docker-compose, you would need to use a range of ports, like this in your docker-compose file:
    ```yml
    # ...
    ports:
      - "3000-3003:3000"
    # ...
    ```
  - Commands: - Clean unused containers, networks and images:
    - `docker container prune`
    - `docker network prune`
    - `docker image prune` - Clean all unused files in the system by docker
    - `docker system prune` - Force rm containers
    - `docker rm -f containerName or id` - Limit ram usage of a container
    - `docker run -d --memory 40m or 1g app` - Check if a container stopped because it ran Out Of Memory
      `docker inspect containerName`
  - output:

             ```jsonc
               {
               // ...
               OOMKilled, true
               // ...
               }
             ```

        `- Check ram usage of docker

    `docker stats`- Horizontally scale containers used in a service:
    `docker-compose up -d --scale appService=4`
    **Thoughts**: Today for personal reasons I only advanced one hour, so yeah, nothing under my control for now.

### Day 28: January 22, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I advanced three classes, where I learned about docker-compose, how to use it, basic commands with it, and how to apply it in the software development, of course, also I learned more useful commands:
  - One curious detail for me, is that, when you use `docker-compose exec serviceName bash`, you don't need to add -it as parameter, thanks to docker-compose
  - Another curious detail, is that you can ignore files when doing bind mounts specified in docker-compose.yml like this:
    ```yml
    # ...
    volumes:
      - .:/usr/src
      - /usr/src/node_modules # Here, I ignore from the bind mount, node_modules folder, to prevent override of it, from the host filesystem, to the container filesystem.
    # ...
    ```
  - Commands:
    - Activate all services listened in the docker-compose file
      `docker-compose up`
    - See logs
      - of the service
        `docker-compose logs serviceName`
      - Follow service logs
        `docker-compose logs -f serviceName`
    - Execute a command within a service container
      `docker-compose exec serviceName command`
    - Stop all services
      `docker-compose down`
    - Build an image for a service, specified in docker-compose.yml
      `docker-compose build serviceName`
    - Activate all services detached
      `docker-compose up -d`

**Thoughts**: Today I had a bit more time to practice, one and a half hour to be precise. Also, I knew just basic commands for using docker-compose when I was building my most recent backend project, Devshop API, and it was groundbreaking to discover how I can configure even more of the services, and I know tomorrow I'll learn even more, so, I'm excited about that.

### Day 27: January 21, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I advanced two classes, where I learned about the cache of the layer system, how to optimize it in a simple way, and docker networking, AKA connecting containers and making them talk to each other, and lastly, more useful commands:
  - As promised, I attach some of my last day notes about the past section of the course (They are in Spanish, because it's easier for me to write them in my mother tongue and the course is in Spanish too):
    - ![notes](https://imgur.com/bFpsyaW.png)
  - Another curious detail for me, is that, if you organize well your steps when using a Dockerfile, you optimize build time for images, thanks to the efficient cache use.
  - Commands:
    - List docker networks
      `docker network ls`
    - Create new network
      `docker network create creativeName`
    - Connect container to a docker network
      `docker network connect networkName containerName`
      The above command works ONLY if the containers you want to connect, are in the same network
    - Assign env variables to containers
      `docker run --env MONGO_URL=mongodb://...`

**Thoughts**: It's like a filler word that I noticed, today, today, today. Kinda funny, but well, currently, I want to try something that I hope, I'll be telling right here in the coming days.

### Day 26: January 20, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I advanced two classes, where I learned more about the layer system in images used by Docker, discovered a curious tool called dive, that lets you see more details about an image history, and lastly, more useful commands:
  - A detail that is curious to me, is that, like git, the image layer system saves changes made in the file system, and the creation and deletion of an archive, is registered and has a weight in the final image size, even if you removed a past created file from the image, it stills in the image history as a previous change.
  - **Dive**: It's a tool used to see more info about the image history, layers and current state per layer, the link it's right here: [**GitHub link**](https://github.com/wagoodman/dive)
  - Commands:
    - Show an image history:
      `docker history IMAGE_NAME:TAG` → `docker history lenoxo/ubuntu:message`
    - Use dive to watch more details about an image history:
      `dive IMAGE_NAME:TAG` → `dive lenoxo/ubuntu:message`

**Thoughts**: Today I had just one hour to learn, and because I finished an important part of the course, tomorrow I'll be sharing here my notes from that part too.

### Day 25: January 19, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today all the time I had for learning (1h and 30 mins), I spent it debugging that error of the last day:

  ```bash
  ➜  dockerImages docker push lenoxo/ubuntu:message
  The push refers to repository [docker.io/lenoxo/ubuntu]
  6389d27b5662: Preparing
  a1360aae5271: Preparing
  denied: requested access to the resource is denied
  ```

What I tried is this:

1. Doing the same push in another environment, in this case, I used an instance of Play with Docker, and the above command worked as intended:

```bash
[node1] (local) root@192.168.0.18 ~
$ docker push lenoxo/ubuntu:message
The push refers to repository [docker.io/lenoxo/ubuntu]
f3c98273d297: Layer already exists
8e87ff28f1b5: Layer already exists
message: digest: sha256:1c69461ad98cb1131e7460afa03f5fa31cbbb7eac9e22c7388089657206ff07a size: 736
```

2. Restoring a past snapshot I had before I installed docker desktop in Arch Linux and trying the command again, but with sudo, because I didn't configure at that time the docker group, worked as intended.

```bash
➜  ~ sudo docker push lenoxo/ubuntu:message
[sudo] contraseña para emanuel:
The push refers to repository [docker.io/lenoxo/ubuntu]
a7bcbb0d1b6a: Layer already exists
8e87ff28f1b5: Layer already exists
message: digest: sha256:d7d9f02abb6d491f5a3ee230c1e0ed8044dbaf3f5deb9be84cfe03afe43d1df6 size: 736
```

4. Going back to the docker desktop snapshot and trying to clear all docker config, and pass config too, before using again docker push, and the error happened again.
5. Removing with `pacman -Rns docker-desktop` and trying again the command, both ways, using and not using sudo, and the error happened again.

So, what I have to say is that it appears to be a rare bug with how the configuration is rewritten by docker-desktop in Arch Linux, and because the package still in experimental phase, I think that explains why this happened.
For now, I'll just use docker and docker-compose installed from official repos in Arch Linux, and maybe in the weekend, I'll report this bug in the docker community.

**Thoughts**: These last two days I didn't advance in this challenge mainly because I had personal problems, that took all my day and until this evening, I was able to come back to home and learn again.

### Day 24: January 16, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I advanced 2 classes, where I learned how to copy files/folders from and to containers, create (build) images, briefly how the layer system of images works, how to change images tags and how to pull and push images, here are some useful commands I learned:
  - Copy a folder to a container, and upside down.
    `docker cp testfiles copycont:/testing`
    `docker cp copycont:/testing localtesting`
  - List and pull images
    `docker image ls`
    `docker image pull ubuntu:22.04`
  - Rename images tags
    `docker tags ubuntu:message lenoxo/ubuntu:message`
- For me, image layers work very similar to git commits, only saving the changes, and not copying again and again the same info.

- And I had some bugs, more specifically one that I couldn't resolve while I'm writing this so, I'll solve it tomorrow, and it is still happening even after I created the repository using docker hub, and logged-in in docker CLI.
  ```bash
  ➜  dockerImages docker push lenoxo/ubuntu:message
  The push refers to repository [docker.io/lenoxo/ubuntu]
  6389d27b5662: Preparing
  a1360aae5271: Preparing
  denied: requested access to the resource is denied
  ```

**Thoughts**: Well, today I advanced in this challenge more than the hour, so, I'll try to keep making bigger the time I reserve to practice in this challenge.

### Day 23: January 15, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I advanced 2 classes, where I learned what is the difference between bind mounts and volumes, and how to use both, here are some useful commands I learned:
  - Use a folder in the host machine as bind mount
    `docker run -d --name monguito -v /home/emanuel/dockerTests/mongodata:/data/db mongo`
  - Use an (autogenerated if not exists) volume for a container
    `docker run -d --name monguitoV --mount src=dbdata,dst=/data/db mongo`
  - List and create volumes
    `docker volume ls`
    `docker volume create nameVolume`

**Thoughts**: Well, today I procrastinated 1 hour, and it hurt a lot when some sudden events happened that took a good amount of my nighttime, so, I'll apply one of the parts taught in Atomic Habits; adapt your environment to make it almost impossible to procrastinate.

### Day 22: January 14, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I advanced 3 classes, where I learned briefly how the container's life cycle works, what is interactive mode and how to use it, how to expose ports in containers and see logs, here are some useful commands I learned:
  - Keep a container with Ubuntu running
    `docker run --name alpha -d ubuntu tail -f /dev/null`
  - Run a command in a container
    `docker exec nameCont echo "Hello world"`
  - Search container process ID (use name / ID)
    `docker inspect --format '{{.State.Pid}}' alpha`
  - Stop a container
    `docker stop id or name`
  - Expose ports of a container
    `docker run --name proxy -d -p 8080:80 nginx`
  - See logs of a container
    `docker logs -f --tail 3 proxy`
- Notes of this section (They are in Spanish, because it's easier for me to write them in my mother tongue and the course is in Spanish too):
  - ![notes](https://imgur.com/xTgrUZw.png)
    **Thoughts**: I had less time today because I spent most of the day with my family, and yesterday with some friends I won't see up to 8 months, but I managed to advance a little.

### Day 21: January 12, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I advanced 5 classes, where I learned about how the state in containers is managed, more exactly what is a container, what is the Docker architecture, practiced with my first used container, hello world and learned some useful commands:

  - Execute containers
    `docker run hello-world`
    `docker run --name jojo-reference hello-world`
  - List containers
    `docker ps` list of active containers
    `docker ps -a` list all containers
  - Remove containers
    `docker rm id-contenedor`
    `docker container prune` remove all inactive containers
  - Plus: Rename containers: `docker rename id-cont. nuevo-nombre`

When I finish a big section of the course, I'll put some notes again.

**Thoughts**: It was curious to see how every time I use docker run, it creates a new container and runs it, I thought it just reused the created container with cache, but it appears that only happens with the Image.

### Day 20: January 11, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I advanced 4 classes, mainly in the Introduction part, where I learned about what is Docker, the main problem that it solves, what is virtualization and how VM's and Containers work as ways to virtualize apps.

- Some of today notes (They are in Spanish, because it's easier for me to write them in my mother tongue and the course is in Spanish too):

  ![notes](https://imgur.com/q78ZAUw.png)

- Also, I had a few bugs to fix during my Docker-Destop install in Arch Linux, because there is just an experimental package, and one of the downsides it has that, currently the login process doesn't work in Docker-Desktop.

  - I managed to barely fix this by logging in using the CLI, but the account just logout after I reboot or close Docker-Desktop.

- And other bug I had, but that was all my fault, is that for 15 minutes I thought that dependencies weren't in the Arch repositories:
  - I was getting 404 errors when trying to install Docker-Desktop with `pacman -U`
  - The problem was that I don't upgrade the system every day, but once or twice per week, and the packages I was trying to install were updated.
  - So, to fix it, I just had to upgrade. `pacman -Syu`

**Thoughts**: Well, most of the practice time today was taken for the bugs, but I feel it's for now, much easier to learn about Docker than DSA.

### Day 19: January 10, 2024

**Today's Progress**:

- [**"Docker Course - Platzi"**](https://platzi.com/cursos/docker/): Today I did a pre-study session to get in my head the basic structure of the topic, which are the different parts of the course, why is Docker organized that way and why is so important to learn about it.
  Since tomorrow I'll start applying some things during learning that I hope will help me learn faster and retain better, combined with practice of course.

**Thoughts**: Today I had less time to practice, just about 1 hour, so I had to suspend for now the reinforcement I was doing with my knowledge gaps in the DSA course.

### Day 18: January 9, 2024

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I did a recall session of the course, and identified that I had knowledge gaps in:
  - BubbleSort
  - QuickSort
  - BFS and DFS
  - heap and trie tree
  - graphs

**Thoughts**: Today I finished very late the recall session, because I had some incidentals that I only complete after late night. And since tomorrow, I'll start learning about Docker.

Also, I didn't write here almost anything today because currently I'm very tired after this day. Hope to get a good night sleep.

### Day 17: January 8, 2024

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Well, I finished this course, and yeah, I'll practice with neovim more after watching the last class. Today I implemented my first LRU cache and it was exciting.
  - **In summary:**
    - This are some notes I took today, hope it helps if you read this:
      <img width="700px" src="https://i.imgur.com/sRGnNQa.png">
    - If you want to build and LRU you would need to combine two data structures, DoublyLinkedList and Maps.
    - And if you need in some part to get a key by it's value (in this case, node) you need to add another map to the recipe.
  - As always, all the exercises I did today, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/15766854901f185d9700b7f9c9db416319149718)

**Thoughts**: I'm getting more comfortable with the pen tablet, my third day using it and at least, I write readable letters now, and I think it is a really good coincidence that the last message from the course by Prime, was my yesterday Thoughts, seek and improve using this tools, to create really good things, and using those great opportunities I have right now, for me, and also, taking into account that there are a lot of people that don't have such opportunities like I have.

I'm really grateful with that part of my life, in fact, without entering in too much details, I know a few people that are currently in a bad situation, for now I can't help them, but if I improve and get better in this field, I'll have resources and ways to help them.

And I think for me completing this course was a good challenge, because currently I still learning English by myself, and I didn't know anything about Typescript, never used it before. It took me more time than expected also because I had knowledge gaps in math, more related to how to manage all the variables using **BigO**. I identified what I would like to improve in Typescript and Math, so maybe I'll checkout the Typescript docs / algebra that I was missing and practice with them the next week.

Ah, yeah, I'll start improving my projects and building new ones while I learn about Docker since past tomorrow, but tomorrow, I'll dedicate to practice and recall the most difficult parts for me from the course.

### Day 16: January 7, 2024

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced two classes, where I implemented the Dijkstra's shortest path search in a Graph Adjacency list, also I learned just briefly what are maps, and how the would be working underneath the hood in JS.
  - **In summary:**
    - JS doesn't have a good way to represent how the work within, but you trust the abstraction of using `{}` and `new Map()`
    - They work using ArrayList and hashing for generating a way to insert data in the structure.
  - As always, all the exercises I did today, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/39d0b6d72b9cd3936911f93e435672fdb6020b51)

**Thoughts**: I'm getting more comfortable with the pen tablet, and I feel I need to seek a way to implement all these algorithms in my current and coming projects, and later on, search for a way to see how the maps work in js, not the abstracted way, but the raw way.

And I had a funny bug when I was implementing the Dijkstra algorithm, because I forgot to iterate and just put an if statement, so it was just pushing to `out, curr` one time, not the full `prev` path:

```js

    const out: number[] = [];
    let curr = sink;
    // right way
    while (prev[curr] !== -1) {
        out.push(curr);
        curr = prev[curr];
    }
    out.push(source);

    return out.reverse();
// --- ---- ---
    const out: number[] = [];
    let curr = sink;
    // wrong way
    if (prev[curr] !== -1) {
        out.push(curr);
        curr = prev[curr];
    }
    out.push(source);

    return out.reverse();
```

### Day 15: January 6, 2024

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced two classes, where I implemented the Breath First Search in a Graph Adjacency Matrix, also, a Depth First Search in a Graph Adjacency List and lastly, I learned what is the Dijkstra's shortest path search in graphs.
  - **In summary:**
    - When you do a DFS in a Graph List, you need to return the path of how you got to the node.
    - This path is not necessary the shortest one, but the first one built as I remember.
    - In Dijkstra shortest path, it iterates looking for the shortest (smaller sum of distance weights) path to the objective node.
  - As always, all the exercises I did today, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/73ac8b36616a1f3ffbbdeefa2998b60068fedd25)

**Thoughts**: Uff, I'm getting used to use the pen tablet but not as fast as I would like, it stills taking me a lot of time writting, drawing and even moving around with the pen. Just a matter of practice and patience for now.

Ah, and taking about the code itself, today I felt it was difficult to visualize how the Dijkstra shortest path works, but after rewatching last class more slowly, I figured out how to visualize it in my mind.

### Day 14: January 5, 2024

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced two classes, where I learned how are graphs commonly represented and how to implement a Breath First Search in a Graph Matrix.
  - **In summary:**
    - Ways to represent a graph:
      - Adjacency List
      - Adjacency Matrix
    - BFS and DFS works very similar in graphs.
    - In BFS, you need to return a path of how you got to the needle, so you need to save your seen indexes and previous indexes to nodes.
  - As always, all the exercises I did, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/d980f47413f7ef40b423840eb74c76b464137104)

**Thoughts**: Today was a challenging day, because I am currently learning how to use a tablet to take notes, but no the one that has screen, I'm taking about the screen less tablet, for now, it's taking me so much time to get used to it.

And also, I had a confusion when I was trying to implement the BFS, and it was a fun mistake when I look back, because I was engaged with the way adjs indexes where looked, I firstly thought that you used adjs indexes **values** to get the prev and seen index in this code.

But later on, I noticed that it wasn't that way, just using the iteration variable `i`, you use that to get the index of the related node.

Here I attach part of today's notes to show this:
<img width="690px" src="https://i.imgur.com/qfj7cot.png">

### Day 13: January 3, 2024 - Happy New Year!

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced one class, where I learned about what are graphs (every tree is a graph, but not every graph is a tree), and key terminology to work with them.

**Thoughts**: Today because I had some private problems, I didn't manage to save time to practice in the morning, I would like to try it tomorrow or past tomorrow to make it work.

### Day 12: January 2, 2024 - Happy New Year!

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced two classes, where I implemented a heap and lastly, learned about tries, and how they are often used for building autocompletion programs.
  - As always, all the exercises I did, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/7ee7cda9807556e4e7cc93ace8440b282db67ebf)

**Thoughts**: Well, yesterday I spent all my time with my family so, my bad, I should save some more time to practice this programming skill.

### Day 11: December 31, 2023

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced one class, where I learned what is a heap, and how they change how you reference your parent and child nodes, without doing it using references like a linked list, but more like an ArrayList.
- Also, I didn't manage to complete the implementation part, so I hope tomorrow I finish it.
- **You can say, priority queue**

**Thoughts**: Today was very difficult to find this hour to practice, every 3 to 4 minutes were interruptions, but I understand why, so no problem, for today I did my best.

### Day 10: December 30, 2023

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced five classes, where I learned how to implement Depth First Search in Binary Search Trees, and the basic theory behind how to find values, insert new nodes and remove them from the binary tree.
  - **Bottom Line:**
    - In a binary search tree a rule that always has to be true, is that the nodes at the left of the current node, should have values <= to the current node value. And the right nodes values, should be > the current node value.
  - As always, all the exercises I did, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/e5164b0b3f20788a9302cb8a2a695e21f54b7b40)

**Thoughts**: Today I had even less time than yesterday, just an hour, but enough time to complete today's challenge, so, I'm happy with it.

### Day 9: December 29, 2023

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced four classes, where I learned what is Search by Breath First in Binary Trees, how to implement it, how to consider using this one or Depth First Search in Binary Trees, and lastly, how to compare binary trees both in structure and values.
  - **Bottom Line:**
    - `In Depth First Search:` You're implicitly using a Stack, so it preserves the shape / order of the structure.
      That makes it perfect to compare by shape Binary Trees.
    - `In Breath First Search:` You're using implicitly a Queue, so it doesn't preserve shape like a Stack would.
  - As always, all the exercises I did, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/a2b36b999d7db7572eddc88fe51cfbc3d8114c40)

**Thoughts**: Today I had less time but advanced all I could, and after I finish this course, I want to implement all of this in my current and coming projects, this last part about Depth and Breath search in Binary Trees captured my attention.

### Day 8: December 28, 2023

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced five classes, where I learned a bit of how to debug a a **DoublyLinkedList**. Also, I learned about what is a tree, what is a traverse a tree, and how to implement tree different ways to traverse a binary tree by depth first:
  - **PreOrder Traverse**, **In Order Traverse** and **PostOrder Traverse**
  - As always, all the exercises I did, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/33f9ecde3a6b06470d8b8cf91db01194a69f08ee)

**Thoughts**: Today I advanced more, also, I had a bit of time where I organized my notes and also did a bit of priming for the next DS I'll be learning during the next days, if I have more time, I'll organize more my other repos following day 3 advice.

### Day 7: December 27, 2023

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced two classes in where I learned how to implement a **DoublyLinkedList**, but I wasn't able to finish today the implementation part. So, it's for tomorrow.
  - Also, I did a brief recall of some stuff I was forgetting, like BinarySearch, the changes are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/108ce293120b1d5d352be00f9bccd3c8902ead9e/src/DSA-challenges)

**Thoughts**: I finally understood how recursion works in a basic level, with that being said, I have to admit that one of the things that slows me down for now is also learning how to use vim motions, but I'm getting used to them pretty quickly during these last couple of hours.

### Day 6: December 26, 2023

**Today's Progress**:

- **The Last Algorithm Course You'll Need**: Today I advanced one class in "The Last Algorithm Course You'll Need" and learned the basics of how to use quick sort.

**Thoughts**: Now it's a bit easier for me to visualize how do recursive calls happen, but I still feel that need some practice to fully understand it.

### Day 5: December 25, 2023

**Today's Progress**:

- **The Last Algorithm Course You'll Need**: I dedicated today to practice and understand better recursion, and now I feel that, in an easy problem I understand how to apply it, also, all the exercises I did with it, are in one of my github repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/blob/main/src/JS-challenges/recursion.js)
  - Resources I used today:
    - [Google DataStructures and Algorithms free course](https://techdevguide.withgoogle.com/paths/data-structures-and-algorithms/#sequence-9)
    - [¿Qué es la Recursividad?](https://www.youtube.com/watch?v=YwRjEOFxvO0)
    - chatgpt for creating some of the challenges.

**Thoughts**: I really feel that is difficult for now to visualize how the functions recurse themselves in every case, I still don't get it for now.

### Day 4: December 24, 2023 - Merry Christmas!

**Today's Progress**:

- **The Last Algorithm Course You'll Need**: Today I advanced just one class, and also, because currently, after doing the exercise, I'm even more confused about how to implement recursion, so, later or next day, I'll practice some time with other resources to understand better how recursion works.

**Thoughts**: Yesterday, I missed a day, for something that was out of my control at that time, more specifically, working and helping with a relative throw all day, and when I finished, I just had time to go to sleep and that's it.

Now, I think I could handle it better, waking up earlier to practice 1 hour before anything else in my day.

### Day 3: December 22, 2023

**Today's Progress**:

- **The Last Algorithm Course You'll Need**: Today I advanced three classes; Data Structures Q&A, Recursion and Path Finding: Base Case. (Which is the first part of recursion implementation)

  - Also, in this same topic, I found a great playlist in YouTube where a developer explains how different Data Structures are implemented in Typescript: [DataStructures List](https://www.youtube.com/playlist?list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd)

- **Improving my current projects**: According to an excellent video I've seen today: [Link to the video](https://www.youtube.com/watch?v=N7pXEy5i-Vs), now I'll be improving continuously all my current projects adding / setting up this:

  1. Code clarity: Making consistent the way I format code

  - Unit testing: Just for the critical features.

  2. Good branching: Using an issues / functionalities based branching and PR
  3. Good issue management: Using mainly Github Projects
  4. CI / CD: In some projects I have this already

  - Today, I advanced with that issue management in [DevShop API](https://github.com/Lenoxo/DevShop)

**Thoughts**: Today I advanced more than yesterday, and also learned how, a project is managed professionally, thanks to a great resource by Bob Fornal, he always has something valuable to teach.

Well, other thing I would like to mention is that I'm still kind a newbie with Twitter. So 1 step at a time.

### Day 2: December 21, 2023

**Today's Progress**:

- **The Last Algorithm Course You'll Need**: Today I advanced one class; ArrayBuffer or also called Ring Buffers.

**Thoughts**: Today I did two things:

- Accidentally erased my last week notes from the course and restoring them from scratch took me most of today's hour.
  - It happened because I forgot to save a backup of the .mozilla folder
- Trying to understand how that recycle of space works on the Ring Buffers, actually, I still don't understanding it well, so I'll search more about them tomorrow.
  Also, I really wanted to advance more but today I didn't manage well my time, so, I know what I have to prioritize.

### Day 1: December 20, 2023

**Today's Progress**:

- **Async-Landing**: Add links to my updated social media, own website and improving navbar links.
- **The Last Algorithm Course You'll Need**: Today I advanced two classes; Arrays vs Linked Lists and ArrayList.

**Thoughts** I wonder if I should share my current notes taken in Draw.io, because until I finish a course, they're really changing every single class / research I made.

### Day 0: December 18, 2023

**Today's Progress**: Set up the learning plan, I'll do the following during the next 100 days:

1. **Learning about DSA**: Using the free course from Frontend Masters [The Last Algorithm Course You'll Need](https://frontendmasters.com/courses/algorithms/)
2. **Learning about Docker**: Using the Platzi's Docker course [Curso de Docker](https://platzi.com/cursos/docker/)
3. **Learning about Typescript**: Using mainly Typescript docs and other resources if I hit a hard problem [Typescript Docs](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
4. **Building side projects**: This one is hard to predict, because I have some ideas but none of them concrete, so during the above learning phase, I'll use some time to search for ideas of projects that could be a rewarding challenge to build.

   - **A webchat app**: Because currently I don't know how to work with websockets.
   - **Improving my current projects**: There are things I can improve of how I tackle new problems and issues.

**Thoughts:** I know that I don't need a perfect plan from day 0, but a flexible one, due to my current schedule.
