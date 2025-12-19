+++
title = "Top Four"
+++


[Directory](#directory) • [Add](#add-your-top4-page) • [Remove](#remove-your-top4-page) • [Ideas](#top-4-list-ideas)

## What is an /top4 page?

A **/top4** page is a personal webpage where you can share your definitive ranked list of your top 3 favorites and an honorable mention. In a specific topic, such as movies, albums, snacks, games, or anything else you feel strongly about. 

Inspired by the fun, opinionated style of ranking things in fours, it allows you to express your tastes clearly and concisely while inviting discussion and debate. 

You can add a **/top4** page to your personal website as a lightweight and engaging way to share more about yourself beyond the usual /about or /now pages.

---


## Directory

{{ directory() }}

---

## Add your /top4 page

If you have an account on [GitHub](https://github.com), please follow the steps below. If not, or if you run into any issues, feel free to [reach out](mailto:hi@topfour.net) to me.

### 1. Go to the data file

[Go to data file...](https://github.com/peterspath/topfour.net/blob/main/data/data.json)


### 2. Edit file

Click on the edit (pencil) button. GitHub will prompt you to fork the repository under your own user so that a Pull Request can be made.

[Learn more about Pull Requests.](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)


### 3. Add your /top4 page

Add the following to the data file, replacing the values with your own: 

```
{ "name": "Example", "url": "https://example.com/top4/", "emoji": "🍕", "category": "Pizza", "number1": "Hawaii", "number2": "Pepperoni", "number3": "Brooklyn", "number4": "Chicago" },
```

Do not forget the trailing comma. Unless you are the last entry. It does not matter where you add your addition in the file. It will be sorted alphabetically,

### 4. Commit file

Commit the file, and if you could be so kind, set the Commit Message to something that helps me understand what your commit is doing.

Example: "added: Example to the directory"

### 5. Create Pull Request

GitHub will then prompt you to create a Pull Request against the original repository. Do so and you are all set!

### 6. Review

Submissions will be reviewed as quickly as possible, and when your Pull Request is merged, your website will appear in the directory above!

### 7. Link back

It would be awesome if you link back to this website from your **/top4** page. This way your readers can discover Top 4's from other people.

---

## Remove your /top4 page

If for any reason you wish to remove your **/top4** page from the directory, you can follow the above steps, but instead of *adding* a new line to data file, *delete* your respective line from the data file.

Only Pull Requests made by the same GitHub user that originally *added* the line to the data file will be merged, i.e. please do not request deletions on behalf of someone else.

If you want a maintainer to do this for you, please get [in touch](mailto:hi@topfour.net), and you will be asked to provide proof that you are the owner of the page before it is removed from the directory.

---

## Top 4 list ideas

- 🎥 Movies
- 🦹 Fictional Villains
- 📺 90s Cartoons
- 🚗 Road Trip Snacks
- 🍟 Fast Food French Fries
- 💿 Albums
- 🎮 Video Games
- 🥣 Breakfast Cereals
- 🍲 Comfort Foods
- 📚 Books
- 🖥️ Desk Setup Items
- ♟️ Board Games
- ☕️ Coffee Shop Orders
- 🍕 Pizza Toppings
- 🏁 Mario Kart Tracks
- 🏞️ National Parks
