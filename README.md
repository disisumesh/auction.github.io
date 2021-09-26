# Ipl-Auction

[![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://ipl-mega-auction.herokuapp.com/)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/67f92738bcce4a2c83e2b0885e3bf649)](https://www.codacy.com/gh/Coder-Srinivas/Ipl-Auction/dashboard?utm_source=github.com&utm_medium=referral&utm_content=Coder-Srinivas/Ipl-Auction&utm_campaign=Badge_Grade)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## Tech Stack 👨‍💻

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"> <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white">

## Inspiration

It began back during my childhood days, the urge to play the IPL Auction depicting real players. I used to team up with my friends and play the auction manually with a pen and paper, with a organizer to keep track. Over the last 1 year, I wondered, can I do anything to make my experience better? So I came up with the idea of building a IPL auction app, based on the MERN stack.

## What it does?

You can team up with your friends and dive into the fun world of auctioning IPL players. The application calulates the score generated by each team based on the performance of each player in the respective IPL year. The team with the most points wins. It's a fun application to experience the the real IPL Auction with friends. Simply create an account, gather your friends and jump staright into the auction.

## Rules

- Batsmen
  - Each run scored by a batsman accounts for one point
- Bowler
  - Each wicket taken by a bowler accounts for 25 points
- WicketKeeper
  - Each catch taken a wicketkeeper accounts for 2 points
  - Each stumping accounts for 5 points
- General
  - Each catch taken on the field accounts for 2 points

The team with the highest points in the auction wins.

## Steps to get the project running locally on your machine

#### Setting Up Environment Variables

1. Create a .env file in the backend directory
2. Initialize DEV_MONGO_URL to mongodb://localhost:27017/
3. Initialize DEV_REACT_URL to http://localhost:3000
4. Initialize DEV_SERVER_URL to http://localhost:8000
5. Initialize SECRET to a JWT secret key

#### Installing the dependencies

Run the following command in the root
of the project to install the packages
on the server side:

```
npm i
```

Run the following command in the root
of the project to install the packages
on the client side:

```
cd client
npm i
```

#### Running the project

Run the following command in the root
to get the client side and the server
side running concurrently:

```
npm run dev
```

## Note

Keep the monogodb database running locally before running the application.
