# Matt Gannon's Demo Project

![MIT license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)![](https://badges.aleen42.com/src/javascript.svg)![React](https://badges.aleen42.com/src/react.svg)![Redux](https://badges.aleen42.com/src/redux.svg)![Node](https://badges.aleen42.com/src/node.svg)![npm](https://badges.aleen42.com/src/npm.svg)![Visual Studio](https://badges.aleen42.com/src/visual_studio.svg)![ESLint](https://badges.aleen42.com/src/eslint.svg)![Webpack](https://badges.aleen42.com/src/webpack.svg)

## About 📝

I have created this full-stack JavaScript demo project using the MERN stack (Mongo, Express, React, Node).

The project can be run locally using `npm run dev`. This will start a node server on port 5000 and a React client on port 3000.

## Tech used ✨

### API

- Node server - `/server.js`
- Auth middleware (inc. JWT verification) - `/middleware/auth.js`
- Mongo / mongoose data entity models - `/models/*`
- CRUD functionality - `/routes/api/items.js`
- Bcrypt password hashing and JWT creation - `/routes/api/users.js`
- Bcrypt password matching and JWT creation - `/routes/api/auth.js`

### Client

- Redux reducers (inc. localStorage) - `/client/src/reducers/*`
- Redux actions (inc. axios and JWT) - `/client/src/actions/*`
- Redux store (inc. thunk) - `/client/src/store.js`
- Components (inc. PropTypes) - `/client/src/components/*`

## To do 📚

- <del>Update readme</del>
- Deploy to web
- Add tests

## Contact 🚀

You can reach me at https://mattgannon.co.uk
