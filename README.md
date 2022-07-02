# my-community
Setup your community page in an instant and take your community to the next level!

```js
// MEME: how a community begins:
const community = new Community();
community.setRule("no memes in #general")
```

## 📖 Your community, your rules
Setup your rules simply and fast, no need to wait!

```py
com = Community(webhook="secret webhook url")
com.setRule("no memes in #general") # just a simple rule!
com.postRule()
```

## ✅ Create Tasks
Create tasks for your community to do!

```py
task = Task(com) # hands over your community
task.createTask(
    name="Spanish Time",
    description="Seems like you missed your lesson",
    completed=False # boolean
)
task.postTask()
```

## 📜 Easy for beginners
Are you a code begginer, or you have no coding experience? Introducing — `mycScript`!

(Yes, I'm really bad at naming)

### 🤖 Creating a bot has never been easier!
```yml
# Detects message "hi":
@message:hi
# replies "hello!":
send: hello!
# gives role and remove role:
giveRole: User
removeRole: Bot

```
### 🌐 Bad at HTML? We've got you covered! 
```yml
theme: default
[title]: Welcome To My Community!
[description]: This community is really epic!
[urlButton]
    text: Click here to join!
    url: https://discord.gg/invite-link
    newWindow: false
```
Translates to HTML:
```html
<h1>Welcome To My Community!</h1>
<p>This community is really epic!</p>
<a href="https://discord.gg/invite-link">
    <button>Click here to join!</button>
</a>
```
And even translates to Markdown:
```markdown
# Welcome To My Community!
This community is really epic!
[Click here to join!](https://discord.gg/invite-link)
```

## We can't wait to see what you will create!
What will you create? If I were you, I would create a huge chocolate bar and eat them all!

> [The Get Started Guide](/)

> [Learn How To Grow Your Community](/)

> [My Github!](https://github.com/AWeirdScratcher)

```js
const version = ["Latest", "Latest", "Latest"];
version.forEach((v) {
    console.log(`The only version is '${v}!11!!'`)
});
```
