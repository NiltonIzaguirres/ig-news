<h1 align="center">
    <a href="#">📖 Ig.news </a>
</h1>

<h1 align="center">
    <img alt="Ig.news Preview" src="https://cdn.discordapp.com/attachments/880027077884137492/909811219714699284/ezgif.com-gif-maker.gif" />
</h1>


<h4 align="center"> 
	 Status: Finished
</h4>

<p align="center">
 <a href="#about">About</a> •
 <a href="#tech-stack">Tech Stack</a> • 
 <a href="#author">Author</a> • 
 <a href="#how-to-contribute">Contribute</a> •
 <a href="#user-content-license">License</a>

</p>


<h2 id="about">❓ About</h2>

 📖 Blog with subscription template

### 💬 Pre-requisites

Before you begin, you will need to have the following tools installed on your machine:

[Git](https://git-scm.com).
In addition, it is good to have an editor to work with the code like [VSCode] (https://code.visualstudio.com/)


#### 💿 Running the web application

```bash

# Clone this repository
$ git clone https://github.com/NiltonIzaguirres/ig-news.git

# Access the project folder in your terminal
$ cd ig-news

# Create a file called .env.local with the settings below:

# Stripe config
NEXT_PUBLIC_STRIPE_PUBLIC_KEY=
STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=
STRIPE_SUCCESS_URL=
STRIPE_CANCEL_URL=
# Github config
GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=
# FaunaDB config
FAUNADB_KEY=
# Prismic config
PRISMIC_ENDPOINT=
PRISMIC_ACCESS_TOKEN=

# Install the dependencies
$ npm install

# Run the application in development mode
$ npm run dev

# The application will open on the port: 3000 - go to http://localhost:3000

```

---

<h2 id="tech-stack">🛠️ Tech Stack</h2>

The following tools were used in the construction of the project:

#### **Website**  ([NextJS](https://nextjs.org)  +  [TypeScript](https://www.typescriptlang.org/))

> See the file  [package.json](https://github.com/NiltonIzaguirres/ig-news/blob/main/package.json)


---

<h2 id="how-to-contribute">🤔 How to contribute</h2>

1. Fork the project.
2. Create a new branch with your changes: `git checkout -b my-feature`
3. Save your changes and create a commit message telling you what you did: `git commit -m" feature: My new feature "`
4. Submit your changes: `git push origin my-feature`

---

<h2 id="author">🧒🏽 Author</h2>

  <a href="https://github.com/NiltonIzaguirres">
    <img style="border-radius: 50%;" src="https://github.com/NiltonIzaguirres.png" width="100px;" alt="Nilton Izaguirres"/>
    <br />
    <sub><b>Nilton Izaguirres</b></sub>
  </a>
 <br />

<a href="https://www.linkedin.com/in/nilton-izaguirres">
  <code><img alt="My linkedin" width="28" src="https://www.flaticon.com/svg/static/icons/svg/1383/1383262.svg" /></code>
</a>

<a href="mailto:niltonizaguirres2003@gmail.com">
  <code><img alt="My e-mail" width="32" src="https://www.flaticon.com/svg/static/icons/svg/324/324123.svg" /></code>
</a>


---

<h2 id="user-content-license">📄 License</h2>

This project is under the license [MIT](./LICENSE).
