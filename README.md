## <img src="https://github.com/user-attachments/assets/9659b3f8-1507-4860-b6b8-39f7b5a4d4f8" alt="drawing" width="30"/> Lighthouse Score

![image](https://github.com/user-attachments/assets/f7554901-5725-401d-a582-49b4ad89694e)

## My Goal With This Project

My goal was to simulate a professional work environment.

- I built this app using a [Next.js](https://nextjs.org/docs) [starter template](https://vercel.com/templates/next.js/image-gallery-starter), [Cloudinary API](https://cloudinary.com/documentation/transformation_reference) to manage the assets, and [Tailwind](https://tailwindcss.com/docs/installation) for the styling.
- I worked with tasks on a Kanban board using [Todoist](https://todoist.com/): [Screenshot Of Archived Board](https://github.com/user-attachments/assets/dfe84e7c-9938-4a0a-a72c-e1e5737c891f)
- I used feature branches and pull requests: [Pull Request Example](https://github.com/user-attachments/assets/6773d4ed-5648-465a-8035-cde7c3028c2d)

## How To Navigate This Project

- Responsive components using tailwind.
- Fetches items applying orientation transformation using Cloudinary API.
- Refetches items on breakpoints on carousel view as the Cloudinary API provides horizontal or vertical padding based on orientation on fetch.

## Why I Built This Project This Way

I set myself the goal of creating a presentable gallery website within a 1-week timeframe, with the deadline being my grandfather's anniversary.

- I intentionally used a template that uses Tailwind with the Cloudinary API already built-in as I set velocity as the highest priority for this project.
- For styling I installed a linter called prettier that sorts the elements and tailwind classes automatically.

## If I Had More Time I Would Change These

- Modify the template to support Video items using Cloudinary API. 
- Contribute my changes to the starter template as a pull request. <!-- The support for Video items was already broken when I used the template. -->
- Add authentication with a content management UI to easily add items on the site instead of on Cloudinary. <!-- Use tailwind to create UI and Cloudinary API to manage images -->
- Mocking Cloudinary http requests using Jest. <!-- To avoid external dependencies -->

## Usage

1. Fork this repository
2. Create a [Cloudinary account](https://cloudinary.com/users/register_free)
3. Set up your Cloudinary API configuration and your environment variables
4. Run ```npx install```
5. Run ```npx run dev```

### How To Add Images?

You can easily add images by:

1. logging in to your cloudinary account,
2. go to assets,
3. then folders,
4. and drag and drop them as you like.

> login > assets > folders

# License

All images and videos in this repository are licensed under a [Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International License][cc-by-nc-nd].

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/  
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png  
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg  

### Note

- **Images and Videos**: All images and videos in this repository are subject to the Creative Commons license mentioned above.  
- **Other Content**: If the repository includes other types of content (e.g., code), their license will be indicated separately if applicable.
