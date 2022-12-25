# NextJS-Template-Blog

Credit: [@ravinder-Olivier](https://github.com/ravinder-Olivier) [![Dependency Review](https://github.com/ravinder-Olivier/NextJS-Template-Blog/actions/workflows/dependency-review.yml/badge.svg)](https://github.com/ravinder-Olivier/NextJS-Template-Blog/actions/workflows/dependency-review.yml)

## Getting Started

```bash
# Clone the repository 
git clone https://github.com/ravinder-Olivier/NextJS-Template-Blog.git

# cd into the directory
cd NextJS-Template-Blog

# Install dependancies
npm install --include-dev

# Run the program
npm run dev
```

## Writing Posts

Posts are stored in the /posts directory
### Format

Posts should follow this format explicitly
![Screen Shot 2022-08-25 at 11 46 09 AM](https://user-images.githubusercontent.com/77025041/186744323-7b764ace-4c06-49c2-a3da-a6744e7a59a4.png)

The first lines of code on the top will not show in the users view, it's only for the backend funcionality of the article thumbnails and meta; more info at [Github.com/jonschlinkert/gray-matter](https://github.com/jonschlinkert/gray-matter)

### Images

Upload images for your posts in the public/images/  directory
Suggested naming conventions:
- mm-dd-yy
- mm-yy-articlename


## Customization

You can edit the favicon in /public/images, and can change the header and footer in /components/layout.js.
