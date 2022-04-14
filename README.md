# Parcel + Vercel

## Hosting

- Set up Git locally in your project
- Make sure your package.json doesn't have a "main" key and you have your "build" script (get these from this repo's package.json)
- BEFORE you add or commit
  - Set up your .gitignore file (get the value of this from this repo)
- Add, Commit
- Create a new GitHub repository
- Follow the steps for "Uploading an existing repo"
- Log in / sign up to Vercel
  - Go to your Dashboard and click "New Project"
  - Import the Parcel Github Repo
  - Set the framework preset to Parcel
  - Customize all of the Build and Output Settings
  - Build command is `npm run build`
  - Output directory is `dist`
  - Install command is `npm install`
