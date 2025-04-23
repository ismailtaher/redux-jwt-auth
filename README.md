# Redux JWT Auth (Frontend)

This is the **frontend** portion of a full-stack authentication system built with **React**, **Redux Toolkit**, and **RTK Query**. It supports **JWT authentication** with **access and refresh tokens**, automatic re-authentication, and protected routes using React Router.

> The backend is required for this app to work. You can use [gitdagray/redux_jwt_auth](https://github.com/gitdagray/redux_jwt_auth) or your own Express-based backend that exposes `/auth`, `/refresh`, `/logout`, and `/users`.

---

## Features

- JWT-based login with Redux state
- Access token refresh on 403 errors
- Protected routes using `<RequireAuth />`
- Logout support with state cleanup
- Ready for role-based authorization
- API calls with `fetchBaseQuery` via RTK Query

---

## Tech Stack

- React
- Redux Toolkit
- RTK Query
- React Router v7
- JavaScript (ES6+)

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ismailtaher/redux-jwt-auth.git
cd redux-jwt-auth
npm install
