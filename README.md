# VG Direct

VG Direct is a web application designed to provide video game information, user reviews, and a community forum for discussions.

## Live Links

- **Frontend Render**: [VG Direct Frontend](https://vg-direct-frontend.onrender.com/)

## Repositories

- **Frontend Repository**: [vg-direct-frontend](https://github.com/aladamm78/vg-direct-frontend)
- **Backend Repository**: [vg-direct-backend](https://github.com/aladamm78/vg-direct-backend)

## API Used

- **RAWG Video Games Database API**: [RAWG API Documentation](https://rawg.io/apidocs)

## Project Description

This project was initially developed in a single directory but has since been split into two separate repositories for frontend and backend components. The original combined directory has been retained for fallback purposes. This separation ensures a more modular architecture and better maintainability.

### Notes on Render Hosting

Currently, VG Direct is hosted on the free tier of [Render.com](https://render.com/). While this provides accessible hosting, it does come with some limitations:

- Free Render instances are slower and may timeout quickly if inactive.
- To ensure smooth operation, **load the backend first** in a browser tab and then open the frontend immediately afterward. This keeps both services active simultaneously.

#### Known Issues

Reloading the page when not on the homepage may throw a "404 Not Found" error. I believe this is due to the free tier of Render.com, as it lacks consistency in its hosting services. During testing, I found that this issue occurs randomly and without a clear pattern. Thank you for your patience if you encounter this.

### Running the Project Locally

If you encounter issues with the hosted versions, you can run the project locally using the following instructions:

#### Original Combined Code

1. Navigate to the project directory.
2. Start the backend server:
   ```bash
   node server.js
   ```
3. Start the frontend:
   ```bash
   npm start
   ```
## Troubleshooting

If you encounter any difficulties, feel free to report issues via the repositories listed above. Thank you for your understanding and patience while using this project!

---

**Maintainer**: Adam (GitHub: [aladamm78](https://github.com/aladamm78))
