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

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 Note]()

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

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 Note]()

### Day 47: April 24, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** Today I learned about the `Omit<TypeName, "key or value to omit"` and applied it in the current project of `diario-vuelo-Ilari`. Also, I learned a bit of how to detect the subfiles in `ts-node-dev`. Mainly you have to set the **directory to watch**, like `src/`, not the `--watch` or `--exit-child` flags.

  Link to the repos used:

  1. [diario-vuelo-Ilari](https://github.com/Lenoxo/diario-vuelo-Ilari)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 Note]()

### Day 46: April 23, 2024

**Today's Progress**:

- **Learning Typescript:** Today I continued learning more about Typescript, on how the json imports as modules works, practicing with the diario-vuelo-Ilari project.

  In one sentence, the json import recommendation is that, when you work with modules in the project, name the files differently, even if the extension is not the same. Because the `.js` files are imported first than the `.json` ones thanks to the alphabetic order.

  Link to the repos used:

  1. [diario-vuelo-Ilari](https://github.com/Lenoxo/diario-vuelo-Ilari)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 Note]()

### Day 45: April 22, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** Today I continued improving one of my first projects, YardSale, fixing errors with the last element I added, which is the search bar.

  Link to the repos used:

  1. [exercises repo - YardSale](https://github.com/Lenoxo/YardSale)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 Note]()

### Day 44: April 21, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** Today I continued improving one of my first projects, YardSale, connecting it with more pages and fixing the dark mode functionality. Also I learned about the `<select>` element and how to style it.

  Link to the repos used:

  1. [exercises repo - YardSale](https://github.com/Lenoxo/YardSale)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 Note]()

### Day 43: April 20, 2024

**Today's Progress**:

- **Practicing with Personal Projects:** Today I advanced improving one of my first projects, YardSale, connecting it with more pages and fixing visual bugs mainly.

  Link to the repos used:

  1. [exercises repo - YardSale](https://github.com/Lenoxo/YardSale)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 Note]()

### Day 42: April 19, 2024

**Today's Progress**:

- **Learning Typescript:** Today I advanced completing exercise 9.9, connecting the backend endpoint to the patientor frontend in `/ping` when making a request from the frontend

  Link to the repos used:

  1. [exercises repo - backend](https://github.com/Lenoxo/backend-typescript-fullstack-open)
  2. [patientor fork - frontend](https://github.com/Lenoxo/patientor)

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 Note]()

### Day 41: April 18, 2024

**Today's Progress**:

- **Learning Typescript:** Today I advanced Practicing with exercises 9.8, creating a little server using `Express.js` which responds to requests in `/api/ping` endpoint.

  Also related to with that practice, I learned the basics of how to configure a project using `tsconfig.json` and `ts-node-dev` `ts-node`.

  Link to the repos used:

  1. [diario-vuelo-Ilari](https://github.com/Lenoxo/diario-vuelo-Ilari)

  2. [exercises repo](https://github.com/Lenoxo/backend-typescript-fullstack-open)

  <!-- TODO: Update thoughts with the May 1 Note here -->

**Thoughts**: I'll give explanations of why I stopped taking notes in this diary until now in the [May 1 Note]()

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
