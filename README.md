# social-media

## Description

A REST API for a social media app. Built with Express, Mongoose, and MongoDB.

## User Story

**As a** social media startup, **I want** an API for my social network that uses a NoSQL database **so that** my website can handle large amounts of unstructured data.

## Usage

1. Make sure you have MongoDB installed on your machine (if you don't, follow the instructions on the [MongoDB Website](https://docs.mongodb.com/manual/installation/))
2. Clone the repo
3. Install dependencies with `npm -i`
4. Run `npm start` to run the server and make the API live
5. Use [Insomnia](https://insomnia.rest/) to test the REST API.

## Models

- User
- Thought
- Reaction

## Endpoints
**User**

- Get all users:        `GET /api/users`
- Create a user:        `POST /api/users`
- Get user by ID:       `GET /api/users/:id`
- Update a user:        `PUT /api/users/:id`
- Delete a user:        `DELETE /api/users/:id`
- Add a friend:         `PUT /api/users/:userId/friends/:friendId`
- Delete a friend:      `DELETE /api/users/:userId/friends/:friendId`

**Thought**

- Get all thoughts:     `GET /api/thoughts`
- Create a thought:     `POST /api/thoughts`
- Get thought by ID:    `GET /api/thoughts/:id`
- Update a thought:     `PUT /api/thoughts/:id`
- Delete a thought:     `DELETE /api/thoughts/:id`

**Reaction**

- Add a reaction:       `PUT /api/thoughts/:id/reactions`
- Delete a reaction:    `DELETE /api/thoughts/:id/reactions`

## Packages

- express
- moment
- mongoose

## Contributing

Contributions are part of this open source project. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/name-of-feature`)
3. Commit your Changes (`git commit -m "Add some feature"`)
4. Push to the Branch (`git push origin feature/name-of-feature`)
5. Open a Pull Request


## Questions

- GitHub - [griffondean](https://github.com/griffondean/)
- Linkedin - [Griffon Dean](https://www.linkedin.com/in/griffon-dean-433088111/)
- Project Repository Link: https://github.com/griffondean/book-search

[Back To Top](#book-search)

---