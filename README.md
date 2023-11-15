# Outsourced Selling
Outsourced sales is the website of [outsourcedsales.com](https://outsourcedsales.com)

Outsourced Sales offers a solution for manufacturing and engineering companies, handling the marketing and selling of products and services. Their mission is to relieve businesses of the challenges associated with sales and marketing, allowing them to focus on core operations. Leveraging their own experience in manufacturing and engineering, they've optimized and automated the sales process, offering a results-driven approach to put sales on autopilot.

Outsourced Sales has successfully grown sales for manufacturing and engineering companies, providing a service that allows businesses to grow without the need for extensive time investment. By outsourcing sales, companies can avoid the hassle of training sales staff, managing additional personnel, and dealing with price negotiations. The focus is on helping businesses get paid what they deserve and grow without the need for in-depth knowledge of marketing and sales tactics.

The website explains the typical sales pipeline and outlines the reasons to outsource sales, emphasizing the decrease in overhead and boost in ROI. Outsourced Sales manages the entire sales process, putting sales on autopilot and eliminating the worry of how to sell. The approach is transparent, collaborative, and results-driven, with a month-to-month execution and the option for clients to continue, try something else, or opt-out.

The FAQ section addresses common questions about how Outsourced Sales can help businesses, collaboration with existing sales and marketing teams, the time to see results, measurement of marketing efforts, termination of services, cost, and alignment of marketing strategies with company goals. The blog features articles on topics like the power of a consistent website and social media presence, as well as leveraging outsourced sales for exponential business growth. The site encourages visitors to book a free consultation to receive a personalized sales strategy for their business.




<!-- GETTING STARTED -->
## Getting Started

You will first need to install the tools used to build the project namely
* Hugo - the static site generator
* NPM - the tool used to manage node module dependencies

### Prerequisites

To install Hugo and NPM, on a mac you can use brew
* npm
  ```sh
  brew install node
  ```
* Hugo 
  ```sh
  brew install hugo
  ```

**Clone Repository and open in VSCode**  
`git clone git@github.com:imobilize/outsourcedsales`

##### Install with NPM 
`npm install`
##### Install with Yarn
`yarn`

**To start developing:**
##### Develop with NPM 
`npm run start`
##### Develop with Yarn
`yarn start`

**To generate the site HTML:**
##### Build with NPM 
`npm run build`
##### Build with Yarn
`yarn build`

**npm run start** will run two commands parallel:  
`npx tailwindcss -i ./assets/css/main.css -o ./assets/css/style.css --watch`

Has paginated Categories and Tags. Markdown files will automatically convert images put into `/assets` folder to .webp images. 

## Image shortcodes for webp as well.
{{< imgh src="img-name.jpg" alt="Place alt text here." >}}

## Credits
4044ever - Original Theme
https://github.com/4044ever/Hugo-Tailwind-3.0.git

