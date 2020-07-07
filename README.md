<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" style="width: 100%;"/>

<h3 align="center">
  Challenge: Node.js Concepts
</h3>

## :rocket: About the challenge

In this challenge, you must create a application to practice what you have learned in Node.js!

Thils will be an application to storage repositories of your portfolio, that will allow you to list, update, and delete repositories, and besides that, the repositories can also receive likes.

### Application Routes

- **`POST /repositories`**: The route must receive `title`, `URL`, and `techs` inside of the request body. The URL must be the link to the Github of that repository. When registering a new project, it must be stored inside an object in the following format: `{id:" uuid ", title: 'Desafio Node.js', URL: 'http: //github.com / ...' , techs: ["Node.js", "..."], likes: 0} `; Make sure the ID is a UUID, and always start likes as 0.

- **`GET /repositories`**: The route that lists all repositories;

- **`PUT /repositories/:id`**: The route should only change the `title`, `URL` and `techs` of the repository that has the` id` equal to the `id` present in the route parameters;

- **`DELETE /repositories/:id`**: The route must delete a repository with the `id` present in the route parameters;

- **`POST /repositories/:id/like`**: The route must increase the number of likes from the specific repository chosen through the `id` param present in the route parameters, at each call of this route, the number of likes must be increased by 1;



## :memo: Licence

This project is under license from MIT. See the archive [LICENSE](LICENSE) to more details.

---
Made with 💜 by Fabio Menozzi <a href="https://www.linkedin.com/in/menozzi-fabio" target="_blank">Fabio Menozzi</a>
