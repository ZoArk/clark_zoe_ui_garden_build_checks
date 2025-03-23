 ## Garden UI Library & Web App
A React component library (clark_zoe_ui_garden_build_checks) packaged and deployed inside a Create React App (clark_zoe_ui_garden). This project includes:

 Reusable UI Components
 
 Pre-commit hooks with ESLint, Prettier, Jest
 
 GitHub Actions CI/CD workflow
 
 Dockerized production build (running on port 8018)

 # Clone the Repository
git clone https://github.com/ZoArk/clark_zoe_ui_garden.git

cd clark_zoe_ui_garden

# Install Dependencies
yarn install

# Start the App
yarn start

# Pre-Commit Checks
yarn lint  - Run ESLint

yarn format  - Format code

yarn test  - Run tests

# Build the Docker Container
docker build -t clark_zoe_coding_assignment13 .

# Run the Container
docker run -p 8018:80 --name clark_zoe_coding_assignment13 clark_zoe_coding_assignment13
