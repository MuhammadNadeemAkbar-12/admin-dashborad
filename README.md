# Chat Clone (WhatsApp-like) 🚀

## Project Overview
This is a lightweight chat application clone inspired by WhatsApp, built purely with **HTML**, **CSS (Bootstrap)**, and **JavaScript**. It simulates real-time chat functionality in the browser using `localStorage` for persisting users and message history. No backend is required.

## Features
- Add / delete users
- Send and receive chat messages (simulated)
- Persistent conversation history via `localStorage`
- Responsive UI using Bootstrap (works on mobile and desktop)
- Simple authentication stub (e.g., select or "login" as a user)
- Search/filter between conversations
- Input validation (e.g., empty message prevention)
- Timestamped messages
- User-friendly UI with conversation list and chat window

## Tech Stack
- HTML5
- CSS3 + [Bootstrap](https://getbootstrap.com/) for layout & responsiveness
- Vanilla JavaScript for logic and state management
- `localStorage` for client-side persistence

## Responsibilities / What This Repo Covers
- **UI Design:** Building a responsive chat interface with Bootstrap components (conversation list, message bubbles, input bar, user list).
- **Client-side Authentication:** Simulated login/selection of users without server-side logic.
- **State Management:** Storing users, active conversation, and messages in `localStorage`.
- **Chat Logic:** Sending, displaying, and timestamping messages; managing conversation context.
- **User CRUD:** Adding new users, deleting existing ones, and switching between them.
- **Persistence:** Ensuring chat history survives page reloads via `localStorage`.
- **Validation:** Preventing invalid inputs (e.g., blank messages or duplicate user names).
- **Responsiveness:** Ensuring layout adapts to various screen sizes using Bootstrap grid and utilities.
- **Search/Filter:** Allowing users to search for conversations or contacts (if implemented).
- **Code Organization:** Modular JavaScript for clarity (e.g., separation of DOM handling, storage helpers, UI rendering).

