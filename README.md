CineSphere: Your Personal Universe of Film.

CineSphere is a full-stack, responsive web application built with the MERN stack (MongoDB, Express.js, React, Node.js) designed for true movie enthusiasts. Move beyond basic streaming queues and dive deep into the world of cinema.

Discover Your Next Favorite Film: Use our powerful, intuitive filters to explore movies by genre, year, cast, crew, and keywords. Unearth hidden gems you won't find on popular platforms.

Curate & Share Your Experience: Create personalized watchlists, log the films you've seen, and rate and review them. Build your digital film library and share your curated lists with friends.

A Wealth of Information at Your Fingertips: Access detailed information including plot summaries, cast and crew biographies, high-quality trailers, and user-generated reviews—all in one sleek, ad-free interface.

CineSphere isn't just a database; it's a connected community for exploring, discussing, and celebrating the art of film. Start your journey today.

<h2>Installation</h2>
Use the package manager [npm](https://www.npmjs.com/) to install CineSphere.

Fork the Project by using:

```bash
git clone https://github.com/orifmilod/iCinema.git
```

then cd into the project by using:

```
cd iCinema
```

Now, Install the packages by running:

```bash
npm run setup
```

Run project with command

```bash
npm run dev
```

<h2> Built with  </h2>
<ul>
  <li>FrontEnd: <b> React.JS, Redux Library, Bootstrap, HTML/CSS </b></li>
  <li>Backend:  <b> Node.JS, Express.JS </b> </li>
  <li>Database: <b> MongoDB, Mongoose </b> </li>
</ul>

<h2> Features </h2>
<ul>
  <li> Sign In / Sign Up / Sign Out the user. </li>
  <li> Recieving a welcoming email when sign-up using Nodemailer. </li>
  <li> Add a new movie to the list.</li>
</ul>

<h2> API </h2>

<h4> Users </h4>
<ul>
  <li> <b>POST</b> /api/auth/signUp </li>
  <li> <b>POST</b>  /api/auth/signIn  </li>

   <li> <b>PATCH</b>  /api/users/:userId  </li>
  <li> <b>DELETE</b>  /api/users/:userId </li>
</ul>

<h4> Movies </h4>
<ul>
  <li> <b>GET</b> /api/movies</li>
  <li> <b>GET</b> /api/movies/:movieId</li>
  <li> <b>POST</b> /api/movies/addMovie</li>
  <li> <b>PATCH</b> /api/movies/:movieId</li>
</ul>

<h4> Genres </h4>
<ul>
  <li> <b>GET</b> /api/genres </li>
</ul>
