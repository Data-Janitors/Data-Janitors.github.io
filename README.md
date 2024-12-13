# Data Janitors
## https://data-janitors.github.io/
<!--TODO: Add Data Janitors logo and relevant tech icons.-->

<div style="text-align: center;">

  ![Static Badge](https://img.shields.io/badge/React-61DBFB?style=for-the-badge&logo=react&labelColor=black)
  ![Static Badge](https://img.shields.io/badge/TypeScript-1D4ED8?style=for-the-badge&logo=typescript&labelColor=black)

</div>

## To get started with editing the website's contents, you can follow this steps: 

### 1. Install Node.js 

If you don't have Node.js installed already, you can download and install the LTS version from [Node.js](https://nodejs.org) 

After installation, verify the installation by running:

```bash
node -v
npm -v
```

### 2. Clone the Repository 

Clone this repository to your local machine by running the following command: 

  ```bash
  git clone https://github.com/data-janitors/data-janitors.github.io/
  ```

### 3. Navigate to the Project Directory

Once you have successfully cloned the repository to your local machine, move into the project directory by running the following command:

  ```bash
  cd data-janitors.github.io
  ``` 

### 4. Install Dependencies

Once inside the project directory, run the following command to install all the required npm packages:

  ```bash
  npm install
  ```

### 5. Start the Development Server

To run the website locally, run the following command: 

  ```bash
  npm run dev
  ```
This will start the website, and you can view it at http://localhost:5173.

### 6. Build and Preview the Website

To build the project, run:

  ``` bash
  npm run build
  ```

To preview the production build, run:

  ```bash
  npm run preview
  ```

### 7. Deploy changes 

This project uses the `gh-pages` npm package for deploying to GitHub Pages.

After making any changes to the website and ready to deploy the changes, run the following command.

  ```bash
  npm run deploy
  ```

  This will automatically build the project and push the production files to the gh-pages branch, which is used by GitHub Pages to host the website.