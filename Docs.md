# Pose-Bot <img src="###" width="80" height = "70" >

### Inspiration ⚡

<strong>Gender based crimes are highly prevalent in India. Most of the crimes don't get reported and are left unresolved. We wanted to do our part in making sure authorities are held accountable and can't get away with refusing to register or acknowledge cases.
</strong>

<p  align="center"><img height= "400" width = "800" src = "## Title Post ##"></p>

### What it does 🤖

In this era of Work From Home, when we are attending meeting continuously and stuck to our screens for long hours, this bot uses a image classifier from the teachable machine's <strong>Google API</strong> to detect user's posture and notifies the user to correct their posture or move away from the screen when they may not notice it.

<!-- First it extracts a certain number of tweets having hashtags related to crime against women, and supporting women. Once the tweets are retrieved, it performs sentiment analysis on them to figure out whether the tweets are spreading awareness about women crimes and empowering women or asking for immediate help and classifies them as 'positive' or 'negative', respectively. It retweets tweets and under tweets asking for help (negative), it tags authorities publicly to increase the visibility of the tweets and bring them to their notice. -->

### How We built it 💡

1. We used the Teachable Machine's Tensorflow.js API to train our model to classify user's pose, proximity to screen and if the user is holding a phone.
2. For training our model we used our own image as the train data and tested it in different settings.
3. This model is then used to classify the users video feed to assess their pose and detect if they are slouching or if they are too close too screen or are sitting in a generally a bad pose.
4. If the user sits in a bad posture for a few seconds then the bot sends a notificaiton to the user to correct their posture or move away from the screen.
5. The website UI/UX was designed using Figma and then developed using HTML, CSS and JavaScript.Tensorflow.js was used to detect pose and JavaScript API to send notifications.

### Challenges we ran into 🧠

- Creating a model with good acccuracy in a general setting.
- Reverse engineering the Teachable Machine's Web Plugin snippet to aggregate data and then display notification at certain time interval.

### Accomplishments that we are proud of 😌

We created a completely functional posture bot, which can make a small difference in in our everyday health. We successfully made the website display system notifications which can be viewed across system even in different apps.

### What we learned 🤩

We learned how to how to ... To be Completed.

### What's next for Pose-Bot 📈

#### ➡ Tag authorities based on the geographic location

Currently the bot uses the webpage .

#### ➡ Improve the sentiment analysis model

The accuracy of the sentiment analysis model can be increased in the future.

#### ➡ Extend the bot to other crime genres

Fembot mainly focuses on gender related crimes and more prominently those against women. This model can be used for other genres of crime and be made more inclusive for other communities.

### Help File 💻

- [x] Clone the repository to your local directory
- `git clone https://github.com/cryptus-neoxys/posture.git`

- [x] `npm i -g live-server`
- Install live server to run it locally

- [x] `live-server .`
- Go to project directory and launch the website using live-server

- [x] Voilla the site is up and running on your PC.

- [x] Ctrl + C to stop the live-server!!

### Built With ⚙

- [x] HTML
- [x] CSS
- [x] Javascript
  - Tensorflow.js
- [x] Deployed on Vercel

### Try it out 👇🏽

- 🤖 [Tensorflow.js Model](https://teachablemachine.withgoogle.com/models/f4JB966HD/)
- 🕸 [The Website](https://Pose-Bot.vercel.app/#home)
- 🖥 [The Figma Prototype](https://www.figma.com/file/utEHzshb9zHSB0v3Kp7Rby/Untitled?node-id=0%3A1)

### 3️⃣ Cheers to the team 🥂

- [Apurva Sharma](https://github.com/Apurva-tech)
- [Aniket Singh Rawat](https://github.com/dikwickley)
- [Dev Sharma](https://github.com/cryptus-neoxys)
