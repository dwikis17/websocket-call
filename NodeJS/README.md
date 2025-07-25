# NodeJS WebRTC Signaling Server

This is a Node.js signaling server for WebRTC.

## Deploying to Render

1. Push your code to a GitHub repository.
2. Create a new Web Service on [Render](https://render.com/).
3. Connect your repository.
4. Render will detect the `render.yaml` and use the following commands:
   - **Build Command:** `npm install`
   - **Start Command:** `node app.js`
5. Set any required environment variables in the Render dashboard.

## Local Development

```bash
npm install
node app.js
```

## Project Structure
- `app.js`: Main application entry point
- `package.json`: Project dependencies and scripts
- `render.yaml`: Render deployment configuration
- `.gitignore`: Files and directories to ignore in git 