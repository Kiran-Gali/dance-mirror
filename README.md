# DanceMirror

DanceMirror is an AI-powered web application to help students learn dance by comparing their movements to a teacher’s uploaded video.

## Features
- Role-based login: Student, Teacher, Admin
- Real-time pose detection using TensorFlow MoveNet
- Pose comparison and similarity scoring
- Session handling and logout
- Easy deployment via GitHub Pages

## Usage
1. Open `index.html` in a browser to log in.
2. Depending on role, users are redirected to their dashboard.
3. Code is frontend-only (no server) and uses `localStorage` for session control.

## Deployment
To deploy:
1. Push this repo to GitHub.
2. Enable GitHub Pages under the repository's **Settings > Pages** section.
3. Select the `main` branch and `/ (root)` directory.
4. Access the app via your GitHub Pages URL.

## License
MIT License
